
## Lab 4: Data Loading into ATP

## Introduction
With OCI you can upload files to the Oracle Cloud Infrastructure (OCI) Object Storage, creating sample tables, loading data into them from files on the OCI Object Storage.

You can load data into Autonomous Transaction Processig Database using Oracle Database tools, and Oracle and 3rd party data integration tools.

You can load data:
- From files local to your client computer
- From files stored in a cloud-based object store

For the fastest data loading experience Oracle recommends uploading the source files to a cloud-based object store, such as Oracle Cloud Infrastructure Object Storage, before loading the data into your Autonomous Transaction Processing Database.

To load data from files in the cloud into your Autonomous Transaction Processing database, use the new PL/SQL DBMS_CLOUD package. The DBMS_CLOUD package supports loading data files from the following Cloud sources: Oracle Cloud Infrastructure Object Storage, Oracle Cloud Infrastructure Object Storage Classic, and Amazon AWS S3.

In this lab we will insert data into the DB by executing a SQL code snippet.

To **log issues**, click [here](https://github.com/oracle/learning-library/issues/new) to go to the github oracle repository issue submission form.

## Objectives

- Learn how to use the SQL Developer to execute Query
- Learn how to create tables in your database

## Required Artifacts

- Please ensure you are connected to your cloud account and have provisioned an ATP instance. Refer <a href="./Lab1.md" target="_blank">LabGuide1.md</a>
- You have installed Oracle SQL Developer. You can download SQL Developer 18.3 [here](https://www.oracle.com/technetwork/developer-tools/sql-developer/downloads/index.html) and follow the instructions to complete the installation.

## Steps


### **STEP 1: Create Schema for aOne application**

- Connect as admin in SQL Developer and copy and paste <a href="https://github.com/CloudTestDrive/ATPDocker/blob/master/aone/create_schema.sql" target="_blank"> this code snippet</a> to SQL Developer worksheet. We will be using this code to create the schema for our application which will be used in Lab 6.


-   You are now ready to move to the next lab.


## Great Work - All Done!

