# Data Virtualization & Data Fabric Portfolio

## About This Repository
This repository showcases hands-on projects in **Denodo-based data virtualization**, **SQL/Python automation**, and **CI/CD-driven data integration workflows** — built to demonstrate practical, end-to-end data fabric engineering skills.

The work here reflects real-world patterns used in enterprise data integration: connecting heterogeneous sources, building reusable virtual views, automating deployments, and ensuring governed, secure data access.

## Background
I'm a Data Virtualization / Data Fabric professional with experience designing and deploying Denodo-based solutions for enterprise-scale data integration. My work typically spans:

- Designing and optimizing **Denodo virtual views and data models** using VQL
- Integrating **relational databases, data lakes, and custom sources** via connectors and JDBC drivers
- Building and maintaining **GitLab CI/CD pipelines** for automated build, deployment, and promotion of Denodo components across environments
- Applying **data governance, security, and role-based access controls**
- Using **SQL and Python** for data validation, automation, and workflow enhancements

This repository contains simplified, self-built versions of these patterns using public/sample data — recreated independently for demonstration purposes (no proprietary or client data/configurations are used).

## Projects in This Repository

| Project | Description | Tech Stack |
|---|---|---|
| `denodo-cicd-pipeline` | Automated deployment of Denodo view revisions across Dev/Test/Prod using GitLab CI/CD | Denodo, VQL, GitLab CI/CD |
| `data-virtualization-layer` | Unified virtual views across multiple heterogeneous sources (SQL DB, MongoDB, API/CSV) | Denodo, SQL, MongoDB |
| `python-data-automation` | Scripts for data validation, schema comparison, and workflow automation | Python |
| `sql-query-optimization` | Case study on identifying and resolving query performance issues | SQL |
| `snowflake-powerbi-dashboard` | End-to-end pipeline from raw data to Snowflake to a Power BI dashboard | Snowflake, Power BI |

*(Update this table as each project is added — each project has its own folder and README with setup details.)*

## Tech Stack Overview
- **Data Virtualization:** Denodo (Express Edition), VQL
- **Databases:** SQL, MongoDB, Snowflake
- **Automation/Scripting:** Python
- **CI/CD & DevOps:** GitLab CI/CD
- **Visualization:** Power BI

## Repository Structure
```
├── denodo-cicd-pipeline/
├── data-virtualization-layer/
├── python-data-automation/
├── sql-query-optimization/
├── snowflake-powerbi-dashboard/
└── README.md   (this file)
```

## Why This Repository
Most Denodo/data virtualization experience lives inside client environments and isn't publicly demonstrable. This repository exists to make that skill set visible — with working, self-contained examples that mirror real enterprise use cases.

## Contact
**Mohanavalli Devaraj**
Technical Consultant — Data Virtualization & Data Fabric
[www.linkedin.com/in/mohanavalli-devaraj-3953ab168] | [mececemohanavalli@gmail.com]
