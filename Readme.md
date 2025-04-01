## History

Before we dive into basic ETL project, lets focus on the term ELT first, so here before cloud space was expensive, so we used to transform the data and then load to the database, but now cloud storage are relatively cheaper.

So we tend to load first and then perform transformation.

```
So now it make more sence to dump your data into a ware house and transfor later on
```
We have tool in the market, 
Such as DBT, snowflake, Dagster Apache Spark etc.

So we will try to build a ELT pipeline and we will look into basic data modeling techniques such as how to build fact tables, data marts, we will look into snowflake RBAC- role based access control. 

1. DBT for transformation
2. Snowflake for data warehousing.
3. Airflow for Orchestration.


Here we will use snowflake TPC-H dataset.
```
https://docs.snowflake.com/en/user-guide/sample-data-tpch
```

Before this you need to have you snowflake personl account created.
