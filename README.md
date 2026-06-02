### Data Pipeline: Oracle DB to PostgreSQL (PySpark vs. DuckDB + Polars)
This repository provides a comprehensive, production-grade blueprint for building and executing data integration pipelines designed to extract, transform, and load (ETL) data between relational database systems. Specifically, it demonstrates two distinct architectural approaches for migrating data from a source Oracle Database to a target PostgreSQL Database: a distributed computing approach leveraging PySpark, and a modern, highly optimized single-node approach combining DuckDB and Polars.

The pipeline is structured to showcase how to securely connect to an Oracle instance via JDBC drivers, read massive datasets efficiently, apply necessary schema mappings or transformations, and bulk-upload the processed records into PostgreSQL. By providing parallel implementations, this project serves as a practical benchmark and architectural guide, allowing developers to compare the heavy-duty, cluster-ready processing capabilities of Apache Spark against the blazing-fast, memory-efficient, and zero-dependency performance of Polars and DuckDB for medium-sized datasets. Inside, you will find complete source code, connection configurations, dependency setups, and modular scripts that can be seamlessly integrated into your own data engineering workflows.

You can check out the documentation on 
* [PySpark Documentation](https://spark.apache.org/docs/latest/api/python/)
* [DuckDB Documentation](https://duckdb.org/docs/)
* [Polars Documentation](https://docs.pola.rs/)
