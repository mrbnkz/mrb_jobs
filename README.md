# mrb_pipeline_jobs: microsoft azure adventureworkslt2017
Goal: Solving Big Data Problems in Your Organization 
# Step One: Data Pipeline Development
Batch processing: This jobs form a workflow of sequenced commands, where the output of one command becomes the input of the next command

# Step Two: Data Modeling and Architecture:
![image](https://github.com/mrbnkz/mrb_jobs/assets/147990007/fbc0deea-1ae7-4959-becb-dfb96adf454f)

# Step Three: Data Integration/ Ingestion
USING SQL QUERIES
SELECT 
s.name AS SchemaName,
t.name AS TableName
FROM sys.tables t
INNER JOIN sys.schemas s
ON t.schema_id = s.schema_id
WHERE s.name = 'SalesLT'
