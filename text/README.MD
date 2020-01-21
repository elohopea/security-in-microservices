# Security in microservices

Microservice architecture differs from a monolith architecture in a fundamental way. In a monolith architecture the software consists of a one large chunk which operates on its own. All communication within the software is to flow within one computer (Really?, source?). In a microservices architecture the software is typically split according to functions (source?). The meaningfull service to the software user typically consists of using a multitude of microservices which together deliver the desired outcome. The services can use a shared database or in a more typical fashion each of the services have their own database. In the monolithic architecture there usually exists a single database (source?, really?).

In a typical singular microservice the database contains all the necessary data for the operation of this service.

The database is a separate entity from the application/service. In a monolith architecture the software needs to communicate with the database which typically is done via web using HTTP/HTTPS. All communication from the service originates from one source and end up in the endpoint. In microservices the services or databases can be "instantiated" as needed and thus the network location might not be known prior.



Questions?
 - If all microservices have their own DB. How does one ensure the CIA?
 - 

##Definitions
###Security (information security)
Confidentiality, Integrity, Availability as is stated in ISO/IEC 27001 -standard for information security.  Critique for CIA / improved definition: https://www.ncbi.nlm.nih.gov/pmc/articles/PMC6450831/
###Microservice


## What is a microservice?
### History
### Present
### Future

## Specific security aspects in microservices

## Development using microservices

## Benefits given in [Wiki](https://en.wikipedia.org/wiki/Microservices#Benefits)
### Modularity
### Scalability
### Integration
### distributed development


