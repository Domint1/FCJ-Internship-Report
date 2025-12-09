---
title: "Week 11 Worklog"
date: "2025-12-08"
weight: 2
chapter: false
pre: " <b> 1.11. </b> "
---


### Week 11 Objectives:

* Learn the basics of cloud security for web applications.
* Understand AWS WAF and how it protects APIs and static websites.
* Learn common web attack patterns (SQLi, XSS, bad bots) at a beginner level.
* Create a simple WAF WebACL and attach it to CloudFront or API Gateway.
* Enable basic AWS Managed Rule Groups for quick protection.

---

### Tasks to be carried out this week:

| Day | Task | Start Date | Completion Date | Reference Material |
| --- | ---- | ---------- | ---------------- | ------------------ |
| 2 | - Learn basic web security concepts: <br>&emsp; + What attacks WAF can block <br>&emsp; + Layer 7 vs Layer 4 protection <br>&emsp; + OWASP Top 10 (simplified) | 10/18/2025 | 10/18/2025 | AWS Security Docs |
| 3 | - Learn AWS WAF components: <br>&emsp; + WebACL <br>&emsp; + Rules & Rule Groups <br>&emsp; + Action: Allow / Block / Count | 10/19/2025 | 10/19/2025 | AWS WAF Docs |
| 4 | - Create a WAF WebACL in console <br> - Attach the WebACL to CloudFront distribution (or API Gateway) <br> - Enable AWS Managed Rules (CommonRuleSet) | 10/20/2025 | 10/20/2025 | AWS WAF Managed Rules |
| 5 | - Add simple custom rules: <br>&emsp; + Block IPs <br>&emsp; + Block known malicious paths (/wp-admin, /xmlrpc.php) <br>&emsp; + Rate-based rule (beginner level) | 10/21/2025 | 10/21/2025 | AWS WAF Docs |
| 6 | - Test WAF behavior by sending sample requests: <br>&emsp; + Normal traffic (should pass) <br>&emsp; + SQL-like inputs (should be blocked by managed rules) <br> - Review logs in CloudWatch or WAF Dashboard | 10/22/2025 | 10/22/2025 | AWS WAF Logging |

---

### Week 11 Achievements:

* Understood the role of WAF in protecting cloud applications from common Layer 7 attacks.
* Learned AWS WAF structure and how WebACL, Rules, and Rule Groups work together.
* Successfully created a WAF WebACL and attached it to CloudFront or API Gateway.
* Enabled AWS Managed Rule Groups for protection against common exploits.
* Added simple custom rules such as IP blocking and path filtering.
* Performed basic testing of WAF to observe blocked requests and allowed traffic.
* Built core security fundamentals that will help secure the final project.

---
