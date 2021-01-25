Hi, This is a simple Demo of 3rd Party Int using Mulesoft Studio, ARC with Salesforce.
Created is the implementation of REST Api to insert Records into salesforce.

Initially we see there a set of records in Account Section on Salesforce Platform.
![Before Insert](https://user-images.githubusercontent.com/75612168/105698296-b92e8c00-5f2b-11eb-9b3d-fbc8f5dc96f1.JPG)

Created API on Design Centre of Mulesoft Anypoint.
![Own API](https://user-images.githubusercontent.com/75612168/105698305-ba5fb900-5f2b-11eb-806c-7286a494b63a.JPG)

Lets have a look at out test sample json file to insert in the Transform.
![test json](https://user-images.githubusercontent.com/75612168/105698313-bb90e600-5f2b-11eb-9577-640de2087415.JPG)

After putting the example for Metadata
![API Example](https://user-images.githubusercontent.com/75612168/105698294-b7fd5f00-5f2b-11eb-96df-bd990d7ff02c.JPG)

Now we look at Salesforce Connector - Create with Connection Config.
![Salesforce connector Create](https://user-images.githubusercontent.com/75612168/105698307-baf84f80-5f2b-11eb-81b3-038e853e685f.JPG)

![Config](https://user-images.githubusercontent.com/75612168/105698299-b92e8c00-5f2b-11eb-9a3e-e283ed54565e.JPG)

Let's have a look at our DataWeave where we can see the 2 Metadata Mapping.
![DataWeave](https://user-images.githubusercontent.com/75612168/105698301-b9c72280-5f2b-11eb-8622-6bde7979ba35.JPG)

Test our API using Advanced Rest Client, we can use other Apps such as Postman too.
![Input Data](https://user-images.githubusercontent.com/75612168/105698303-b9c72280-5f2b-11eb-8775-4053a0b0f3c2.JPG)

Sucess Resposne shown to user on ARC.
![Success](https://user-images.githubusercontent.com/75612168/105698312-bb90e600-5f2b-11eb-839e-2f486e13abfe.JPG)

Output from Salesforce
![Shown to user](https://user-images.githubusercontent.com/75612168/105698308-baf84f80-5f2b-11eb-8647-29bb69fd8da4.JPG)

Now we check Salesforce Platform.
Click Accounts, Change view to All Accounts
![Updated Record](https://user-images.githubusercontent.com/75612168/105698317-bc297c80-5f2b-11eb-9849-bffb629a8677.JPG)

Opening up the record for Detailed View.
![Updated More](https://user-images.githubusercontent.com/75612168/105698315-bc297c80-5f2b-11eb-9006-093aa62e4adf.JPG)

# Salesforce DX Project: Next Steps

Now that you’ve created a Salesforce DX project, what’s next? Here are some documentation resources to get you started.

## How Do You Plan to Deploy Your Changes?

Do you want to deploy a set of changes, or create a self-contained application? Choose a [development model](https://developer.salesforce.com/tools/vscode/en/user-guide/development-models).

## Configure Your Salesforce DX Project

The `sfdx-project.json` file contains useful configuration information for your project. See [Salesforce DX Project Configuration](https://developer.salesforce.com/docs/atlas.en-us.sfdx_dev.meta/sfdx_dev/sfdx_dev_ws_config.htm) in the _Salesforce DX Developer Guide_ for details about this file.

## Read All About It

- [Salesforce Extensions Documentation](https://developer.salesforce.com/tools/vscode/)
- [Salesforce CLI Setup Guide](https://developer.salesforce.com/docs/atlas.en-us.sfdx_setup.meta/sfdx_setup/sfdx_setup_intro.htm)
- [Salesforce DX Developer Guide](https://developer.salesforce.com/docs/atlas.en-us.sfdx_dev.meta/sfdx_dev/sfdx_dev_intro.htm)
- [Salesforce CLI Command Reference](https://developer.salesforce.com/docs/atlas.en-us.sfdx_cli_reference.meta/sfdx_cli_reference/cli_reference.htm)
