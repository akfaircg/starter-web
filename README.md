# Overview
> This is a sample wishlist service which can be used in YaaS user stories. you can check those user stories on Jira under YaaS component.

## Prerequisites
> In order to build this project you need to have **maven** installed on your computer. To download maven [click here](https://maven.apache.org/download.cgi#).
>
> To run this project on the cloud you need to have the following
>* An account in one of the cloud service providers.  At the time of creating this document YaaS recommended to use PWS as it has a trial period of 60 days.
>* Some knowledge on how to use cloud foundry CLI. 
  
## Build project
>
>+ Open windows command line
>+ Navigate to the root directory where the **pom.xml** file is located.
>+ Run this command  
  `mvn clean package`


## Run project       
> This project can be run in locally as well as over the cloud.
>* To run it locally open windows command line and navigate to the root directory where the **pom.xml** is located and run  
>  `mvn jetty:run`
>    
>   you can test it over this URL  `http://localhost:8080`
>* To run it on the cloud you can check the How to deploy service project using cloud foundry document over [here](https://faircg.atlassian.net/browse/UP-58).
