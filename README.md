## Vinícius Borges, Data Engineer. See how to engineer's tomorrow's data today.

<p align="left">
  <a href="https://www.linkedin.com/in/viniciusfborges/"><img src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white"/></a>
  <a href="mailto:vinicius.ferreiraborges@outlook.com"><img src="https://img.shields.io/badge/Outlook-0078D4?style=for-the-badge&logo=microsoft-outlook&logoColor=white"/></a>
  <a href="https://www.notion.so/28bd696d49218053bb30eb58ffecc17f?source=copy_link"><img src="https://img.shields.io/badge/Website-000000?style=for-the-badge&logo=About.me&logoColor=white"/></a>
  <a href="https://x.com/BorgesTalks"><img src="https://img.shields.io/badge/X-000000?style=for-the-badge&logo=x&logoColor=white"/></a>
  <a href="https://medium.com/@viniciusborgess"><img src="https://img.shields.io/badge/Medium-12100E?style=for-the-badge&logo=medium&logoColor=white"/></a>
  <a href="https://www.kaggle.com/viniborgess"><img src="https://img.shields.io/badge/Kaggle-20BEFF?style=for-the-badge&logo=kaggle&logoColor=white"/></a>
  <a href="https://MASTODON_SERVER/viniciusborges"><img src="https://img.shields.io/badge/Mastodon-6364FF?style=for-the-badge&logo=mastodon&logoColor=white"/></a>
  <a href="https://orcid.org/0009-0003-6962-9392"><img src="https://img.shields.io/badge/Orcid-A6CE39?style=for-the-badge&logo=orcid&logoColor=white"/></a>
    <img src="https://img.shields.io/badge/Availability-Remote_(GMT--7_to_GMT+3)-228B22?style=for-the-badge"/>
</p>

Engineering data as a first-class product, not a byproduct. This portfolio features production-ready data solutions — from ingestion to ML model APIs. Built for high performance, this collection includes high-leverage projects on a modern, multi-cloud stack to deliver trustworthy data.


## Roadmap:

This roadmap outlines my strategic focus. 

Each initiative is a foundational block, designed to solve a core industry challenge and enable the next level of analytical and predictive capabilities.

| Status | Timeline | Initiative | Core Engineering Objective |
| :--- | :--- | :--- | :--- |
| 🚧 | **H2 2025** | **The Serverless Analytics Backbone** | To engineer a production-grade, event-driven data ingestion and warehousing foundation on AWS, delivering clean, reliable, and queryable datasets for BI and strategic analysis with near real-time latency. |
| 💡 | **H1 2026** | **The High-Frequency Market Data Warehouse** | To design and build a specialized, time-series optimized data warehouse capable of capturing and modeling the full complexity of an in-game economy, enabling deep forensic analysis and macroeconomic insights. |
| 💡 | **H2 2026** | **The Competitive Telemetry Platform** | To architect a data model and platform that can store and analyze complex player interactions within competitive matches, creating the foundation for next-generation matchmaking and performance analysis. |

---

## Featured: Serverless Game Analytics Platform

This is the current focus of the roadmap, building the foundational layer for all future data products.

- **The Strategic Imperative:** Game studios need a single source of truth for player behavior that is scalable, cost-effective, and fast enough to inform operational decisions.
- **The Platform:** A production-grade, serverless batch pipeline on AWS, defined entirely with Infrastructure as Code (AWS CDK). This platform ingests millions of events, processes them into a clean data warehouse, and makes them available for exploration.
- **Immediate Outcomes:** Powers strategic dashboards for tracking KPIs (DAU, MAU, retention) and enables ad-hoc querying for deep-dive analysis by product teams.
- **Future Capabilities Enabled:** This platform is the necessary foundation for future ML applications, such as churn prediction, player segmentation, and LTV modeling.
- **[➡️ View the Project Repository](https://github.com/vinifborgess/gaming-serverless-analytics-pipeline)**

---

### 🌩 Cloud-Native by Default

| Technology | Strategic Rationale |
| :--- | :--- |
| **AWS Lambda** | Serverless compute for event-driven workloads, eliminating the overhead of server management. |
| **AWS Glue** | Native, serverless ETL for both batch & streaming, seamlessly integrated with the S3 Data Lake. |
| **Amazon Kinesis** | For scalable, real-time data ingestion at any scale, with automatic provisioning. |
| **Amazon S3** | The cost-effective, durable foundation for the Data Lake, with versioning and full AWS ecosystem integration. |
| **Amazon Athena** | For rapid, on-demand querying directly on the S3 Data Lake, bypassing the need for dedicated clusters during exploration. |
| **Amazon Redshift** | A high-performance analytical warehouse, purpose-built for complex BI queries and reporting at scale. |
| **Terraform / AWS CDK** | Enabling version-controlled, auditable, and repeatable infrastructure as code (IaC). |
| **Docker** | For containerizing applications, ensuring portability and consistency across development and production environments. |
| **GCP BigQuery / Cloud Run**| A multi-cloud approach for leveraging best-in-class massive-scale analytics and fast, container-based microservices. |

### 📦 Data as a Product (DaaP)

| Technology | Strategic Rationale |
| :--- | :--- |
| **dbt** | For bringing software engineering best practices to data transformation: version control, testing, and documentation. |
| **SQL** | The universal language for data modeling and analysis; the lingua franca of the data world. |
| **Python (Pandas, Polars)** | The workhorse for batch processing, rapid prototyping, and complex data manipulation. |
| **Apache Spark** | The standard for distributed, large-scale data processing when a single node is not enough. |
| **Great Expectations** | For building a culture of data quality and ensuring that data is trustworthy by design. |
| **Data Catalogs (AWS Glue, etc.)** | For enabling data discovery and governance, empowering true self-service analytics. |

### 🚀 Performance Engineering

| Technology | Strategic Rationale |
| :--- | :--- |
| **Spark / Flink / Kafka** | For architecting high-throughput distributed systems capable of handling massive batch or streaming workloads. |
| **KDB+/q** | The specialized tool for ultra-low-latency queries in time-series scenarios where microseconds matter. |
| **System Design & Tuning** | The practice of fine-tuning architecture, caching, and indexing for mission-critical workloads. |

---

## Let's build the future together.
