# Progress Corticon Decision Management

[Progress Corticon](https://www.progress.com/corticon) enables domain experts to author, test, and deploy complex, explainable business rules without coding and run them anywhere—on servers, in clouds, serverless, browsers, mobile, and IoT. This page provides sample rule projects and demos for both Corticon Classic and Corticon.js.

👉 Try our interactive Corticon Knowledge Bot:

[![Try the Searcher](https://img.shields.io/badge/Corticon_Knowledge_Bot-Chat_now-success?style=for-the-badge\&logo=progress)](https://corticon.github.io/searcher/)

---

## Getting Started

1. **Author Rules** in [Corticon Studio](https://docs.progress.com/bundle/corticon-quick-reference/page/A-guide-to-Progress-Corticon-Studio.html) or [Corticon.js Studio](https://docs.progress.com/bundle/corticon-js-quick-reference/page/A-guide-to-Progress-Corticon.js-Studio.html).
2. **Explore Sample Repos** (see below) and import rule projects into your studio.
3. **Deploy**: Package a Decision Service to Corticon Server/Web Console (Classic) or build a JS bundle for browser, Node, or serverless (Corticon.js).
4. **Integrate**  via REST/SOAP, embedded Java/.NET, or JavaScript function calls depending on target runtime.

---

## Corticon Deployment Models


| Model | Deployment | Key strengths | Typical uses | Samples |
| :--- | :--- | :--- | :--- | :--- |
| **Corticon Classic** | Stateless Decision Services on Corticon Server; embed in Java/.NET; deploy on‑prem or cloud | Enterprise data integration, linear scalability, operational monitoring | High‑throughput transactional and batch, compliance, eligibility | Classic samples in this org |
| **Corticon.js** | Transpiled JS bundles for browser, Node, mobile, and serverless (FaaS) | Lightweight, offline, low‑latency, edge execution | In‑app decisions, dynamic forms, serverless APIs | Corticon.js samples in this org |

---

## Application Scenarios

- Compliance and policy automation with transparent explanations.
- Eligibility, benefits, and casework decisions for public sector and pensions.
- Underwriting, claims, loans, and fraud checks in financial services and insurance.
- Dynamic, rules‑driven forms that adapt in real time.
---

### Why Classic vs Corticon.js
- Choose Classic for centralized, enterprise services with rich data access and full server management/monitoring.
- Choose Corticon.js to run rules as fast, self‑contained JavaScript bundles in browsers, mobile apps, or serverless functions.

### Learn and support
- Documentation and PDFs: [Corticon Information Hub](https://docs.progress.com/category/corticon-information-hub).
Of course. Here is a more detailed, markdown-formatted directory of the public repositories within the `github.com/corticon` organization, with descriptions expanded based on their READMEs and other available information.

-----

### Repository Overview Repositories

  * **[Corticon.js Samples](https://github.com/corticon/corticon.js-samples)**
    This repository contains a wide range of sample decision services and examples for using Corticon.js. Corticon.js is a powerful rules engine that allows you to execute business rules as JavaScript in various environments. The samples showcase uses in serverless environments (AWS Lambda, Google Cloud Functions, Azure Functions), dynamic forms, mobile and web applications (React, Vue.js, Angular), and in-browser execution. The repository is organized into specific use cases, including extended operators, integration with different JavaScript frameworks, and service callout examples.

  * **[Corticon Classic Samples](https://github.com/corticon/corticon-classic-samples)**
    This repository provides sample rule projects designed for the classic, Java-based version of Corticon. These samples demonstrate how Corticon can be deployed as a stateless decision service on a Corticon Server or embedded directly within a Java/.NET application. They are intended to be imported into the Corticon Studio for classic (non-JavaScript) development.

   * **[Dynamic Forms](https://github.com/corticon/corticon-dynamic-forms)**
    This project is a rules-driven, framework-agnostic solution for creating and maintaining complex, dynamic forms. It uses Corticon.js to separate the form's logic from its presentation, allowing business users to define the rules that govern the form's behavior. This is ideal for applications like insurance claims or loan applications where the questions shown to the user change based on their previous answers.

  * **[Corticon on MarkLogic](https://github.com/corticon/corticon-on-marklogic)**
This repository contains a project that demonstrates the integration of Progress Corticon with MarkLogic. It allows you to use Corticon to apply business rules to data stored in a MarkLogic NoSQL database. This enables powerful, rule-based processing of documents and data within the MarkLogic ecosystem.

  * **[Corticon Server Extensions & Integration Samples](https://github.com/corticon/server-integration-and-extensions)**
This repository provides examples of how to integrate and extend the capabilities of the Corticon Server. It includes various projects that demonstrate Service Callouts (SCO), Enterprise Data Connector (EDC) usage, and other advanced integration patterns for the classic Java-based Corticon Server.

  * **[Server Analytics](https://github.com/corticon/server-analytics)**
    Introduced with Corticon v7.0, this project provides analytics capabilities to capture the details of rule executions. It enables the auditing of individual decision service executions and the analysis of decision service behavior over time, helping with performance monitoring and compliance.

-----
