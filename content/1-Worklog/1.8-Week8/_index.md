---
title: "Week 8 Worklog"
date: "`r Sys.Date()`"
weight: 1
chapter: false
pre: " <b> 1.8. </b> "
---


### Week 8 Objectives:

* Deploy the actual project frontend using AWS Amplify Hosting.
* Understand how Amplify automates build → deploy → host workflow.
* Connect Amplify with GitHub (or use manual upload if needed).
* Configure build settings, environment variables, and deployment rules.
* Test frontend → API Gateway → Lambda → DynamoDB integration.
* Prepare the application for further authentication and security features.

---

### Tasks to be carried out this week:

| Day | Task | Start Date | Completion Date | Reference Material |
| --- | ---- | ---------- | ---------------- | ------------------- |
| 2 | - Review project frontend code (React/Vue/Next/HTML) <br> - Ensure the project can run locally without errors <br> - Create production build locally | 27/10/2025 | 27/10/2025 | Project Source Code |
| 3 | - Learn AWS Amplify Hosting workflow: <br>&emsp; + How Amplify uses GitHub to build and deploy <br>&emsp; + Difference between Preview & Production builds <br>&emsp; + Deploy without Git (manual upload) | 28/10/2025 | 28/10/2025 | AWS Amplify Docs |
| 4 | - Connect GitHub repository to Amplify (preferred) <br> OR <br> - Upload build folder manually (if using static HTML) <br> - Configure build settings (`amplify.yml` auto-generated) | 29/10/2025 | 29/10/2025 | Amplify Console |
| 5 | - Configure project environment: <br>&emsp; + API endpoint URL (API Gateway) <br>&emsp; + Region <br>&emsp; + Any required environment variables <br> - Trigger a new Amplify build & wait for deploy | 30/10/2025 | 30/10/2025 | Amplify Console |
| 6 | - Test fully deployed frontend: <br>&emsp; + Frontend → API Gateway → Lambda → DynamoDB <br>&emsp; + Validate CORS configuration <br>&emsp; + Check HTTPS, caching, and static file loading <br> - Fix errors and redeploy if needed | 31/10/2025 | 31/10/2025 | AWS Docs |

---

### Week 8 Achievements:

* Successfully prepared the project frontend for production build.
* Learned how AWS Amplify automates hosting with CI/CD or manual deploy.
* Connected GitHub repository to Amplify (or used manual upload workflow).
* Configured environment variables and build settings for the application.
* Deployed the project frontend to Amplify and verified site availability.
* Tested full end-to-end flow: **Frontend → API → Lambda → DynamoDB**.
* Ensured the project is ready to integrate authentication and security in upcoming weeks.

---
