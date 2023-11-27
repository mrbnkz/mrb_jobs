# mrb_pipeline_jobs: microsoft azure adventureworkslt2017
Goal: Solving Big Data Problems in Your Organization 
# Step One: Data Pipeline Development
Batch processing: This jobs form a workflow of sequenced commands, where the output of one command becomes the input of the next command

# Step Two: Data Modeling and Architecture:
![image](https://github.com/mrbnkz/mrb_jobs/assets/147990007/fbc0deea-1ae7-4959-becb-dfb96adf454f)

# Step Three: Data Integration/ Ingestion
USING SQL QUERIES to get schema_name and table_name 

![image](https://github.com/mrbnkz/mrb_jobs/assets/147990007/90073c89-3b6b-4434-aa6e-1af282d97e76)

After getting the table_names and schema_names, then copy the file into the azure datalakegen2 from microsoft SQL server management studio, using azure datafactory (ADF)

![image](https://github.com/mrbnkz/mrb_jobs/assets/147990007/d1950b04-d268-4046-8dc0-bff90229a742)

# Step Four: Data Transformation
* Transform and clean data to make it suitable for analytical and reporting purposes.
* Handle data enrichment and data augmentation where necessary.

* Stage One: Mount Storage on azure datalakegen2 storage into azure databricks using python
  ![image](https://github.com/mrbnkz/mrb_jobs/assets/147990007/6319d445-5b8c-4615-8565-42291d023011)
  ![image](https://github.com/mrbnkz/mrb_jobs/assets/147990007/0a0a4080-37d8-4a5c-bac2-c3b008ac2bfd)

* Stage Two: Transform the raw files(Adjust the timestamp of the data and then convert it into delta format) using Python and PySpark
  ![image](https://github.com/mrbnkz/mrb_jobs/assets/147990007/23d9f6aa-5f29-481e-ad15-3722c18bd5c7)
  
* Stage Three: 
  
