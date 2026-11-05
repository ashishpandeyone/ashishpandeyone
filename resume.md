<div align="center">

# Ashishkumar Pandey

**Solutions Architect & Backend Engineer**<br>
AWS Serverless · Streaming & IoT Pipelines · OTT Platforms · Agentic AI

Mumbai, India · Remote or Mumbai hybrid · Available immediately

[![Email](https://img.shields.io/badge/Email-ashishpandeyone%40gmail.com-0f766e?style=flat-square&logo=gmail&logoColor=white)](mailto:ashishpandeyone@gmail.com)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-ashishpandeyone-0f766e?style=flat-square&logo=linkedin&logoColor=white)](https://linkedin.com/in/ashishpandeyone)
[![Website](https://img.shields.io/badge/Web-ashishkumarpandey.com-0f766e?style=flat-square&logo=googlechrome&logoColor=white)](https://ashishkumarpandey.com)
[![GitHub](https://img.shields.io/badge/GitHub-ashishpandeyone-0f766e?style=flat-square&logo=github&logoColor=white)](https://github.com/ashishpandeyone)

</div>

---

Backend engineer and solutions architect with nearly nine years in software, most of the recent ones on AWS serverless. I built the backend of an OTT streaming platform on my own, from concept to 1.2 million paid subscribers, with APIs held under 30 ms p95 and 18+ months without downtime. Since then I've architected IoT ingestion for 30,000+ smart meters. The problems I care about are the unglamorous ones: idempotency, late data, p95 budgets and the cloud bill.

<table>
<tr>
<td align="center" width="25%"><b>1.2M</b><br><sub>paid OTT subscribers on a backend I built solo</sub></td>
<td align="center" width="25%"><b>&lt;30 ms</b><br><sub>p95 API latency, held in production</sub></td>
<td align="center" width="25%"><b>18+ months</b><br><sub>zero downtime</sub></td>
<td align="center" width="25%"><b>30,000+</b><br><sub>smart meters on the IoT ingestion platform</sub></td>
</tr>
</table>

## Skills

| Area | Stack |
|---|---|
| **Languages** | TypeScript, JavaScript (ES6+), Node.js, SQL, Ruby |
| **AWS** | Lambda, API Gateway, DynamoDB, S3, Kinesis, Amazon MSK (Kafka), IoT Core, MediaConvert, CloudSearch, Timestream, Glue, Athena, CDK |
| **Architecture** | Serverless and microservices, event-driven systems, streaming and near real-time processing, time-series and lakehouse storage, multi-tenant isolation |
| **Identity & Security** | OAuth 2.0, OpenID Connect, X.509, TLS, IAM, RBAC |
| **Media & Delivery** | OTT platforms, MediaConvert transcoding pipelines, Akamai CDN, CloudFront |
| **Agentic AI** | Agents on AWS (serverless and EKS), agent evaluation and observability, AI governance |
| **Operations** | CI/CD, blue/green deployments, observability (X-Ray, logging, alerting), p95 budgets, cost governance |
| **Frontend & Mobile** | React, Redux, React Native, Electron, Ruby on Rails |

## Experience

### Career Break & Upskilling
<sub>Feb 2026 – Present</sub>

- Career break for personal commitments (Feb – Jul 2026); back to full-time engineering since Aug 2026.
- Joined Become a Solutions Architect (BeSA) Cohort 10, *Agentic AI: POC to Production on AWS*, mentored by AWS solutions architects.
- Passed AWS Certified AI Practitioner and published an open-source CDK construct library (below).

### Solutions Architect · KVell Dynamics
<sub>Aug 2024 – Jan 2026 · Mumbai</sub>

- Architected IoT ingestion for **30,000+ smart meters** and sensors over MQTT and HTTPS, with device registry, secure provisioning, multi-tenant data isolation and schema governance.
- Built near real-time streaming pipelines on AWS IoT Core, Kinesis, Amazon MSK (Kafka), Lambda and Apache Spark, with windowed aggregations, late-event handling and idempotent writes.
- Designed time-series and lakehouse storage on Timestream, InfluxDB and S3, with partitioning, SQL analytics in Glue and Athena, and lifecycle and retention policies.
- Delivered KPI analytics and alerting (consumption, anomalies, outages) through Grafana and QuickSight dashboards and notification workflows.
- Implemented end-to-end device security with X.509 certificates, TLS, IAM and RBAC, plus device shadow patterns and observability for high availability.

### Technical Architect & Lead Backend Engineer · Planet Marathi Group
<sub>Feb 2021 – Aug 2024 · Mumbai</sub>

- Architected an end-to-end OTT platform for web and mobile and **single-handedly built its microservices backend** on AWS serverless in Node.js and TypeScript, scaling to **1.2 million paid subscribers** globally.
- Designed REST APIs with rate limiting and idempotency that consistently met **sub-30 ms p95 latency**.
- Traced a ~700 ms p95 on the v1 catalog API to TLS and connection setup against MongoDB Atlas using AWS X-Ray; cached the connection pool as a stopgap, then moved the Lambdas into a VPC peered with the same-region cluster, cutting p95 to ~200 ms.
- Replaced a high-cost authentication vendor with an **in-house OAuth 2.0 / OIDC** identity layer, consolidating vendors and cutting third-party spend.
- Authored media ingestion specs for studios and built template-driven **MediaConvert** pipelines for high job fan-out; integrated Akamai CDN, Razorpay, Twilio and 2Factor.
- Kept the platform at **zero downtime for 18+ months** through CI/CD with blue/green deployments, resilient design and proactive observability.

### Programmer Analyst · BrandMusiq
<sub>Aug 2019 – Jun 2020</sub>

- Built a React and Redux PWA with IndexedDB offline audio caching for seamless playback, backed by a Ruby on Rails API serving tracks and metadata.

### Software Development Engineer · Valuefy Solutions
<sub>Sep 2018 – Aug 2019 · Mumbai</sub>

- Independently implemented **OCR-based KYC**, along with face verification with liveness detection and secure payment and SMS integrations.
- Mentored 3–4 engineers on Git, ES6, Node.js and Linux, and authored the team's build and deploy guidelines.
- Drafted the technical and architectural scope of RFP responses.

<details>
<summary><b>Earlier roles (2015 – 2018)</b></summary>

- **Software Engineer, BrandMusiq** (Jun 2017 – Aug 2018): built soniqspaces, a multi-track music player for Android and iOS in React Native, with a desktop version in Electron.
- **Lead Developer, Bridge Properties** (Oct 2016 – Apr 2017): designed the stack for the company website and API, and a CRM holding client history across projects.
- **Junior Software Engineer, FreeWave Tech-Solutions** (Nov 2015 – Jan 2016): full-stack Ruby on Rails apps, hybrid mobile apps in Ionic, and server DevOps.
- **Support Technician, Node Outlet** (Aug 2015 – Nov 2015): remote management of physical and virtual servers for hosting clients.

</details>

## Open Source

| Project | What it is | Signal |
|---|---|---|
| [**cdk-lambda-web-function**](https://github.com/ashishpandeyone/cdk-lambda-web-function) | AWS CDK L2 construct for Lambda Web Functions, with an API modelled on `aws-cdk-lib/aws-lambda`; one-flag CloudFront and multi-region endpoints. [npm](https://www.npmjs.com/package/@ashishpandeyone/cdk-lambda-web-function) · [write-up](https://ashishkumarpandey.com/blog/a-cdk-l2-construct-for-aws-lambda-web-functions) | 2,000+ npm downloads in its first three weeks |
| [**cdk-freedoom-lambda-web-functions**](https://github.com/ashishpandeyone/cdk-freedoom-lambda-web-functions) | Julian Wood's Freedoom-on-Lambda sample rebuilt on the construct above; six resources collapse into one construct | Reference example |
| [**react-native-flip-toggle-button**](https://github.com/ashishpandeyone/react-native-flip-toggle-button) | Cross-platform animated toggle for React Native, animations on the native driver | 22★ · 13 forks · ~4,000 npm downloads/year |
| [**notetaker**](https://github.com/ashishpandeyone/notetaker) | Least-privilege serverless notes API on API Gateway v2, Lambda, DynamoDB and Secrets Manager, in CDK | |

## Certifications

- **AWS Certified AI Practitioner (AIF-C01)**, Amazon Web Services, Sep 2026
- BeSA, 2026: AI Governance on AWS · Agentic AI Evaluation and Observability · Design Authentication, Authorization and Logging · Building Agentic AI on Amazon EKS · Building Agentic AI with AWS Serverless · Anatomy of an AI Agent

## Education

**B.Sc. Computer Science**, Birla College of Arts, Commerce and Science · Jun 2012 – Jun 2015

---

<div align="center"><sub>Phone number and PDF copy on request.</sub></div>
