# Build data and AI: Who hacked?

## Module 1: Introduction to Azure synapse Analytics
> What is azure synapse analytics
- Descriptive analytics: “What is happening in my business?”. Answered through the creation of data warehouse. 
- Diagnostic analytics: “Why is it happening?”. Answered through exploring information in the data warehouse. 
- Predictive analytics: “What is likely to happen in the future based on previous trends and patterns?”. By using its integrated Apache Spark engine.
- Prescriptive analytics: looks at executing actions based on real-time or near real-time analysis of data, using predictive analytics
> How Azure synapse analytics works
- Analytics capabilities offered through Azure Synapse SQL through either dedicated SQL pools or serverless SQL pools 
- The serverless resource model is the ideal resource model in occasionally prepare data for ad hoc data exploration and analysis.
- Apache Spark pool with full support for Scala, Python, SparkSQL, and C#. For machine learning workloads, you can use SparkML algorithms and AzureML integration for Apache Spark 2.4 with built-in support for Linux Foundation Delta Lake. 
- Using Azure Synapse Pipelines, you can create and schedule data-driven workflows (called pipelines) that can ingest data from disparate data stores. 
- Perform operational analytics with near RT processing: data changes in the transactional system, the changed data is fed to the analytical store in a Column store format from which Azure Synapse Link can query with no disruption to the source system.
- Single web UI to access all azure synpase analytics capabilities
- Integrate a variety of Azure data platform technologies, including Primary ADLS Gen2 account URL, SQL endpoint, SQL on-demand endpoint, workspace web URL, SQL pools and apache spark pools.
- Azure Synapse Studio is where you can develop TSQL scripts and notebooks. 

> When to use?
- Advanced analytics
- Data exploration and discovery
- RT analytics
- Data integration
- Integrated analytics

## Module 2: Design a modern data warehouse using azure synapse analytics
> Describe a modern data warehouse
- Increased volumes of data, new varieties of data, data velocities (RT)
> Define a modern data warehouse architecture
- Process of building a modern data warehouse consists of: data digestion and preparation; making the data ready for consumption by analytical tools; providing access to the data in shaped format so that it can be easily consumed by data visualization tools. 
- Data ingestion and preparation: Build a data lake to store data with azure data lake store Gen2. To ingest, can use code-free ETL/ELT, SQL server integration services packages (SSIS), Azure databricks (shape data format and prep it using a notebook). 