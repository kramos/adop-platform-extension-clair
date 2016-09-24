# Service
This directory can contain sub directories containing the method to provision a service.

## Structure 

This component allows following implementations of the service -

 * aws
  * Allows to define a cloudformation template to provision service in aws
 * docker 
  * Allows to define a docker-compose file to spin up on ths same machine / swarm as the ADOP instance. 
