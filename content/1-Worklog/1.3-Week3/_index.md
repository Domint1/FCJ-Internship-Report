---
title: "Week 3 Worklog"
date: "`r Sys.Date()`"
weight: 1
chapter: false
pre: " <b> 1.3. </b> "
---


### Week 3 Objectives:

* Learn key tools used for the FCJ workshop.
* Install and use Hugo to build a documentation website.
* Practice writing content in Markdown.
* Understand introductory AWS services needed for hosting: S3, IAM, CloudFront.
* Prepare foundation for deploying the documentation website later.

### Tasks to be carried out this week:
| Day | Task | Start Date | Completion Date | Reference Material |
| --- | ---- | ---------- | ---------------- | ------------------ |
| 2 | - Install Hugo <br> - Learn Hugo folder structure: content/, themes/, layouts/ <br> - Create first Hugo site and run on local | 22/09/2025 | 22/09/2025 |
| 3 | - Write Week 1 & Week 2 content in Markdown <br> - Add pages to Hugo `content/` directory <br> - Test local rendering | 23/09/2025 | 23/09/2025 |
| 4 | - Learn S3 basics: creating bucket, uploading objects <br> - Understand static hosting (only the easy part) | 24/09/2025 | 24/09/2025 |
| 5 | - Learn basic IAM: Users, Policies, least-privilege concept <br> - Create a simple IAM user for S3 access | 25/09/2025 | 25/09/2025 |
| 6 | - Learn CloudFront basics (what is CDN, why it's used) <br> - Understand how CloudFront can be used later to host Hugo site via S3 | 26/09/2025 | 26/09/2025 | 

### Week 3 Achievements:

* Understood S3 core concepts: bucket, object, key, region, storage classes.
* Learned how S3 provides high durability and availability for stored data.
* Configured S3 security controls: Block Public Access and Bucket Policy.
* Successfully hosted a static website using S3 Static Website Hosting.
* Deployed a CloudFront distribution using S3 as the origin.
* Connected CloudFront to S3 using Origin Access Control to improve security and performance.
* Tested access via both S3 endpoint and CloudFront and observed the difference in behavior and latency.
