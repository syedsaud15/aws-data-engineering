# ☁️ AWS Data Engineering

<p align="center">

### Cloud Infrastructure → Data Services → Observability → Analytics

<br>

![AWS](https://img.shields.io/badge/AWS-Cloud%20Engineering-FF9900?style=for-the-badge&logo=amazonaws&logoColor=white)
![IAM](https://img.shields.io/badge/IAM-Security-DD344C?style=for-the-badge&logo=amazonaws&logoColor=white)
![S3](https://img.shields.io/badge/S3-Storage-569A31?style=for-the-badge&logo=amazons3&logoColor=white)
![Glue](https://img.shields.io/badge/Glue-Data%20Integration-FF9900?style=for-the-badge&logo=amazonaws&logoColor=white)
![Athena](https://img.shields.io/badge/Athena-Analytics-232F3E?style=for-the-badge&logo=amazonaws&logoColor=white)
![Redshift](https://img.shields.io/badge/Redshift-Data%20Warehouse-8C4FFF?style=for-the-badge&logo=amazonredshift&logoColor=white)

</p>

> A structured AWS Data Engineering hands-on repository covering the cloud foundations required to design, operate, secure, monitor, and analyze modern data workloads.

---

# 🧭 What This Repository Is

This repository is not a single application or isolated ETL pipeline.

It is a **progressive AWS engineering environment** covering the services that form the foundation of cloud-based data platforms.

The learning path moves through four architectural layers:

```text
┌─────────────────────────────────────────────────────────┐
│                    CLOUD FOUNDATION                     │
│                                                         │
│   IAM → EC2 → VPC → RDS                                 │
└───────────────────────────┬─────────────────────────────┘
                            │
                            ▼
┌─────────────────────────────────────────────────────────┐
│                    DATA PLATFORM                        │
│                                                         │
│   S3 → Lambda → Glue                                    │
└───────────────────────────┬─────────────────────────────┘
                            │
                            ▼
┌─────────────────────────────────────────────────────────┐
│                 OBSERVABILITY & QUERY                   │
│                                                         │
│   CloudWatch → Athena                                   │
└───────────────────────────┬─────────────────────────────┘
                            │
                            ▼
┌─────────────────────────────────────────────────────────┐
│                    DATA WAREHOUSE                        │
│                                                         │
│                     Redshift                            │
└─────────────────────────────────────────────────────────┘
