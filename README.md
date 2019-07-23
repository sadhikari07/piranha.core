# Lab: Deployment

## Overview
This is a group project completed by John Winters, Sudip Adhikari, Saurav Kadariya, and Peter Tyann.

## Feature Tasks:
Create a full cloud deployment pipeline for Piranha CMS (.NET)
-	Instantiate the appropriate server architecture
-	Create, initialize, and load any databases
-	Connect the application to the created database
-	Automate the entire process with a CI/CD pipeline
-	Connect to github and auto-deploy from master
-	Run all automated tests
## Steps taken:

### To get the latest code and run it locally:
- Fork the repo from https://github.com/PiranhaCMS/piranha.core.git

On your terminal run the following commands:
- git clone https://github.com/PiranhaCMS/piranha.core.git
- cd piranha.core
- cd examples/
- mkdir <some project name>
- dotnet new piranha.web or dotnet new piranha.blog
- dotnet restore
- dotnet run
- On browser enter: localhost:5000

Screenshot of the app running locally:
![Screen Screen](https://github.com/sadhikari07/piranha.core/blob/master/assets/one.png)
![Screen Screen](https://github.com/sadhikari07/piranha.core/blob/master/assets/two.png)
![Screen Screen](https://github.com/sadhikari07/piranha.core/blob/master/assets/three.png)

### To deploy:
