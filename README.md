---
page_type: sample
languages:
- java
products:
- azure
extensions:
  services: Sql
  platforms: java
---

# Getting Started with Sql - Manage Sql Database - in Java #


  Azure SQL sample for managing SQL Database -
   - Create a SQL Server along with 2 firewalls.
   - Create a database in SQL server
   - Change performance level (SKU) of SQL Database
   - List and delete firewalls.
   - Create another firewall in the SQlServer
   - Delete database, firewall and SQL Server
 

## Running this Sample ##

To run this sample:

Set the environment variable `AZURE_AUTH_LOCATION` with the full path for an auth file. See [how to create an auth file](https://github.com/Azure/azure-libraries-for-java/blob/master/AUTH.md).

    git clone https://github.com/Azure-Samples/sql-database-java-manage-db.git

    cd sql-database-java-manage-db

    mvn clean compile exec:java

## More information ##

[http://azure.com/java](http://azure.com/java)

If you don't have a Microsoft Azure subscription you can get a FREE trial account [here](http://go.microsoft.com/fwlink/?LinkId=330212)

---

This project has adopted the [Microsoft Open Source Code of Conduct](https://opensource.microsoft.com/codeofconduct/). For more information see the [Code of Conduct FAQ](https://opensource.microsoft.com/codeofconduct/faq/) or contact [opencode@microsoft.com](mailto:opencode@microsoft.com) with any additional questions or comments.