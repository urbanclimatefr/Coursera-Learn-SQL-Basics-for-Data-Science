1. Decoupling storage and compute means storing data in one location and processing it using a separate resource. What are the benefits of this design principle? (Select all that apply.)

- It allows for elastic resources so larger storage or compute resources are used only when needed
- It makes updates to new software versions easier
- Resources are isolated and therefore more manageable and debuggable

2. You want to run a report entailing summary statistics on a large dataset sitting in a database. What is the main resource limitation of this task?

- IO: the transfer of data is more demanding than the computation

3. Processing virtual shopping cart orders in real time is an example of...

- OLTP

4. When are BLOB stores an appropriate place to store data? (Select all that apply.)

- For storing large files
- For cheap storage
- For a "data lake" of largely unstructured data

5. JDBC is the standard protocol for interacting with databases in the Java environment. How do parallel connections work between Spark and a database using JDBC?

- Specify a column, number of partitions, and the column's minimum and maximum values. Spark then divides that range of values between parallel connections.

6. What are some of the advantages of the file format Parquet over CSV? (Select all that apply.)

- Parallelism
- Compression
- Columnar

7. SQL is normally used to query tabular (or "structured") data. Semi-structured data like JSON is common in big data environments. Why? (Select all that apply.)

- It allows for missing data
- It does not need a formal structure
- It allows for data change over time
- It allows for complex data types

8. Data writes in Spark can happen in serial or in parallel. What controls this parallelism?

- The number of data partitions in a DataFrame

9. Fill in the blanks with the appropriate response below:

A _________ table manages  _________  and a DROP TABLE command will result in data loss.

- managed, both the data and metadata such as the schema and data location