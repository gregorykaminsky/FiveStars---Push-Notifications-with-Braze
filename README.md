# Data-Pipeline---S3-Fluentd-and-all-that
A data pipeline between Braze messenger client and Treasure Data storage. Created as part of a consulting project with a company Fivestars.
## Motivation
* Coordinate email promotions organized by Fivestars
* Move data generated by email campaigns administered by Fivestars and send out by Braze to Treasure Data storage.
* Move data queried from Treasure Data to Braze in order to administer said email campaigns. 

## Architecture 
![Project's pipeline](pics/pipeline.jpg)
## Advantages
* Cheap: AWS Lambda used for less then 50 min a day costs $3 a year. 
* Scalable: startup of a lambda is instantenous so arbitrary number can be launched depending on the data volume.
* Fast: instantenous startup and variable lambda numbers makes for a fast transfer of arbitrary data volumes. 


