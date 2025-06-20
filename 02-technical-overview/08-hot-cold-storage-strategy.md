# Hot & Cold Storage Strategy

## How Silencio Stores Data: Balancing Quick Access and Cost-Effectiveness

**Hot Storage in PostgreSQL:** We use PostgreSQL for our hot storage, maintaining data for up to one month. This allows us to easily access the most recent data for quick analysis and retrieval.

**Daily Data Pipeline:** Every day, we run a pipeline that extracts the oldest daily partition of data from PostgreSQL. This data is then moved to AWS S3 Glacier cold storage in Parquet format. This helps us reduce storage costs while ensuring that historical data remains intact and accessible when needed.

**Decentralized Storage with Filecoin:** We also utilize decentralized storage with Filecoin, adding an extra layer of security. By storing our data across a distributed network, we enhance its resilience and availability.

This storage strategy ensures that both current and historical data are securely stored and accessible, and it is cost-efficient, giving users peace of mind when accessing our services.
