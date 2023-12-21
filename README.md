## UK National Rail Data Pipeline & EDA
For this project, we created a data pipeline to gather data from
the National Rail Data Portal, which streams live train movement
data from the UK National Rail system.  We built the pipeline using
Kafka producer and consumer and containerized the application in Docker.  Collected data 
was stored to an AWS postgres database.  The pipeline ran for a couple
of days. Once that data was collected, we read data into a Jupyter Notebook
and performed EDA, answered some business questions and created
visualizations.

## API info
Met Office "Getting Started" guide:
https://www.metoffice.gov.uk/services/data/datapoint/getting-started

Registration for National Rail Data Portal:
https://opendata.nationalrail.co.uk/registration

## File Guide
All information about building and running the pipeline found in zip file:
**final_project.zip** 
