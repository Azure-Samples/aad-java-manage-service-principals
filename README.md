---
services: Graphrbac
platforms: java
author: jianghaolu
---

## Getting Started with Graphrbac - Manage Service Principal - in Java ##


  Azure Service Principal sample for managing Service Principal -
   - Create an Active Directory application
   - Create a Service Principal for the application and assign a role
   - Export the Service Principal to an authentication file
   - Use the file to list subcription virtual machines
   - Update the application
   - Update the service principal to revoke the password credential and the role
   - Delete the application and Service Principal.
 

## Running this Sample ##

To run this sample:

Set the environment variable `AZURE_AUTH_LOCATION` with the full path for an auth file. See [how to create an auth file](https://github.com/Azure/azure-libraries-for-java/blob/master/AUTH.md).

    git clone https://github.com/Azure-Samples/aad-java-manage-service-principals.git

    cd aad-java-manage-service-principals

    mvn clean compile exec:java

## More information ##

[http://azure.com/java](http://azure.com/java)

If you don't have a Microsoft Azure subscription you can get a FREE trial account [here](http://go.microsoft.com/fwlink/?LinkId=330212)

---

This project has adopted the [Microsoft Open Source Code of Conduct](https://opensource.microsoft.com/codeofconduct/). For more information see the [Code of Conduct FAQ](https://opensource.microsoft.com/codeofconduct/faq/) or contact [opencode@microsoft.com](mailto:opencode@microsoft.com) with any additional questions or comments.