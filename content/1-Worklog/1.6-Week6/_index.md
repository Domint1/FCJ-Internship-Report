---
title: "Week 6 Worklog"
date: "`r Sys.Date()`"
weight: 1
chapter: false
pre: " <b> 1.6. </b> "
---


### Week 6 Objectives:

* Learn API Gateway in more depth (REST API model).
* Understand how API Gateway handles methods, resources, and responses.
* Practice connecting API Gateway → Lambda → DynamoDB.
* Learn basic input validation, mapping templates, and HTTP status codes.
* Test API endpoints using browser, Postman, or curl.

---

### Tasks to be carried out this week:

| Day | Task | Start Date | Completion Date | Reference Material |
| --- | ---- | ---------- | ---------------- | ------------------ |
| 2 | - Learn API Gateway structure: Resources, Methods, Stages <br> - Understand GET vs POST behaviour | 13/10/2025 | 13/10/2025 | AWS API Gateway Docs |
| 3 | - Create a simple API with a `/test` endpoint <br> - Integrate API Gateway → Lambda using “Lambda Proxy Integration” | 14/10/2025 | 14/10/2025 | AWS API Gateway Docs |
| 4 | - Learn how API Gateway passes event input to Lambda <br> - Understand basic mapping: statusCode, headers, body | 15/10/2025 | 15/10/2025 | AWS Lambda Docs |
| 5 | - Connect API → Lambda → DynamoDB <br> - Use GET method to read an item from DynamoDB <br> - Return JSON response | 16/10/2025 | 16/10/2025 | AWS API + DynamoDB Docs |
| 6 | - Use POST method to write an item to DynamoDB via Lambda <br> - Test API using browser, Postman, or curl <br> - Review CloudWatch Logs for API/Lambda | 17/10/2025 | 17/10/2025 | AWS CloudWatch Docs |

---

### Week 6 Achievements:

* Gained solid understanding of API Gateway’s structure for REST APIs.
* Created an API with multiple resources and HTTP methods.
* Learned how API Gateway forwards events to Lambda using proxy integration.
* Successfully built a workflow: **API Gateway → Lambda → DynamoDB**.
* Used GET to read from DynamoDB and POST to write data through the API.
* Tested API endpoints using different tools and reviewed logs in CloudWatch.
* Built a stronger foundation for future serverless development (authentication, hosting, etc.).

---

