##Spark DataFrame API Examples

#Spark DataFrame API's are:-
1. A distributed collection of rows organised into columns
2. A single abstraction for Selecting, filtering and aggregating and plotting structured data
3. Previously SchemaRDD

#High Level Operations:-
1. Selecting Required columns
2. Joining different data sources
3. Aggregation (count, sum, average, etc)
4. Filtering

#Spark DataFrame is a:-
1. Container for Logical plan
2. Logical plan is a tree which represents data and schema
3. Every transformation is represented as a tree manipulation
4. These trees are manipulated and optimized by catalyst rules
5. Logical plan will be converted to physical plan for execution
