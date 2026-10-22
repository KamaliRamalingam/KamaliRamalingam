# Kamali Ramalingam

Data Analyst based in Stockholm, working across business intelligence and data engineering.

I am currently studying on the Data Analyst programme at Hyper Island. Before moving into data, I spent three years as a C#/.NET developer at Cognizant, working on an enterprise legal platform. That background still shapes how I approach analysis work: I care about whether the numbers reconcile, whether the pipeline can be re-run, and whether someone else can pick up what I built.

Over the past year I have worked on client projects in Sweden in retail, fintech and travel, alongside building data pipelines of my own. I am now looking for a six-month LIA internship from December 2026 to June 2027, ideally one that can grow into a full-time analyst role.

## What I work on

Most of my work falls into three areas:

- **Analysis and reporting** — SQL and Python analysis, KPI definition, demand analysis, customer segmentation and A/B testing. I build dashboards in Power BI and Tableau, usually starting from the decision the dashboard needs to support rather than from the chart.
- **Data engineering** — ELT pipelines on Snowflake using dbt and Apache Airflow, with data quality checks built in. Dimensional modelling (star schema), medallion architecture and Azure Blob Storage for ingestion.
- **AI projects** — Retrieval-augmented generation (RAG) applications with LangChain and LangGraph, and MCP tooling. This has mostly come through hackathons so far.

Tools I use regularly: SQL, Python (Pandas, Plotly, Jupyter), Power BI (DAX), Tableau, Snowflake, dbt Cloud, Apache Airflow, Excel, Git, Docker and REST APIs. Earlier in my career I worked mainly in C#, .NET Core and ASP.NET MVC.

## Selected work

**[IPL Analytics Pipeline](https://github.com/KamaliRamalingam/ipl_pipeline)**
An automated ELT pipeline covering 1,241 IPL matches from 2008 to 2026. Match data is ingested with Python into Azure Blob Storage, loaded into a Snowflake medallion warehouse, transformed with dbt models and presented in a Tableau dashboard. This is the project that best shows how I structure a pipeline end to end.

**Destination Prioritisation Dashboard** — travel industry client project
A Power BI dashboard that classifies destinations into four prioritised actions for a travel company. I owned the build from stakeholder requirements to delivery and validated every figure in the dashboard back to the raw source data.

**Sell-Out Analysis for Seasonal Restocking** — Happy Socks
A demand scoring model for seasonal restocking, combining early sell-out signals with retailer breadth and back-tested against two previous seasons. Our restocking recommendations were used by the client in planning for the following season.

**Financial Data Visualisation Redesign** — Charly
A redesign of a Swedish fintech's parental-leave calculator. We replaced the original line charts with a comparison view that shows a household's financial imbalance against a partner, workplace and national averages, which made the result considerably easier to understand.

**Customer Segmentation (RFM)**
Segmented around 150,000 customers in SQL on Snowflake using recency, frequency and monetary value, and set out a retention approach for each segment.

## Hackathons

Hackathons have been a good way to work on problems outside the programme:

- **Couchbase Edge Resilience Hackathon** (2026) — Built, with a team, an [edge-resilient baggage operations system](https://github.com/KamaliRamalingam/edge-resilient-baggage-system) that keeps airport baggage operations running locally during a cloud outage and synchronises with the cloud once connectivity returns. There is a demo video in the repository.
- **Kong AI Governance** (April 2026) — Top 5 finalist. We built an AI gateway for Volvo with PII and DLP scanning, rate limiting and GDPR audit logging.
- **Snowflake AI Hackathon** (April 2026) — Built an agreement classification model in Snowflake using Cortex AI.
- **Cline AI-Assisted Coding** (May 2026) — Lead developer on an Electrolux proof of concept that turns technical updates into plain-language communication.
- **Build for Impact: Labor Rights** (May 2026) — Built a dashboard comparing labour precarity across five dimensions.

## Background

- **Data Analyst Programme, Hyper Island** (2025–2027) — Pass with Distinction in Python Programming, Data Engineering, Data Governance and Ethics, Leadership and Team Excellence, and Business Intelligence. The programme includes the six-month LIA placement I am applying for now.
- **Programmer Analyst, Cognizant** (2012–2015) — Developed features for a large legal platform in an Agile organisation of around 100 people, maintaining over 95% unit test coverage. Won the company's Bright Sparks innovation contest.
- **M.Sc. in Computer Science, College of Engineering Guindy, Anna University** (2007–2012)

Languages: Tamil (native), English (professional working proficiency), Swedish (basic — SFI C completed).

## Contact

The best way to reach me is on [LinkedIn](https://www.linkedin.com/in/kamaliramalingam), or by email at vrpkamali@gmail.com.

If you are hiring for an LIA, internship or part-time data role in Stockholm starting December 2026, I would be glad to hear from you.
