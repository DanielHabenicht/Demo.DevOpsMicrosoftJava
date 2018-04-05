# Tutorial for Setting Up a Java DevOps Project with Azure and Sonarcloud

## Preconditions

You need these accounts in order to follow the tutorial.

* Microsoft Account
* Github Account

## Disclaimer

This Tutorial sets you up with a completly free DevOps Environment, but there are some restrictions:

* You should only use the Free Tarif for Azure WebApps, there are also free Database or in App MySQL
* VSTS is only free as the Team is not bigger than 5 persons
* You do only habe 240 free Build minutes each month
* Sonarcloud is only free if you are an Open Source project

## Start

### Setup VSTS

1.  Go to the [Azure Portal](https://portal.azure.com/) and search for 'DevOps Project'
    * Create one. Note the Project Name
2.

### Import your Repo and edit Builds

### Configure Sonarcloud or Sonarqube

1.  Add the [Sonarcloud Extension](https://marketplace.visualstudio.com/items?itemName=SonarSource.sonarcloud) or [Sonarqube Extension](https://marketplace.visualstudio.com/items?itemName=SonarSource.sonarqube) to your VSTS.

2.  Edit your Build Steps

### DevOps Workflow in VSTS

#### Setup Pull Request validation

## Extra

### Setup a CosmosDB - SQL

1.  Go to the [Azure Portal](https://portal.azure.com/).
2.  Search for 'Azure Cosmos DB'.
    * Click the 'Create' Button.
3.  Enter an ID.
4.  Select SQL as API.
5.  Select an Abbonement.
6.  Select New Resource Group and enter a Resource Group name.
7.  Select a Location of your favour.
8.  Maybe tick the 'Pin to Dashboard' option for easier access.
9.  As soon as the Deployment of your Database has succeded go to the Main Page of the Resource
10. Go to Data-Explorer and create a new Collection with
    * Enter a datanase Id and Collection ID
    * Select the minimum Throughput (400) as you only have 100 RU hours free per day.

### Setup an Extra WebApp Environment

### Setup a Build Server
