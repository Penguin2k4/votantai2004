---
title: "Create the Target Group"
date: 2026-07-22
weight: 11
chapter: false
pre: " <b> 5.3.11. </b> "
---

# Create the Target Group for Streamlit

The Target Group contains the destinations that receive requests from the ALB. For Fargate, ECS automatically registers the private IP address of each task.

## 1. Define the Target Group

Go to **EC2 → Target Groups**, choose **Create target group**, and configure:

- **Target type:** `IP addresses`
- **Target group name:** `malscanai-streamlit-tg`
- **Protocol:** `HTTP`
- **Port:** `8501`
- **IP address type:** `IPv4`
- **VPC:** `malscanai-vpc`

![Target Group configuration](/images/5-Workshop/5.3.11-Target-Group/target-group-create.png)

The target type is IP because Fargate uses `awsvpc`; tasks do not run on team-managed EC2 instances. Port `8501` matches the Streamlit container port.

## 2. Configure the health check

Under Health checks, select HTTP and use a path that returns a successful response from Streamlit.

![Health check configuration](/images/5-Workshop/5.3.11-Target-Group/health-check.png)

The ALB uses the health check to decide whether a task is ready to receive requests. A running container can still remain `Unhealthy` when the path or port is incorrect.

## 3. Review the attributes and create the Target Group

The initial deployment keeps health check thresholds close to their defaults for easier troubleshooting.

![Target Group attributes](/images/5-Workshop/5.3.11-Target-Group/target-group-attributes.png)

Do not register IP addresses manually. The ECS Service adds and removes task IPs automatically.

![Review the Target Group](/images/5-Workshop/5.3.11-Target-Group/target-group-review.png)

![Created Target Group](/images/5-Workshop/5.3.11-Target-Group/target-group-created.png)
