# Awesome-Customer-360-Platform

# Top Customer 360 Platform Ecosystem

**Curated List of SaaS Products & Open-Source GitHub Projects**  
*Focused on Customer Data Unification, Identity Resolution & Real-Time Activation*  
**Last updated: March 2026**

This repository tracks notable **SaaS platforms** and **open-source projects** for **Customer 360 Platforms**. These tools unify customer data from disparate sources, resolve identities across devices and channels, build comprehensive customer profiles, and activate insights across marketing, sales, and service touchpoints.

**Examples** include Salesforce Customer 360, Segment Unify, Microsoft Dynamics 365 Customer Insights, Tealium, ActionIQ, Amperity, Oracle Unity CDP, Adobe Experience Platform, Redpoint Global, and Informatica MDM (the category leaders).

**Open-source emphasis**: This section is heavily expanded with every major active project for self-hosting, custom identity resolution, and open customer data platforms — ideal for organizations seeking transparent, data-sovereign Customer 360 solutions.

Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites.

## Table of Contents
- [SaaS/Hosted Platforms](#saas-hosted-platforms)
- [Open-Source GitHub Projects](#open-source-github-projects)
- [How to Contribute](#how-to-contribute)
- [Disclaimer](#disclaimer)

## SaaS/Hosted Platforms

- **[Salesforce Customer 360](https://www.salesforce.com/)**  
  Unified CRM platform connecting Sales, Service, Marketing, Commerce, and Data Cloud. Provides a single view of the customer across all Salesforce applications with Einstein AI for predictions and personalization.

- **[Segment Unify](https://segment.com/)**  
  Customer data platform that collects data from all sources, resolves identities across devices and channels, and creates unified real-time profiles. Includes Profile API, Computed Traits, SQL Traits, and Profiles Sync for warehouse interoperability .

- **[Microsoft Dynamics 365 Customer Insights](https://dynamics.microsoft.com/)**  
  Unifies customer data from multiple sources, enriches with Microsoft's unique data assets, and creates comprehensive unified profiles, AI-driven predictions, segments, and measures. Two components: Customer Insights - Data and Customer Insights - Journeys .

- **[Tealium](https://tealium.com/)**  
  Customer data platform with real-time data collection, identity resolution, and audience segmentation. Features an extensive integration ecosystem for marketing and analytics tools.

- **[ActionIQ](https://www.actioniq.com/)**  
  Composable CDP that sits on top of existing data warehouses. Enables marketers to build audiences, orchestrate journeys, and activate across channels without data duplication.

- **[Amperity](https://amperity.com/)**  
  AI-powered CDP focused on identity resolution and customer data unification. Uses patented probabilistic and deterministic matching to create accurate customer profiles.

- **[Oracle Unity CDP](https://www.oracle.com/)**  
  Customer data platform integrated with Oracle Cloud. Features identity resolution, real-time segmentation, and activation across Oracle's CX applications.

- **[Adobe Experience Platform](https://business.adobe.com/)**  
  Enterprise platform with Real-Time CDP capabilities. Unifies customer data, applies AI-driven insights, and activates experiences across Adobe Experience Cloud.

- **[Redpoint Global](https://www.redpointglobal.com/)**  
  Customer data platform with identity resolution, data quality, and real-time interaction management. Focuses on personalized customer experiences at scale.

- **[Informatica MDM](https://www.informatica.com/)**  
  Master data management platform providing a 360-degree view of customers, products, and suppliers. Features data quality, governance, and multi-domain MDM.

## Open-Source GitHub Projects

- **[LEO CDP](https://github.com/trieu/leo-cdp-framework)**  
  Open-source AI-first Customer Data Platform (license varies) for building customizable, self-hosted, privacy-friendly CDP infrastructure. Features omnichannel data collection, real-time Customer 360 profiles, AI-based segmentation (RFM, CLV, churn prediction), behavioral tracking, predictive analytics, audience activation, and Agentic AI personalization. Built with Java, Python, ArangoDB, and Apache Airflow .

- **[Zeotap Open CDP](https://zeotap.com/)**  
  First fully composable CDP running entirely on open-source compute over the customer's own lakehouse. Uses Apache Spark for identity resolution, audience computation, and activation, with Apache Iceberg tables on customer-owned object storage. No proprietary warehouse, no data copying, no per-credit compute tax. Sovereign by design for regulated enterprises .

- **[CustomerLake](https://www.databricks.com/)**  
  Agentic CDP embedded in Databricks and governed by Unity Catalog. Features Profile Agents for Customer 360 profiles with Agentic Identity Resolution (deterministic + probabilistic + agentic workflows) and Campaign Agents for audience building, next-best-action recommendations, and continuous optimization .

- **[IdentityRAG](https://github.com/tilotech/identity-rag-customer-insights-chatbot)**  
  Open-source customer insights chatbot (license varies) connecting to customer data via LLM. Creates a single comprehensive Customer 360 view (golden record) by unifying, consolidating, disambiguating, and deduplicating data across multiple sources through identity resolution .

- **[Intelligent Customer Analysis Platform](https://github.com/mario2046/Intelligent-Customer-Analysis-Platform)**  
  HTTP API server providing CRM, engagement, market intelligence, and knowledge base APIs for Customer 360 platforms. Serves as data backend for agentic applications with Dify orchestration. Built with Python and FastAPI .

- **[LEO CDP Free Edition](https://github.com/trieu/leo-cdp-free-edition)**  
  Binary build of LEO CDP Free Edition for training and evaluation purposes. Provides the same core CDP capabilities as the framework version with simplified deployment .

### Additional Strong Open-Source Options

- **[Apache Unomi](https://github.com/apache/unomi)** — Open-source customer data platform (Apache-2.0) with profile management, segmentation, and personalization.
- **[CDP by Treasure Data](https://github.com/treasure-data)** — Components of Treasure Data's CDP platform (license varies).
- **[RudderStack](https://github.com/rudderlabs/rudder-server)** — Open-source customer data pipeline (AGPL-3.0) for collecting, transforming, and routing customer data.
- **[Jitsu](https://github.com/jitsucom/jitsu)** — Open-source data collection and CDP (MIT) for event streaming and customer data integration.
- **[Metarank](https://github.com/metarank/metarank)** — Open-source personalization and ranking engine (Apache-2.0) for Customer 360 activation.
- **[Apache Airflow](https://github.com/apache/airflow)** — Workflow orchestration (Apache-2.0) for customer data pipelines.
- **[ArangoDB](https://github.com/arangodb/arangodb)** — Multi-model database (Apache-2.0) with document, graph, and search capabilities for customer profiles.
- Community **n8n** workflows for Customer 360 data orchestration and activation.

**Frameworks for building custom systems**: Combine **LEO CDP** or **Zeotap Open CDP** as the Customer 360 backend with **RudderStack** for data collection, **Apache Airflow** for pipeline orchestration, **ArangoDB** for multi-model customer profiles, and **Metarank** for personalization — creating a fully self-hosted, enterprise-grade Customer 360 platform.

## How to Contribute

1. Fork the repo.
2. Add/edit entries in `README.md` (follow existing format).
3. Include: name, link, 1–2 sentence description, and whether it's SaaS or open-source.
4. Submit PR with a short explanation.

Star the repo if you find it useful!

## Disclaimer

- This is a **community-curated** list — not exhaustive and not an endorsement.
- Customer 360 platforms handling personal data must comply with data protection regulations (GDPR, CCPA, HIPAA, etc.).
- Self-hosted open-source solutions require proper security hardening, identity resolution validation, and ongoing maintenance for production reliability.

---

**Made for data teams, CDP engineers, marketing technologists, and developers building transparent Customer 360 solutions.**  
Let's make Customer 360 platforms more open, data-driven, and sovereign.
