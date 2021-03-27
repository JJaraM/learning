# Spring Cloud

The following project contains multiple examples of different applications
using the spring cloud infrastructure.

## Config Server
The config server is a spring boot application that will allow us
to share the configuration properties for different applications,
also give us the possibility to refresh the application 
properties on runtime. 

### FileSystem
This config server application will allow us to read the properties
from the filesystem, you may want to use this type of implementation
if you want to store the properties on a server instead of use a git 
repository.
