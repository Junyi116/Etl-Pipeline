# ETL pipeline

## Introduction
This repository contains code from an ETL pipeline project I did in my bootcamp

- [Extracts transactional data form a local database](https://github.com/Junyi116/etl-pipeline/blob/main/src/extract.py)
- [Identifies and removes duplicates](https://github.com/Junyi116/etl-pipeline/blob/main/src/transform.py)
- [Loads the transformed data to a s3 bucket](https://github.com/Junyi116/etl-pipeline/blob/main/src/transform.py)
- [Inserts the transformed data into the database]()

## Requirements
- The minimum requirement is Python3 
- Import the necessary libraries as [here](https://github.com/Junyi116/etl-pipeline/blob/main/requirements.txt)

## Step by step:
1. Clone the repository, and change the directory to **etl-pipeline**:
```
git clone https://github.com/Junyi116/etl-pipeline.git
```

- Please contact me for a copy of the database if you do not have it, otherwise update the [file path](https://github.com/Junyi116/etl-pipeline/blob/5040b224b2ea434bcd8a655d5d57daf710a777eb/src/extract.py#L6) accordingly. 
- Create a .env file with connection passwords in your  **etl-pipeline** folder, similar to [this](https://github.com/Junyi116/etl-pipeline/blob/main/.env.copy).
- To execute the code to extract, transform and load data to s3, run the [`main.py`](https://github.com/Junyi116/etl-pipeline/blob/main/main.py) file:

Mac users:
```
python3 main.py
```

Window users:
```
python main.py
```

## Workflow Overview
Here is a workflow diagram illustrating the steps involved in the ETL process:

### ETL Workflow
![ETL Workflow Diagram](https://github.com/Junyi116/etl-pipeline/blob/main/Workflow/ETL.PNG)

For the analysis process following the ETL, refer to the Customer Segmentation repository.

### Analysis Workflow After ETL in Related Projects
![Analysis Workflow Diagram](https://github.com/Junyi116/etl-pipeline/blob/main/Workflow/Analysis.PNG)

## Related Projects
For the analysis process, you can check out my [Customer Segmentation Project](https://github.com/Junyi116/Customer_Segmentation).