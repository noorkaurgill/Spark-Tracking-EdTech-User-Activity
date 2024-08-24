# Tracking User Activity

## Project Summary:
Through this project, we assume to be working in an edtech firm and are creating a service that delivers assessments such that customers like Pearson want to publish their assessments on it. In order to get the data ready for data scientists who work for such customers to run queries on it, we aim to develop a data pipeline by using Kafka to publish and consume messages from a dataset of about 3280 assessments from students in the form of a JSON file in addition to using Spark to transform the messages to land them in Hadoop File Systems. This will prepare the infrastructure to land that data for future queries with tools like SQL and Python. 

## Directory:
1. [assessment-attempts-20180128-121051-nested.json](https://github.com/mids-w205-schioberg/project-2-noorkaurgill/blob/assignment/assessment-attempts-20180128-121051-nested.json)
    - JSON-formatted file with data for 3280 assessments with data like exam time, exam name, attempt details, unique identifiers for user and exam details, and information about accuracy of answers and test-taker submissions
   
2. [docker-compose.yml](https://github.com/mids-w205-schioberg/project-2-noorkaurgill/blob/assignment/docker-compose.yml)
    - Used to spin up the cluster; more thoroughly described in the Project_02.ipynb report

3. [myspark-history.txt](https://github.com/mids-w205-schioberg/project-2-noorkaurgill/blob/assignment/myspark-history.txt)
    - Contains the history from Spark
    

4. [noorkaurgill-history.txt](https://github.com/mids-w205-schioberg/project-2-noorkaurgill/blob/assignment/noorkaurgill-history.txt)
    - Contains the history of the console

5. [Report.ipynb](https://github.com/mids-w205-schioberg/project-2-noorkaurgill/blob/assignment/Project_02.ipynb)
    - Report in the form of a Jupyter notebook that describes queries and spark SQL to answer selected business questions
    - Contains approach, key assumption, and discussion of pipeline features and data
    - Goes into further details to explain code and steps in pipeline creation
    - Inputs are formatted as code
    - Outputs are formatted as either italic or displayed as images
    - Commentary is formatted in bold markdown

7. [README.md](https://github.com/mids-w205-schioberg/project-2-noorkaurgill/blob/assignment/README.md)
    - (This file) Lays out basic overview and directory with descriptions of repository files
    
8. [Folder: **Image Data**](https://github.com/mids-w205-schioberg/project-2-noorkaurgill/tree/assignment/Image%20Data)
    - Contains images that represent outputs of the commands discussed on the report (Report.ipynb)
