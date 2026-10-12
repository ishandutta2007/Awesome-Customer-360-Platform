# Awesome-Customer-360-Platform

## Top Customer 360 Platform Ecosystem



**Curated List of SaaS Products & Open-Source GitHub Projects**  

*Focused on Customer Data Unification, Identity Resolution & Real-Time Activation*  

**Last updated: March 2026**



This repository tracks notable **SaaS platforms** and **open-source projects** for **Customer 360 Platforms**. These tools unify customer data from disparate sources, resolve identities across devices and channels, build comprehensive customer profiles, and activate insights across marketing, sales, and service touchpoints.



**Examples** include Salesforce Customer 360, Segment Unify, Microsoft Dynamics 365 Customer Insights, Tealium, ActionIQ, Amperity, Oracle Unity CDP, Adobe Experience Platform, Redpoint Global, and Informatica MDM (the category leaders).



**Open-source emphasis**: This section is heavily expanded with every major active project for self-hosting, custom identity resolution, and open customer data platforms — ideal for organizations seeking transparent, data-sovereign Customer 360 solutions.



Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites.



## Table of Contents

- [Sector Overview & Market Dynamics](#sector-overview--market-dynamics)
- [SaaS/Hosted Platforms](#saas-hosted-platforms)
- [Open-Source GitHub Projects](#open-source-github-projects)
- [How to Contribute](#how-to-contribute)
- [Disclaimer](#disclaimer)

## Sector Overview & Market Dynamics

The global Customer 360 and Customer Data Platform (CDP) market is valued between **$4.5 billion and $7.5 billion**, rapidly expanding at a CAGR of ~18–25% fueled by first-party data demands, privacy regulations, and enterprise AI personalization needs. The sector exhibits a **moderately concentrated structure at the enterprise scale**—where established tech titans (Microsoft, Oracle, Salesforce, Adobe) capture a predominant share of enterprise budgets—coexisting with a **highly fragmented long-tail** of specialized pure-play and composable/warehouse-native CDP providers competing across mid-market and niche verticals.

## SaaS/Hosted Platforms

| Platform | Company Size (Revenue / Valuation) | Starting Tier Pricing | Free Tier / Trial Limits | Description |
|---|---|---|---|---|
| **[Microsoft Dynamics 365 Customer Insights](https://dynamics.microsoft.com/)** | ~$245B+ ARR (Microsoft) / ~$3.1T Market Cap | $1,700/tenant/month (billed annually) | 30-day free trial (up to 100,000 unified profiles and sample customer data; no credit card required) | Unifies customer data from multiple sources with AI-driven predictions, segments, and measures across Customer Insights - Data and Journeys. |
| **[Oracle Unity CDP](https://www.oracle.com/)** | ~$53B+ ARR (Oracle) / ~$480B Market Cap | Custom enterprise quote (starts at ~$10,000/month or ~$120,000/year contract floor) | 30-day free trial via Oracle Cloud ($300 cloud credits; Unity CDP itself requires sales-led guided PoC / demo) | Enterprise CDP integrated into Oracle Fusion CX featuring identity resolution, real-time segmentation, and cross-channel activation. |
| **[Salesforce Customer 360](https://www.salesforce.com/)** | ~$38B+ ARR (Salesforce) / ~$280B Market Cap | Starts at $25/user/month (Starter Suite CRM); Data Cloud packages start at ~$60,000/year (or $500 per 100K credit block) | 30-day free trial for core CRM editions; free zero-cost provisioning for existing Enterprise Edition customers (includes 1 TB storage baseline and foundational data service credits) | Unified CRM platform connecting Sales, Service, Marketing, Commerce, and Data Cloud with Einstein AI for predictions and personalization. |
| **[Adobe Experience Platform](https://business.adobe.com/)** | ~$21B+ ARR (Adobe) / ~$200B Market Cap | Custom enterprise quote (starts at ~$100,000–$250,000/year based on managed profiles and API/event volume) | No self-service free trial; guided sandbox environment available exclusively during negotiated enterprise PoC | Enterprise Real-Time CDP and customer experience architecture unifying profiles and activating journeys across Adobe Experience Cloud. |
| **[Segment Unify](https://segment.com/)** | ~$4.3B ARR (Twilio) / ~$14B Market Cap | Free Connections plan; Segment Unify (Profiles & Identity Resolution) requires custom Business tier (starting ~$25,000–$40,000/year) | Free forever plan: 1,000 MTUs (Monthly Tracked Users), 2 sources, 1 warehouse destination, 300+ integrations (Unify identity resolution excluded) | Data platform collecting cross-channel events with identity resolution, Computed Traits, SQL Traits, and Profiles Sync. |
| **[Informatica MDM](https://www.informatica.com/)** | ~$1.7B ARR (Informatica) / ~$8B Market Cap | Custom IPU consumption quote (starts at ~1,000 IPUs/year, typically ~$150,000–$200,000/year entry floor) | 30-day free trial available for Cloud Data Integration (CDI) and Cloud Data Loader modules (MDM requires assisted PoC) | Master data management and IDMC platform delivering 360-degree views of customers, entities, and multi-domain hierarchies. |
| **[Tealium](https://tealium.com/)** | ~$150M–$195M ARR / $1.2B Valuation (Series G) | Data Cloud Activation starts at $1,000/month (billed annually); full CDP deployments start at ~$35,000–$50,000/year | No self-service free trial; limited access demo and test sandbox available upon request via sales consultation | CDP offering real-time data collection, tag management, identity resolution, and audience segmentation with 1,300+ turnkey connectors. |
| **[Amperity](https://amperity.com/)** | ~$65M–$70M ARR / $1.0B Valuation (Series D) | Custom Amp-consumption quote (starts at ~$150,000–$200,000/year based on records processed and tenant activity) | No public free trial; partner-assisted PoCs and interactive sandbox demos available via Databricks and cloud marketplaces | AI-powered CDP specializing in patented deterministic and probabilistic identity resolution (Stitch) and automated golden profile generation. |
| **[ActionIQ](https://www.actioniq.com/)** | ~$30M ARR / Acquired by Uniphore ($145M+ VC funding) | Custom enterprise quote (starts at ~$100,000/year based on warehouse scale and compute modules) | No public free trial; proof-of-concept testing available via partner cloud environments (Databricks / Snowflake marketplaces) | Composable CDP overlaying enterprise data warehouses to build audiences and orchestrate customer journeys without data duplication. |
| **[Redpoint Global](https://www.redpointglobal.com/)** | ~$25M–$30M ARR / Private (~$39M Total Funding) | Custom enterprise quote (starts at ~$60,000–$100,000/year depending on record volume and deployment model) | No public free trial; tailored product demonstration and scoping PoC available via sales consultation | Customer data platform featuring automated data hygiene, identity resolution, and real-time interaction management across hybrid/cloud setups. |



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
