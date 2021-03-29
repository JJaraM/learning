# [Configuration Server FileSystem](http://localhost:3000/post/254)

# Table Of Content
- [Purpose:](#purpose-)
- [Requirements:](#requirements-)
- [Where store the files?](#where-store-the-files-)
- [Is there any name convention for the files?](#is-there-any-name-convention-for-the-files-)

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
