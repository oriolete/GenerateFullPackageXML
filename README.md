# GenerateFullPackageXML

Generate a full Package.xml using the Salesforce CLI new commands 

* [describemetadata](https://developer.salesforce.com/docs/atlas.en-us.sfdx_cli_reference.meta/sfdx_cli_reference/cli_reference_force_mdapi.htm)
* listmetadata



### Requirements 

* [Bash shell](https://fr.wikipedia.org/wiki/Bourne-Again_shell)
* [jq](https://stedolan.github.io/jq/)
* [Salesforce CLI](https://developer.salesforce.com/tools/sfdxcli) 


## Usage 

    generateFullPackageXML.sh <APIVERSION>  <OUTPUTFILE>
  
  
 Example 
 
    generateFullPackageXML.sh '45.0' './Package.xml'
