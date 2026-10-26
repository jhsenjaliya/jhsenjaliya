# Hi, I'm Jay Sen 👋

**Data Platform Architect & Builder**

I design and build data platforms that connect operational systems, real-time events, and analytical data products. My work spans enterprise engineering at PayPal, open-source collaboration, and applied research into how data is modeled, governed, and made reliable across systems.

Engineer and entrepreneur at heart, with 15+ years of experience turning complex infrastructure into platforms that teams can understand, adopt, and build on.

[LinkedIn](https://www.linkedin.com/in/jaysen2/) · [ODSC speaker profile](https://staging6.odsc.com/blog/speaker/jay-sen/) · [Apache profile](https://home.apache.org/phonebook.html?uid=jaysen) · [Data Oculus](https://dataoculus.app)

---

## 🏗️ My perspective on data platforms

A useful data platform connects architecture to business outcomes: faster delivery, trustworthy data, clear ownership, and sustainable operating cost. I work across the boundaries between ingestion, processing, storage, metadata, and consumption to make those outcomes possible.

| Area of depth | Problems I work on |
| --- | --- |
| **Real-time systems & streaming** | Event collection, change data capture, domain business events, enrichment, and streaming analytics using Kafka, Debezium, and Spark. |
| **Data integration & orchestration** | Metadata-driven pipelines, batch and streaming data movement, workflow orchestration, and secure integration across systems using Airflow and Gobblin. |
| **Data mesh & data products** | Domain ownership, self-service infrastructure, data contracts, and consumer-oriented data products built on existing platforms. |
| **Governance & metadata** | Data discovery, cataloging, sensitive-data classification, schema management, and making governance part of platform design. |
| **Data reliability** | Profiling, schema drift, quality rules, and detecting problems close to the source across streaming and batch data. |

## 🔬 Applied research & architectural ideas

### Super Schema — consistent meaning across systems

The same business entity often has different definitions in databases, Kafka events, and APIs. My **Super Schema** proposal explores a shared logical entity definition that generates platform-specific representations, reducing duplicated schema work and inconsistency. This connects data modeling, developer productivity, and governance.

I'm using [Microsoft TypeSpec](https://github.com/microsoft/typespec) in Super Schema and collaborating with its open-source community on database-schema generation. My proposal explores extending TypeSpec's emitter model to generate schemas for PostgreSQL, Spanner, BigQuery, Iceberg, Parquet, and other targets from a shared definition. The design discussions address type mappings, nullability, constraints, and database-specific semantics—turning cross-platform consistency into concrete engineering work.

[ODSC session & abstract](https://odsc.ai/speakers-portfolio/super-schema/) · [TypeSpec proposal](https://github.com/microsoft/typespec/issues/10334) · [Design discussion](https://github.com/microsoft/typespec/issues/10334#issuecomment-4244266463)

### Practical data mesh — from principles to implementation

My talks and workshops explore how enterprises can introduce domain-owned data products using existing open-source infrastructure. The focus is implementation: how ownership, interfaces, self-service, and governance come together, and how to evolve existing pipelines into reusable data products.

[Practical Data Mesh for Enterprises](https://staging6.odsc.com/blog/speaker/jay-sen/) · [Applied Data Mesh workshop & code](https://github.com/jhsenjaliya/data-product-demo)

### Real-time data products — from changes to business context

The workshop implementation connects PostgreSQL CDC, Kafka Streams, and Spark to build enriched business events and Iceberg data products. It explores the transition from source-oriented records to domain-level events, with both historical snapshots and latest-state views for consumers.

[Explore the implementation](https://github.com/jhsenjaliya/data-product-demo)

## 💼 Enterprise engineering at PayPal

My experience spans data movement, event collection, streaming pipelines, scanning, cataloging, and governed data foundations. I combine architecture, hands-on engineering, and technical leadership, with an emphasis on reliability, adoption, and cost.

My published work describes the evolution of PayPal's data movement platform in an ecosystem spanning hundreds of petabytes, including orchestration, integration, metadata, and secure movement across security zones:

- [**Next-Gen Data Movement Platform at PayPal**](https://medium.com/paypal-tech/next-gen-data-movement-platform-at-paypal-100f70a7a6b) — bringing Airflow, Gobblin, metadata, and platform APIs together.
- [**How PayPal Moves Secure and Encrypted Data Across Security Zones**](https://medium.com/paypal-tech/how-paypal-moves-secure-and-encrypted-data-across-security-zones-10010c1788ce) — security and operational considerations in enterprise data integration.

## 🎤 Sharing the work

I share architectural ideas, implementation lessons, and hands-on examples with the data engineering community.

| Forum | Topic & resources |
| --- | --- |
| **ODSC AI** | [**Super Schema**](https://odsc.ai/speakers-portfolio/super-schema/) — a shared logical definition for business entities across platforms. |
| **ODSC East 2025** | **Applied Data Mesh Workshop for Scalable Data Platforms** — [code & materials](https://github.com/jhsenjaliya/data-product-demo). Selected by the organizers among [ten standout presentations](https://opendatascience.com/top-insights-from-odsc-east-2025-10-slide-decks-every-data-scientist-should-see/). |
| **ODSC West 2024** | **Practical Data Mesh for Enterprises** — implementation approaches and a PayPal case study. [Session listing](https://staging6.odsc.com/blog/speaker/jay-sen/). |
| **Airflow Summit 2021** | **Airflow as the Foundation of a Multi-Faceted Data Platform**, with Ry Walker. [Session & recording](https://airflowsummit.org/sessions/2021/airflow-as-the-foundation-multi-faceted-data-platform/). |

[ODSC speaker profile & session archive](https://staging6.odsc.com/blog/speaker/jay-sen/)

## Open source & community

Open source is part of how I build and learn. I'm a committer on [Apache Gobblin](https://github.com/apache/gobblin) and [Apache Eagle](https://github.com/apache/eagle), and have contributed to [Apache Airflow](https://github.com/apache/airflow). My interests include data integration, workflow orchestration, and data-platform reliability.

## 🚀 Putting the ideas into products

### [Data Oculus — dataoculus.app](https://dataoculus.app)

Building self-service, real-time data reliability across streaming and batch systems. The work brings together data profiling, schema-drift detection, executable data contracts, and AI-assisted quality rules to identify problems closer to the source.

[Explore Data Oculus](https://dataoculus.app) · [Documentation](https://dataoculus.app/docs/intro/)

## 🤝 Connect

I enjoy exchanging ideas on data platform architecture, streaming systems, data mesh, metadata, governance, and reliable data products.

[LinkedIn](https://www.linkedin.com/in/jaysen2/) · [jaysen@apache.org](mailto:jaysen@apache.org) · [Data Oculus](https://dataoculus.app)
