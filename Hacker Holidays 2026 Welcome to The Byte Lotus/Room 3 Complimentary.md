# ☁️ Complimentary

## Description

**Complimentary** introduces a cloud security scenario centered around the Byte Lotus Hotel's guest wellness application. During the investigation, the application is found to rely on **Amazon Web Services (AWS)**, where anonymous users receive temporary cloud credentials through **Amazon Cognito**.

The challenge focuses on analyzing the application's client-side configuration, obtaining temporary AWS credentials, and understanding how misconfigured cloud permissions can expose sensitive data stored in **Amazon DynamoDB**.

---

## Objectives

* Analyze the web application's client-side configuration.
* Identify exposed AWS resources.
* Obtain temporary AWS credentials through Amazon Cognito.
* Investigate the assigned IAM permissions.
* Access data stored in Amazon DynamoDB.
* Understand the impact of excessive cloud permissions.

---

## Skills Learned

* AWS Cloud Security
* Amazon Cognito
* AWS IAM
* Amazon DynamoDB
* Temporary Security Credentials (STS)
* API Analysis
* Client-Side Reconnaissance
* Principle of Least Privilege

---

## Tools Used

* Web Browser
* Browser Developer Tools
* AWS CLI
* cURL
* Amazon Cognito
* Amazon DynamoDB

---

## Key Takeaways

* Client-side applications should never expose sensitive cloud configuration without proper security controls.
* Temporary credentials must be scoped with the principle of least privilege.
* Excessive IAM permissions can allow anonymous users to access data beyond their intended scope.
* Cloud security relies on correct identity management and permission boundaries, not on obscuring client-side configuration.

---

## Disclaimer

This write-up is intended for educational purposes only. All activities were performed within the authorized TryHackMe lab environment.
