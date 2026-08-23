# ☁️ AWS Data Engineering

<p align="center">
  <img src="https://img.shields.io/badge/AWS-Cloud%20Data%20Engineering-FF9900?style=for-the-badge&logo=amazonaws&logoColor=white" alt="AWS">
  <img src="https://img.shields.io/badge/IAM-Security-DD344C?style=for-the-badge&logo=amazonaws&logoColor=white" alt="IAM">
  <img src="https://img.shields.io/badge/S3-Data%20Lake-569A31?style=for-the-badge&logo=amazons3&logoColor=white" alt="Amazon S3">
  <img src="https://img.shields.io/badge/Glue-Data%20Integration-FF9900?style=for-the-badge&logo=amazonaws&logoColor=white" alt="AWS Glue">
  <img src="https://img.shields.io/badge/Athena-Serverless%20Analytics-232F3E?style=for-the-badge&logo=amazonaws&logoColor=white" alt="Amazon Athena">
  <img src="https://img.shields.io/badge/Redshift-Data%20Warehouse-8C4FFF?style=for-the-badge&logo=amazonredshift&logoColor=white" alt="Amazon Redshift">
</p>

<h3 align="center">A Hands-On AWS Data Engineering Foundation</h3>

<p align="center">
  Cloud Infrastructure • Data Storage • Serverless Processing • Observability • Analytics • Data Warehousing
</p>

---

## 🧭 Overview

This repository is a structured exploration of the AWS services and architectural concepts that form the foundation of modern cloud-based data engineering.

Rather than focusing on a single end-to-end application, the repository builds an understanding of the individual capabilities that come together to form a production-oriented data platform.

The progression moves from **identity and infrastructure** into **data storage and databases**, then into **serverless processing, monitoring, data integration, analytical querying, and cloud data warehousing**.

```text
                         AWS DATA ENGINEERING
                                  │
             ┌────────────────────┼────────────────────┐
             │                    │                    │
             ▼                    ▼                    ▼
        FOUNDATION             DATA LAYER          OPERATIONS
             │                    │                    │
       IAM • EC2 • VPC       S3 • RDS • Glue      CloudWatch
             │                    │                    │
             └────────────────────┼────────────────────┘
                                  │
                                  ▼
                             ANALYTICS
                                  │
                         ┌────────┴────────┐
                         ▼                 ▼
                      Athena           Redshift
