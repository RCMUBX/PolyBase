### PolyBase

#### What is Polybase?
- Technology for covering use cases:
 - Connecting heterogeneus , remote data surces
 - Data virtualization: Creatin the apparence of local data while  still having the data live remotely
### Scale-out  VS scale-up and massively  parallel Processing (MPP)
 - Parralel Data warehouse was introduced 2012 only for a huge projects

 - Sql server 2016 Enterprise edition V1 we need JVM
 - You can write to a hdfs and blob storage
  **EXTERNAL FORMAT**:Delimeted file, ORC, PARQUET.

 - sql server 2019  connect to MOGODB, SPARK,CosmoDB (need a driver (odbc) for conectivity)
 - You can only READ
  **EXTERNAL FORMAT** You don't have file formats  instead we use odbc conectivity
**External data Sources** 
 - An internal data source tells SQL Server where it can find remote data, that data does not migrate to SQL Server. It lives on the externa data source
 - Can't use AD Authentication, only SQL Authentication for conectivity
**External table**


