# Upera coding challenges

## MapReduce
there is a file called "myfile.txt" in the MapReduce directory.
plz write a go program to read that file and count how many times each word has occured in that file in a map reduce like manner and in the end print the results into a json file

![map reduce](https://datascientest.com/en/wp-content/uploads/sites/9/2023/09/illu_schema_mapreduce-04.png "map reduce")
[picture source](https://datascientest.com/en/mapreduce-how-to-use-it-for-big-data) 

the goal of this task is to challenge your familiarity with concurrency in goalng.
as a brief description : mapreduce works by spreading data among multiple computation nodes and have each node do the computation for their part. after that, data of each node is sorted and sent to other nodes to be aggregated ( you can ignore this part in your source code for simplicity if you want and aggregate all of them in the main goroutine).
you can think of gorotuines as computation nodes.

## shoes 
write a simple create CRUD api for the "shoes" table using echo library as router and postgres as your database with the database driver of your choice.
the goal of this task is to challenge your familiarity with common best practices for example : project architecture, logging, security best practice and ....  
1. read api must be able to filter based on all properties of the `shoes` table.
2. update api must be able to switch `brand_name` field to a null value or an actuall value.

you can also suggest ways that you think can improve design of databse, but the suggestions will not be applied in the source code. 

a connection string will be given to you during the interview , please do note that the migration file has already been executed on the database.

you can search or read documentations while writing these programs.
