# UCR3802
Python Scripts to Ingest data from AWS S3 buckets/GCP Google Cloud Storage/ Azure Blob Storage  into DWC Space - OpenSQL 

For AWS S3 Bucket
=================

1. Clone the Repo into your Google Colab Account - https://colab.research.google.com/ and select the file **AWS_S3_DataIngest.ipynb**
2. Adjust the code in the following lines 9-12  with your OpenSQL logon details from Data Warehouse Cloud
3. Adjust the code in the following lines 18,19  with your AWS S3 Bucket Credentials
4. Adjust the code in the following line 24 with your AWS S3 Bucket name
5. Execute CTRL F9 to run all Code Cells 
6. Once successfully executed, you will see the CSV Files replicated as individual tables in OpenSQL container


For GCP Google Cloud Storage
============================

1. Clone the Repo into your Google Colab Account - https://colab.research.google.com/  and select the file **GCP_GCS_DataIngest.ipynb**
2. Adjust the code in the following lines 13-16  with your OpenSQL logon details from Data Warehouse Cloud
3. Adjust the code in the following line 16  with your path to service account json file. Import it in colab and share the path.
4. Adjust the code in the following line 19 with your GCS Bucket name
5. Execute CTRL F9 to run all Code Cells 
6. Once successfully executed, you will see the CSV Files replicated as individual tables in OpenSQL container



For Azure Blob Storage
============================

1. Clone the Repo into your Google Colab Account - https://colab.research.google.com/  and select the file **Azure_Blob_DataIngest.ipynb**
2. Adjust the code in the following lines 10-13 with you Azure blob Storage and container details
3. Adjust the code in the following lines 13-16  with your OpenSQL logon details from Data Warehouse Cloud
4. Execute CTRL F9 to run all Code Cells 
5. Once successfully executed, you will see the CSV Files replicated as individual tables in OpenSQL container



