# NoSQL

## Why NoSQL
* **Big Users** Number of concurrent users increased
* **Big Data** Managing Huge load of Unstructured data
* **Cloud Computing** Easy Scaling
* Amount of Data Collected & Stored has increased

# Document DB
* Data On Azure
* Introduction to DocumentDB
* Features
* Constraints & Limitations

## Data on Azure
1. SQL Server / Or Any RDBMS Product
 * Schema changes could result in Downtime.
 * Object Relational Mappings
2. NoSQL
3. MongoDB
4. DocumentDB

## Why DocumentDB
1. Fast Read & Write
2. Easily Scale Up / Down
3. Auto Indexing all documents
4. Query & Transaction support
5. Application logic in form of _Stored Proceedures_ and _Triggers_
6. Support for **REST**
7. Query using Familiar SQL Syntax
8. Fully managed service `Everything managed by Microsoft`

## Limitations / Constraints
1. Each Query can Target only Single collection
2. Transaction cant span across collections
3. No Support for aggregation
4. No *SET* Operations 

# Azure DocumentDB Resources
1. DocumentDB Account   `MaxDB_Account`
2. Database   `/dbs/{id}`
3. Collections `/colls/{id}`
4. Documents  `/docs/{id}`
5. Attachments `/attachements/{id}`

    _Every collection may also contain Stored Procedures, User Defined Functions & Triggers_

### EndPoint URI
    http://synergetics-training.documents.azure.com:443

## Pricing
  - Every collection is **Billed Hourly**
  - Max DB Accounts : 50, [Not Billed when Empty]
  - Document Storage per a/c  1 TB
