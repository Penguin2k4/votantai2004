---
title: "Week 4 Worklog"
date: 2026-05-25
weight: 1
chapter: false
pre: " <b> 1.4. </b> "
---

### Week 4 Objectives:

- **AI/ML Model Research & Training:** Experiment with a combination of Machine Learning (Random Forest, XGBoost) and Deep Learning (CNN) algorithms. Aim to optimize the model to achieve an Accuracy of over 83% with Dataset 1, while expanding testing on other datasets to evaluate generalizability.
- **AWS Professional Practice:** Complete all practice labs in Module 3.

### Tasks to be implemented this week:

| Day | Task | Start Date | Completion Date | Reference Sources |
| --- | --- | --- | --- | --- |
| 2 | - Learn about AWS Backup for the system <br> - **Practice Lab 13**:<br>&emsp;+ Create a backup plan <br>&emsp;+ Test operation <br>&emsp;+ Clean up resources <br> - **Practice Lab 24**: <br>&emsp;+ Create an S3 Bucket <br>&emsp;+ Create an EC2 for Storage Gateway <br>&emsp;+ Create a Storage Gateway <br>&emsp;+ Create File Shares | 25/05/2026 | 25/05/2026 | [Lab13](https://000013.awsstudygroup.com/vi/5-testrestore/) <br>[Lab24](https://000024.awsstudygroup.com/vi/5-testrestore/) |
| 3 | - Test machine learning and deep learning models such as Random Forest, XGBoost, and CNN, achieving 93%, 95%, and 92% respectively for phishing URL dataset 1.<br>- Test on dataset 2 (over 500k URLs) achieving 94% with XGBoost. | 26/05/2026 | 27/05/2026 | |
| 5 | **Practice Lab 57**: <br>&emsp;+ Create an S3 bucket <br>&emsp;+ Upload data <br>&emsp;+ Enable static website hosting <br>&emsp;+ Configure block public access <br>&emsp;+ Configure public objects <br>&emsp;+ Test the website <br>&emsp;+ Block all public access <br>&emsp;+ Configure Amazon CloudFront <br>&emsp;+ Test Amazon CloudFront <br>&emsp;+ Manage Bucket Versioning <br>&emsp;+ Move objects | 28/05/2026 | 28/05/2026 | [Lab57](https://000057.awsstudygroup.com/vi/10-s3ccr/) |
| 6 | - **Deploy and test the model:** <br>&emsp; + Deploy a simple UI <br>&emsp; + Test with 3 random URLs (achieved 33% accuracy rate) <br>&emsp; | 29/05/2026 | 29/05/2026 | |

### Week 4 Achievements:

* **Group Project:**
  * Far exceeded the initial target (83%), successfully training Phishing URL detection models with very high accuracy on Dataset 1: XGBoost (95%), Random Forest (93%), and CNN (92%).
  * Proven the model's generalizability and load capacity when testing on the large-scale Dataset 2 (over 500,000 URLs), with the XGBoost model still maintaining an impressive accuracy of 94%.
  * Initially completed the deployment of a basic UI to integrate the model and conduct practical testing (requires further optimization to improve the random detection rate).

* **AWS Knowledge:**
  * Completed Module 3 with in-depth knowledge of storage and backup.
  * **Lab 13 & 24:** Successfully configured AWS Backup (created a backup plan, tested restore) and set up a Storage Gateway to create a seamless file storage flow between the on-premises system and S3.
  * **Lab 57:** Mastered Amazon S3 storage service and CloudFront content delivery network (CDN). Practically configured a Static Website, managed access permissions (Public Access Block), enabled Versioning to protect data, and configured CDN to accelerate page load speed.
  * Proficiently managed block-level storage by successfully attaching an EBS volume.