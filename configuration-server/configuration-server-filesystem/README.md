# Configuration Server FileSystem

## Purpose:
Create a spring cloud component that will allow to read the configuration from the filesystem, 
this application can be used if you want to store the properties on a server instead of 
a git repository.

## Requirements:
* Java 8

## Where store the files?
The files can be stored in the server-files directory.

## Is there any name convention for the files?
Yes, all files needs to start with application-**<application_name>**-**<environment>**, 
for example: application-ws-dev.yml
