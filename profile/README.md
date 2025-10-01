# Progress Corticon Decision Management

[Progress Corticon](https://www.progress.com/corticon) empowers domain experts to author, test, and deploy complex business rules without writing code. This repository provides a collection of rule projects tailored for both Corticon Classic and Corticon.js, showcasing diverse application scenarios.

[![Try the Searcher](https://img.shields.io/badge/Corticon_Knowledge_Bot-Chat_now-success?style=for-the-badge&logo=progress)](https://corticon.github.io/searcher/)

## Corticon vs. Corticon.js: Choose Your Deployment

Corticon offers two distinct deployment models to suit your needs:

**1. Corticon classic**

* **Deployment:** Deployed as stateless decision services on a Corticon Server, exposed as web services or embedded within Java applications.
* **Key Feature:** Robust data integration capabilities, allowing seamless interaction with external databases and systems.
* **Use Cases:** Primarily focused on transactional processing, ideal for complex, data-driven decision automation within enterprise environments.
* **Repository:** [Corticon Classic Transactional Rules](https://github.com/corticon/corticon-classic-samples) - Contains rule projects optimized for transactional workflows.

**2. Corticon.js: Offline & FaaS Flexibility**

* **Deployment:** Transpiled into self-contained JavaScript bundles, enabling deployment in any JavaScript environment, including offline and serverless (FaaS) scenarios.
* **Key Features:** Lightweight footprint, offline execution, and flexible deployment options.
* **Use Cases:**
    * **Transactional Processing:** Suitable for streamlined, call and response transactional decisions.
    * **Dynamic Forms:** Enables interactive, rule-driven form validation and behavior within web applications.
* **Repositories:**
    * [Corticon.js Transactional Rules](https://github.com/corticon/corticon.js-samples) - Contains rule projects for transactional logic.
    * [Corticon.js Dynamic Forms Rules](https://github.com/corticon/dynamic-forms) - Contains rule projects designed for dynamic form interactions.

## Rule Application Scenarios

Corticon rules can be utilized in various application scenarios:

* **Batch Processing:** Automate large-scale data transformations and decision-making processes.
* **Transactional Processing:** Execute real-time decisions within transactional workflows, ensuring consistency and accuracy.
* **Dynamic Forms:** Create intelligent, interactive forms that adapt to user input based on defined rules.

## Getting Started

1.  **Rule Definition:** Design, analyze, document, sequence, and test your rules in **[Corticon Studio](https://docs.progress.com/bundle/corticon-quick-reference/page/A-guide-to-Progress-Corticon-Studio.html)** or **[Corticon.js Studio](https://docs.progress.com/bundle/corticon-js-quick-reference/page/A-guide-to-Progress-Corticon.js-Studio.html)**.
2.  **Import Rule Projects:** Explore the repositories linked above and import the desired rule projects into your respective Corticon Studio environment.
3.  **Deployment:** Deploy your rules using the appropriate Corticon runtime based on your chosen deployment model (Corticon Server or Corticon.js).
4.  **Integration:** Integrate the deployed rules into your applications via web services, embedded Java code, or JavaScript bundles.
