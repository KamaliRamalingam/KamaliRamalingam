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

## Data Analysis and Engineering Projects

**Destination Prioritisation Dashboard** — travel industry case (Oct 2026)
I owned the end-to-end build of a Power BI decision-support dashboard and Python data workflow, based on stakeholder requirements, classifying destinations into four prioritised actions. I validated the figures end to end — 6 of 6 reconciliation checks and 8 of 8 dashboard tests passed, tracing results from the dashboard back to the raw source rows. Built with Python and Power BI (DAX). Pass with Distinction.

**Sell-Out Analysis for Seasonal Restocking** — Happy Socks (Sep 2026)
In a five-person team, I built an Early Demand Score for a Swedish retail client, combining early sales with retailer breadth. Back-tested against two prior seasons, it outperformed a volume-only baseline in predicting bestsellers. We presented restock recommendations to the client, who confirmed their value for upcoming-season planning. Built with Excel, Google Sheets and Python.

**[IPL Analytics Pipeline](https://github.com/KamaliRamalingam/ipl_pipeline)** — automated ELT pipeline and dashboard (Jun 2026)
I engineered two Airflow ELT pipelines loading 1,243 IPL matches and 4,800+ Reddit posts (refreshed every 15 minutes) into a Snowflake medallion warehouse, transformed with 14 SQL-based dbt models and 100 tests, all passing. The project includes a live Tableau dashboard connected to Snowflake, and the pipelines sustained a 100% success rate across 90+ runs using automatic retries. Built with Python, SQL, Apache Airflow, Snowflake, dbt, Azure Blob Storage and Tableau. Pass with Distinction.

**Financial Data Visualisation Redesign** — Charly (May 2026)
I owned the redesign of a Swedish fintech's parental-leave calculator in a four-person team, replacing line charts with a financial imbalance gauge and comparisons against partner, workplace and national averages, which made the result considerably easier to understand. Built with Power BI, HTML, CSS and JavaScript.

**Hidden Longevity Champions** — Billboard Hot 100 analysis (Jan 2026)
I cleaned and joined five relational datasets covering 10,783 tracks from 2000 to 2024. Only 3% of songs reached number one, while 28% charted for 20+ weeks without ever reaching the top spot. I quantified a 37% decline in chart longevity from the pre-streaming to the streaming era and presented it as an interactive data story with a custom "sleeper score". Built with Python, Pandas and Plotly. Pass with Distinction.

**Customer Segmentation** — RFM analysis (Nov 2025)
I segmented around 150,000 customers using an RFM (recency, frequency, monetary) model in SQL on Snowflake. The top-tier segment — 33% of customers — generated 67% of total revenue. I identified the five highest-value customers and proposed a tiered retention strategy tailored to each segment.

## Hackathons

Hackathons have been a good way to work on problems outside the programme:

- **Couchbase Edge Resilience Hackathon** (2026) — Built, with a team, an [edge-resilient baggage operations system](https://github.com/KamaliRamalingam/edge-resilient-baggage-system) that keeps airport baggage operations running locally during a cloud outage and synchronises with the cloud once connectivity returns. There is a demo video in the repository.
- **Kong AI Governance** (April 2026) — Top 5 finalist. We built an AI gateway for Volvo with PII and DLP scanning, rate limiting and GDPR audit logging.
- **Snowflake AI Hackathon** (April 2026) — Built a loan-agreement ML classifier in Snowflake using Cortex AI.
- **Cline AI-Assisted Coding** (May 2026) — Lead developer on an Electrolux proof of concept that turns technical updates into plain-language communication.
- **Build for Impact: Labor Rights** (May 2026) — Built a dashboard comparing labour precarity across five dimensions.

## Background

- **Data Analyst Programme, Hyper Island** (2025–2027) — Pass with Distinction in Python Programming, Data Engineering, Data Governance and Ethics, Leadership and Team Excellence, and Business Intelligence. The programme includes the six-month LIA placement I am applying for now.
- **Programmer Analyst, Cognizant** (2012–2015) — Developed features for a large legal platform in an Agile organisation of around 100 people, maintaining over 95% unit test coverage. Won the company's Bright Sparks innovation contest.
- **M.Sc. in Computer Science, College of Engineering Guindy, Anna University** (2007–2012)

Languages: Tamil (native), English (professional working proficiency), Swedish (basic — SFI C completed).
