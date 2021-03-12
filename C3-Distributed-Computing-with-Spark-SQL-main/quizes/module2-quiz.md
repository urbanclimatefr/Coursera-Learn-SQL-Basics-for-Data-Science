1. What are the different units of parallelism? (Select all that apply.)

- Partition

- Core

- Executor

- Task

2. What is a partition?

- A portion of a large distributed set of data

3. What is the difference between in-memory computing and other technologies? (Select all that apply.)

- In-memory operates from RAM while other technologies operate from disk

- Computation not done in-memory (such as Hadoop) reads and writes from disk in between each step

- In-memory operations were not realistic in older technologies when memory was more expensive

4. Why is caching important?

- It stores data on the cluster to improve query performance

5. Which of the following is a wide transformation? (Select all that apply.)

- ORDER BY 

- GROUP BY

6. Broadcast joins...

-  Transfer the smaller of two tables to the larger, minimizing data transfer

7. When is it appropriate to use a shuffle join?

- When both tables are moderately sized or large

8. Which of the following are bottlenecks you can detect with the Spark UI? (Select all that apply.)

- Shuffle reads

- Shuffle writes

- Data Skew

9. What is a stage boundary?

- When all of the slots or available units of processing have to sync with one another

10. What happens when Spark code is executed in local mode?

- The executor and driver are on the same machine
