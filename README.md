# Data-Deduplication-using-AWS-Lake-Formation-FindMatches

AWS Lake Formation FindMatches is a new machine learning (ML) transform that enables you to match records across different datasets as well as identify and remove duplicate records, with little to no human intervention. FindMatches is part of Lake Formation, a new AWS service that helps you build a secure data lake in a few simple steps.
FindMatches helps you with the following:
<uL><li>Match customers: Link and integrate customer records across different datasets, even where fields do not match exactly (for example, due to different name spellings, address differences, and missing or inaccurate data).</li>
Match products: Match products across different vendor catalogs and SKUs. You can do this even when records do not share a common structure.
Prevent fraud: Identify potentially fraudulent accounts compared to previously known bad actors.</li>
Match other data: Match addresses, movies, parts lists, etc. In general, if a human being could look at your database rows and determine that they were a match, there’s a good chance that FindMatches can help you.</li></ul>

# Project Description<br>
Input:
1- Neat Dataset1 with some records (~2600).
2- Dataset2 with some records (~64,000). Messy,
duplicated.
3- Matching records (labels) (~350).

