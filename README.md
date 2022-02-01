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
 # AWS Services Used
  AWS Services                        | Description
------------                        | -------------
Amazon S3 (Simple Storage Service)  | used to store and protect any amount of data.
AWS Lake Formation | service that makes it easy to set up a secure data lake in days.
AWS Glue | ETL service to categorize data for cleaning, enriching and transforming between various data stores.
Athena | for querying the data you import into your data lake.

