# Timothy Burns

“Customer-focused data architect with deep technical expertise, persuasive communication skills, and a proven record of building high-performing teams to drive scalable business impact.”

timburnsowlmtn@gmail.com  
(401) 954-1620  
Greater Boston Area  
[linkedin.com/in/tim-burns-5aa6141](https://linkedin.com/in/tim-burns-5aa6141)

---

## Professional Experience


### Azrius Analytics  
** AI Advisor (Part Time) **  
March 2025 – Present | Remote  

- Created training materials and presentations for leveraging AI in traditional cloud data platforms
- Reviewed existing supply chain analytics and data pipelines for integration with LLMs
- Met with early adopters to gather feedback and iterate on the product.



---


### Evolve Vacation Rentals  
**Principal Data Architect**  
May 2023 – March 2025 | Remote

- Migrated Salesforce Application to Javascript/Python  (Leaflet, OpenAPI, Snowflake) stack.
  - Utilized Leaflet for applying price factor multipliers on a map to call the API and track changes.
  - Implemented an OpenAPI stack Gunicorn with sub-second latency, returning fast queries immediately
  - Rebuilt the price and forecast model asynchronously with RabbitMQ services on dbt and Pytorch.
- Built a high-performance microservice with Gunicorn to adjust pricing via real-time geocode queries, enabling faster decision-making. 
  - Revenue managers could manually specify prices and distribute to Airbnb and other rental services via API in real time. 
- Streamed high-volume data into Postgres via AWS SQS for real-time pricing updates with public access and millisecond response times. 

- Replaced Heroku-based architecture with a dbt/Terraform/ArgoCD pipeline.
  - Resulted in a system where we could deploy infrastructure changes and code deployments in minutes rather than hours.
- Implemented a partitioned daily import external table containing all Airbnb and VRBO listings, utilizing Snowflake's capabilities for efficient data management. 
  - Handled hundreds of GBs historical pricing and availability data, improving data accessibility and analysis.
  - Implemented guardrail policies to insulate against pricing shocks while maximizing revenue.

**Key Achievements:**  
- Increased revenue per booked night through targeted pricing and forecasting. 
- Seamlessly migrated a Salesforce UI to a Open Source Javascript/Python stack, enabling fast releases to product needs.
- Improved release velocity code quality via automated testing, merge checklists and test validation. 

**Tech Stack:** Python, Typescript, Node.js, SQL, Snowflake, Salesforce, AWS (EKS, SQS), dbt, Spark, Jupyter, PyTorch, Metabase, Tableau

---

### Abacus Insights  
**Senior Software Engineer**  
October 2021 – April 2023 | Boston, MA

- Built Delta Lake marts in Databricks with Snowflake for sharing, saving over $2K/month.
  - Applied Snowpipe to link DeltaTables from Databricks for cost and performance savings.
  - Implemented an architecture for data sharing on the Snowflake market place for normalized CMS data.
- Migrated healthcare data systems from Oracle to Snowflake with near-real-time claims.
  - Leveraged zero-copy clones to minimize data movement and costs.
  - Build foundational data marts for easy aggregation and reporting.
- Created clinical dashboards to surface alerts for diabetes and obesity management.
  - Aggregate LOINC and ICD codes against terminology codes to provide a normalized view of patient data.
- Rewrote complex EMN Spark to simple Snowflake transforms for member segment dimensions.
  - Eliminated need for costly EMN usage and allowed us to leverage Snowflake's compute capabilities.

**Tech Stack:** Python, Java, SQL, Snowflake, Databricks, Oracle, AWS (EMR, Glue, Lambda, SQS, Terraform), dbt, Delta Lake

---

### Kraft Analytics Group  
**Data Architect**  
July 2019 – October 2021 | Foxboro, MA

- Built a real-time transaction summary pipeline with API Gateway, Lambda, Redis. 
  - Project successfully handled 1000s of transactions per second with sub-second latency.
  - Allowed us to seamlessly handle large usage surges for Sunday football games.
- Spearheaded the design and deployment of a robust, scalable Snowflake data mart using a Data Vault architecture. 
  - Correlated multiple vending receipt sales and ticket sales data to provide target high-value customers.
  - Integrated Acxiom intelligence with rich customer data, building out a 360-degree customer view and "sales cheat sheets" for cold calls.
- Implemented data governance on a SnapLogic pipeline and extended to the BitBucket pipeline deployment for automated testing and validation of ETL pipelines. 
  - Turned an all day manual process into an automated point and click deployment.

**Tech Stack:** Python, Java, SQL, Snowflake, AWS (API Gateway, Lambda, Redis), SnapLogic, Tableau

---

### Virgin Pulse  
**Architect Lead**  
March 2018 – July 2019 | Providence, RI

- Replaced Birst with a custom analytics pipeline using Airflow, Python, Redshift.
- Engineered a templated SQL application to integrate advanced SQL analytics easily across multiple customer data segments and reward rules.
  - Resolved complex segment changes across slowly changing dimensions for insurance enrollment.
- Led the migration of a legacy SQL Server data warehouse to a Redshift data mart, improving performance and reducing costs.
  - Eliminated a three month reporting backlog using automation and self-service on Tableau
  - Implemented continuous replication of SQL Server data to Redshift using AWS DMS.
  - Successfully turned off the SQL server instance, avoiding scaling issues eliminating costs.

**Tech Stack:** Python, SQL, Redshift, SQL Server, AWS (Redshift), Tableau, DOMO, Birst

---

### Retail Solutions Inc.  
**Full Stack Software Engineer Lead / Manager**  
July 2002 – April 2018 | Cranston, RI

- Engineered a robust timezone-aware data tracking solution leveraging Oracle and Java. 
  - Utilized detailed change tracking for push replication data sets to analytics engines.
- Built a web-based reporting system with Java, Spring, and Oracle. 
  - Developed a custom reporting engine to allow users to create and save report parameter templates
  - Integrated processed templates with SQL generation to create regular deliverable reports and alerts
- Leveraged and extended PL/SQL within a Talend infrastructure to create a unified reporting layer for supply chain metrics across 40 retailers. 
  - Implemented automated data cleansing using PL/SQL, Talend, with custom user data defined in a web-based UI. 
  - Allowed a very small team of analysts to support a large number of retailers with vastly different data profiles. 

- **Tech Stack:** Java, C#, SQL, Oracle, SQL Server, SharePoint, Tableau, MS Analytical Services

---

## Volunteer Positions

### Capital Campaign Lead (Non-Profit Fundraising)
** Capital Campaign Chair **  
September 2023 – Present | Providence RI  

- Organized volunteers and led a successful \$2.5 M capital campaign to raise money for capital improvements.
- Direct point of contact for Klote & Associates, the fundraising consultant.
- Initiated cold calls and personal meetings with major donors, securing \$1.2 M in pledges within the first month.
- Managed the CRM database around the campaign, tracking concerns, and targeting members with stewards


---

## Certifications

- AWS Certified Solutions Architect – Professional (2021)
- Certified Scrum Master – Scrum Alliance (2017)

---

## AI/ML Specializations

- Machine Learning Data Lifecycle in Production (2023) 
- Machine Learning in Production (2023)
- Neural Networks and Deep Learning (2024)
- Improving Deep Neural Networks: Hyperparameter Tuning, Regularization, and Optimization (2024) 

---

## Publications

- "Securing the Snowflake Integration on AWS" – *Snowflake, Jan 2023* 
- "Three Literacy Tests for Hiring Data Engineers" – *Better Programming, Apr 2022* 
- "Integrating Snowflake with Glue" – *Towards Data Science, Apr 2021* 
- "Building a Successful Data Initiative" – *Towards Data Science, Oct 2020* 

---

## Education

### University of Utah 
  - Bachelors, Mathematics 
  - Computational Science Master Program

---

## Leadership Skills

- **Data Architecture & Strategy**  
  - Designed and implemented robust data ingestion, ETL, and streaming pipelines to support real-time analytics and reporting.

- **Budget & Resource Management**  
  - Managed multi-cloud budgets and forecasting, optimizing resource allocation and achieving significant cost savings through rightsizing and reserved instances.

- **Team Leadership & Mentorship**  
  - Built and scaled high-performing data engineering teams, established best practices for code quality and data governance, and mentored engineers in career development.

- **Stakeholder & Business Partnership**  
  - Partnered with product, analytics, and executive stakeholders to translate business requirements into scalable data solutions that drive measurable value.

- **Cross-Functional Collaboration**  
  - Collaborated with DevOps, BI, and security teams to integrate data platforms into CI/CD pipelines and ensure compliance with regulatory and security standards.

- **Agile Data Delivery**  
  - Instituted agile methodologies, GitLab pipelines, automated testing, and sprint cadences to deliver reliable, high-impact data features on a weekly cycle.

- **Operational Excellence**  
  - Led data quality frameworks, monitoring, and blameless incident reviews to maintain continuous reliability and drive process improvements.

- **Metrics-Driven Leadership**  
  - Defined and tracked KPIs and dashboards to measure platform performance and business outcomes, guiding strategic decision-making.
