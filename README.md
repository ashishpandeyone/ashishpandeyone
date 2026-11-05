## Ashish Pandey

Backend engineer and solutions architect, Mumbai. Nearly nine years building software, most of the recent ones on AWS serverless.

Most of my work has been in two places. OTT and media, where I built the backend of a streaming platform on my own at Planet Marathi and took it to 1.2 million paid subscribers: API Gateway, Lambda, DynamoDB, media pipelines on MediaConvert, and an in-house OIDC and OAuth 2.0 layer that replaced an expensive vendor. And IoT, where I architected ingestion for 30,000+ smart meters at KVell Dynamics, with near real-time pipelines on Kinesis and MSK and time-series and lakehouse storage behind them.

The problems I keep coming back to are the unglamorous ones. Idempotency when the same event arrives twice. Late data, and the gap between when something happened and when you heard about it. Holding p95 latency down without throwing money at the problem. Watching the bill.

These days I'm working on agentic AI on AWS. AWS Certified AI Practitioner, BeSA Cohort 10 on taking agents from POC to production, and the open-source work below.

### Worth a look

- [**cdk-lambda-web-function**](https://github.com/ashishpandeyone/cdk-lambda-web-function): an AWS CDK L2 construct for Lambda Web Functions, on [npm](https://www.npmjs.com/package/@ashishpandeyone/cdk-lambda-web-function). [Why I built it](https://ashishkumarpandey.com/blog/a-cdk-l2-construct-for-aws-lambda-web-functions).
- [**cdk-freedoom-lambda-web-functions**](https://github.com/ashishpandeyone/cdk-freedoom-lambda-web-functions): Freedoom running on Lambda Web Functions, rebuilt on that construct.
- [**react-native-flip-toggle-button**](https://github.com/ashishpandeyone/react-native-flip-toggle-button): an old React Native library that people still install.

### What's in here

A mix. The repos worth looking at are pinned. The rest is forks I've read through, old experiments, and things I built while learning something. I haven't deleted them, they just aren't representative.

[Resume](resume.md) · [ashishkumarpandey.com](https://ashishkumarpandey.com) · [linkedin.com/in/ashishpandeyone](https://linkedin.com/in/ashishpandeyone)
