# demo-trigger-dataprep-job-from-gcs

![image](How_to_trigger_Dataprep_jobs_From_Cloud_Storage.png)

Resources for blog post **"How to Automate a Cloud Dataprep Pipeline on File’s Arrival"** (https://xxxxxxxxx)

- **[flow_dataprep_demo.zip](https://github.com/victorcouste/demo-trigger-dataprep-job-from-gcs/blob/master/flow_dataprep_demo.zip)** : Dataprep Flow package than can be imported from Dataprep UI.

- **[Customers.csv](https://github.com/victorcouste/demo-trigger-dataprep-job-from-gcs/blob/master/Customers.csv)** : Customers CSV file used as input of the flow and to be stored in the Google Cloud Storage you want to monitor.

- **[cloud-function.py](https://github.com/victorcouste/demo-trigger-dataprep-job-from-gcs/blob/master/cloud-function.py)** : Background Python function to trigger a Dataprep job when a file is created in a Google Cloud Storage bucket folder. Dataprep job started with REST API call and new file as parameter.

- **[Occupation Mapping Google Sheet](https://docs.google.com/spreadsheets/d/10EvnxBM1jXcJj62K7ovAdcA3I8JMOWGU8XUty4bU_C4/edit#gid=0)** : Google Sheet used as input of the flow for the lookup with the Customers dataset.






