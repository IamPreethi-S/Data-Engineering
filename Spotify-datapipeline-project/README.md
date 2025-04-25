# **Project Overview**

### Spotify Stream Analytics
Generated a synthetic Spotify music stream dataset for dashboard creation. Utilize the Spotify API to generate 10,000 fake event data entries emitted to Kafka. Spark consumes and processes Kafka data, saving 8,000 records to the Datalake. Airflow orchestrates the pipeline. dbt moves and transforms 8,000 records to Snowflake, culminating in the creation of dynamic dashboards

### Dataset Simulation

- **Songs**: Leveraged Spotify API to create artists and tracks data, extracted from set of playlists. Each track includes title, artist, album, ID, release date, etc.
- **Users**: Created users demographics data with randomized first/last names, gender and location details.
- **Interactions**: Real-time-like listening data linking users to songs they "listened."


#### 📌 Key Features:

- Real-Time Data Simulation: Synthetic events flow through Kafka, mimicking user behavior.
- High-Performance Processing: Spark Streaming efficiently handles real-time event processing.

#### 🎯 Goals Achieved:
- Instant Music Insights: Real-time trends and user preferences analysis using Spark Streaming and Delta Lake processing.
- Robust Data Security: Ensuring data integrity through Snowflake's secure warehouse.
- Automated Workflows: Reliable hourly pipelines orchestrated with Airflow, Databricks, and dbt for seamless operations.


##### Acknowledgements!
 Marc Lamberti, Zach Wilson, Nana Janashia and Darshil Parmar 


