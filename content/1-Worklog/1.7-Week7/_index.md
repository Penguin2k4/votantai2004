---
title: "Week 7 Worklog"
date: 2026-06-15
weight: 1
chapter: false
pre: " <b> 1.7. </b> "
---

### Week 7 Objectives:
- **AI Development & Optimization:** Fix the screenshot bug when checking via URL. Integrate Domain Info extraction features such as: IP address detection, domain age, geographical location, and registrar information.
- **Model Fine-tuning:** Fine-tune the AI model to improve accuracy and optimize Phishing detection capabilities.
- **AWS Practice:** Continue researching and complete the contents in Module 5.

### Tasks to be implemented this week:

| Day | Task | Start Date | Completion Date | Reference Sources |
| --- | --- | --- | --- | --- |
| 2 | - **System Bug Fixing:**<br>&emsp;+ Review URL input processing source code.<br>&emsp;+ Completely fix the bug of failing to capture website screenshots when scanning. | 15/06/2026 | 15/06/2026 | |
| 3 | - **Domain Info Integration (Part 1):**<br>&emsp;+ Research and integrate APIs/Libraries (like Whois).<br>&emsp;+ Write scripts to extract information: IP Address, Geographical Location, and Registrar. | 16/06/2026 | 16/06/2026 | |
| 4 | - **Domain Info Integration (Part 2):**<br>&emsp;+ Extract Domain Age feature.<br>&emsp;+ Integrate all domain data into the common Data Pipeline as input for the analysis model. | 17/06/2026 | 17/06/2026 | |
| 5 | - **Model Fine-tuning:**<br>&emsp;+ Add new features extracted from Domain Info to the training dataset.<br>- **Practice Lab 28**: <br>&emsp;+ Create IAM User, Policy, and Role <br>&emsp;+ Perform Switch Roles <br>&emsp;+ Access EC2 console, create EC2, and edit Tags <br>&emsp;+ Policy Check <br>&emsp;+ Clean up resources. | 18/06/2026 | 18/06/2026 | [Lab28](https://000028.awsstudygroup.com/vi/)|
| 6 | - **Practice Lab 30**: <br>&emsp;+ Create Restriction Policy <br>&emsp;+ Create IAM Limited User <br>&emsp;+ Check IAM User permission limits <br>&emsp;+ Clean up resources <br>- **Practice Lab 33**: <br>&emsp;+ Create IAM (Policy, Role, Group, User) <br>&emsp;+ Create KMS key, S3 Bucket & Upload data <br>&emsp;+ Configure CloudTrail for logging <br>&emsp;+ Use Athena to query data <br>&emsp;+ Test & share encrypted data on S3 | 19/06/2026 | 19/06/2026 | [Lab30](https://000030.awsstudygroup.com/vi/3-createpolicy/)<br>[Lab 33](https://000033.awsstudygroup.com/vi/3-createpolicy/) |

### Week 7 Achievements:

* **AI/ML Project:**
  * Completely resolved the bug of failing to capture screenshots from URLs, ensuring a smooth and stable input data flow for the analysis process.
  * Successfully integrated the Domain Info extraction module. The system automatically collected important features as an evaluation basis, including: IP address, Domain Age, geographical location, and Registrar information.
  * Completed the AI model Fine-tuning step by adding the Domain Info feature set to the training dataset. Thanks to the combination of multi-dimensional analysis (Image, URL, and Domain Information), the model produced more accurate prediction results and significantly reduced the False Positive rate.

* **AWS Knowledge & Practice:**
  * Mastered permission management operations from basic to advanced. Proficiently created User/Role/Policy, switched roles (Switch Roles), as well as applied Restriction Policies and tested IAM User permission limits.
  * Successfully deployed comprehensive security and monitoring flows: Used KMS to encrypt data on S3 Buckets, configured CloudTrail to log all activities, and applied Amazon Athena to effectively query/analyze log data.
  * Always ensured compliance with the resource clean-up principle after each Lab to optimize system costs.