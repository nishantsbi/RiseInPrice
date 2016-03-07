# RiseInPrice
Data Engineering Project for Galvanize MS in Data Science Program.

#Introduction

Aim of this project is to :

Provide a realtime mapping of Geolocation's in San Fransisco where price surge is happenning for Uber Cabs.

Historical analysis on the price surge data to study the surge behavior and how it relates with time.

#Data

Real time Data is being retrieved from uber API using a cron job.

For Historical Analysis once the real time data processing is done the flag is changed to Batch Mode and updated in DB to do Batch Analysis.

#Data Pipeline and Architecture Diagram

![Architecture Diagram](/uberUI/app/images/ArchitectureDiagram.png)







