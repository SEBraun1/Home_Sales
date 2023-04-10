# Home Sales

## Summary Report
This report contains an analysis of a home sales dataset. PySpark was utilized to read in the dataset, create temporary views, run SQL queries, caching, partitioning and saving the data in Parquet format.

This analysis incidates that caching can improve query performance. When data was stored in Parquet format it slowed performance for this particular analyis.