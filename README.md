# Data-Deduplication-using-AWS-Lake-Formation-FindMatches

# Purpose
AWS Lake Formation FindMatches is a new machine learning (ML) transform that enables you to match records across different datasets as well as identify and remove duplicate records, with little to no human intervention. FindMatches is part of Lake Formation, a new AWS service that helps you build a secure data lake in a few simple steps.
FindMatches helps you with the following:
<uL><li>Match customers: Link and integrate customer records across different datasets, even where fields do not match exactly (for example, due to different name spellings, address differences, and missing or inaccurate data).</li>
<li>Match products: Match products across different vendor catalogs and SKUs. You can do this even when records do not share a common structure.
<li>Prevent fraud: Identify potentially fraudulent accounts compared to previously known bad actors.</li>
Match other data: Match addresses, movies, parts lists, etc. In general, if a human being could look at your database rows and determine that they were a match, there’s a good chance that FindMatches can help you.</li></ul>

# Project Description<br>
Input:
<ul><li>Neat Dataset1 with some records (~2600).</li>
  <li>Dataset2 with some records (~64,000). Messy, duplicated.</li>
  <li>Matching records (labels) (~350).</li>

Combined the two datasets into a single file with a new column that indicates the source of each record, and provided a label file (the “perfect mapping”) in a format compatible with FindMatches.<br>
The matching process includes the following steps:<br>

  <ul><li>Catalog your data with the AWS Glue Data Catalog.</li>
    <li>Create a new FindMatches ML transform for your data.</li>
    <li>Teach FindMatches by providing labeling examples of matching and non-matching records.</li>
    <li>Review match quality metrics and upload more labels if match quality is not yet sufficient.</li>
    <li>Create an AWS Glue ETL job that uses your FindMatches transform.</li>
    <li>Review the output.

# AWS Services Used<br>
  
  
AWS Services                        | Description
------------                        | -------------
Amazon S3 (Simple Storage Service)  | used to store and protect any amount of data.
AWS Glue | ETL service to categorize data for cleaning, enriching and transforming between various data stores.

