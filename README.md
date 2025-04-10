# Tim Burns

timburnsowlmtn@gmail.com  
(401) 954-1620  
Greater Boston Area  
[linkedin.com/in/tim-burns-5aa6141](https://linkedin.com/in/tim-burns-5aa6141)

---

## Professional Experience

### Evolve Vacation Rentals  
**Principal Data Architect**  
May 2023 – March 2025 | Remote

- Migrated geospatial pricing logic from Salesforce into a scalable REST API stack (GraphQL, Gunicorn, Snowflake), improving pricing precision and agility.
- Built a high-performance microservice with Gunicorn to adjust pricing via real-time geocode queries, enabling faster decision-making. 
  - Impact was that a whole team of full stack engineers could adjust pricing in real-time. 
- Streamed high-volume data into Postgres via AWS SQS for real-time pricing updates with public access and millisecond response times. 

- Replaced Heroku-based architecture with a dbt/Terraform/ArgoCD pipeline.
  - Resulted in a system where we could deploy infrastructure changes and code deployments in minutes rather than hours.
- Implemented a partitioned daily import external table containing all Airbnb and VRBO listings, utilizing Snowflake's capabilities for efficient data management. 
  - Handled hundreds of GBs historical pricing and availability data, improving data accessibility and analysis.
  - Implemented guardrail policies to insulate against pricing shocks while maximizing revenue.

**Key Achievements:**  
- Increased revenue per booked night through targeted pricing and forecasting. 
- Seamlessly migrated a Salesforce UI to a React/GraphQL/Gunicorn/Snowflake stack.
- Improved release velocity code quality via automated testing, merge checklists and test validation. 

**Tech Stack:** Python, Typescript, Node.js, SQL, Snowflake, Salesforce, AWS (EKS, SQS), dbt, Spark, Jupyter, PyTorch, Metabase, Tableau

---

### Abacus Insights  
**Senior Software Engineer**  
October 2021 – April 2023 | Boston, MA

- Extracted real-time custom JSON data and CSV into a data lake from Redshift and Legacy systems and imported into Snowflake using Snowpipe. 
- Analyzed and decomposed complex Oracle queries and translated into Snowflake Data Marts. 
- Integrated Tableau Server deployments into a Terraform pipeline, enabling automated and consistent usage of multiple Tableau platforms.
- Decomposed identity management from Reltio (tree-format) into medallion architecture in Snowflake, improving performance, data accessibility, and usability. 

**Tech Stack:** Python, Java, SQL, Snowflake, Databricks, Oracle, AWS (EMR, Glue, Lambda, SQS, Terraform), dbt, Delta Lake

---

### Kraft Analytics Group  
**Data Architect**  
July 2019 – October 2021 | Foxboro, MA

- Built a real-time transaction summary pipeline with API Gateway, Lambda, Redis. 
  - Project successfully handled 1000s of transactions per second with sub-second latency.
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

**University of Utah**  
Bachelor of Science, Mathematics 
---

## Technical Skills

**Languages:** Python, SQL, Java, Node.js, R 
**Machine Learning & AI:** TensorFlow, PyTorch, Scikit-learn, MLFlow 
**Data Platforms:** Snowflake, Databricks, AWS Glue, dbt 
**Big Data & Pipelines:** Spark, Talend, EMR, RabbitMQ, Dagster, Airflow
**Visualization & BI:** Tableau, Jupyter, QlikView, Metabase 
**Cloud & DevOps:** AWS (S3, Lambda, Redshift), Kubernetes, GitOps, Flyway
