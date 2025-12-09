---
title: "Week 8 Worklog"
date: "2025-12-08"
weight: 1
chapter: false
pre: " <b> 1.8. </b> "
---


### Week 8 Objectives:

* Build and export the Hugo documentation website.
* Learn how to prepare Hugo output for deployment.
* Deploy the static Hugo site to S3.
* Connect S3 → CloudFront for production hosting.
* Validate the website accessibility and performance.

---

### Tasks to be carried out this week:

| Day | Task | Start Date | Completion Date | Reference Material |
| --- | ---- | ---------- | ---------------- | ------------------ |
| 2 | - Review Hugo folder structure: layouts, themes, content <br> - Clean up unnecessary files and confirm final content for deployment | 27/10/2025 | 27/10/2025 | Hugo Docs |
| 3 | - Run `hugo` to generate the final static website in `/public` folder <br> - Inspect output (HTML, CSS, JS) to ensure no missing pages | 28/10/2025 | 28/10/2025 | Hugo Docs |
| 4 | - Upload Hugo `/public` folder to S3 bucket <br> - Enable static hosting for this bucket (if not already enabled) <br> - Test S3 website endpoint | 29/10/2025 | 29/10/2025 | AWS S3 Docs |
| 5 | - Update CloudFront distribution to point to the S3 bucket <br> - Deploy changes and verify availability through CloudFront domain | 30/10/2025 | 30/10/2025 | AWS CloudFront Docs |
| 6 | - Perform tests: <br>&emsp; + Check loading speed <br>&emsp; + Test error page <br>&emsp; + Check if all worklog pages are accessible <br> - Trigger a CloudFront cache invalidation for updated content | 31/10/2025 | 31/10/2025 | AWS CloudFront Docs |

---

### Week 8 Achievements:

* Successfully prepared the Hugo site for deployment using the `/public` folder.
* Exported and validated all generated static pages.
* Uploaded the complete Hugo site to an S3 bucket configured for static hosting.
* Connected S3 to CloudFront and verified that content is delivered globally.
* Tested the entire site through CloudFront and ensured fast loading and correct routing.
* Learned how to invalidate CloudFront cache to force content refresh after updates.

---
