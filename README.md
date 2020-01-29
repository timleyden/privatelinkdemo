[![Deploy to Azure](http://azuredeploy.net/deploybutton.png)](https://portal.azure.com/#create/Microsoft.Template/uri/https%3A%2F%2Fraw.githubusercontent.com%2Ftimleyden%2Fprivatelinkdemo%2Fmaster%2Fdeploy.json)
# Private Link example
A sample ARM template that deploys
1. 2 Peered VNets
2. a Azure Firewall in the first VNET
3. a Azure SQL Server and a database
4. a Private link enabling access to database from the 2nd virtual network

This was originally put together to test connecting to Azure sql from another service like PowerBI via Azure Firewall and private endpoints, but this setup can be tweaked to test a number of different private link and peering scenarios.