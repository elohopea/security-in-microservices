Monolith to microservices

"Microservices are independently deployable services modeled around business doman. They communicate with each other via networks, and as an architecture choice offer many options for solving the problems you face."
"They are a type of service-oriented architecture (SOA)..."
Microservices are technology agnostic.
Microservices expose the business capabilities via network endpoints.

1. independently deployable
2. modeled around business domain
2.1 Own their own data
3. communicate via network
4. technology agnostic
5. encapsulate data storage and retrieval
6. stable interfaces

Independently deployable
- services need to be loosely coupled
-> guides our way in finding service boundaries

Modeled around a business domain
Conway's law: Any organization that designs a system will inevitably produce a design whose structure is a copy of the organizations communication structure.
Melvin Conway, How Do Committees Invent?

Own their own data

Microservice is an end-to-end slice of business functionality: UI, application logic, and data storage

Advantages from Microservices
- scalability
- robustnes
- tech agnostic
- services can be worked on in parallel
- felixibility

Problems
- network latency
- network failures

Microservices have a cost associated to them.

User interfaces
- could also be broken into pieces and does not have to be a monolith

Technology
- new technology comes with a cost (Kubernetes, Docker, etc.)

Size of a microservice?
- "As small an interface as possible": Chriss Richardson.
- more important question: "How many microservices can you handle?"

Microservices modeled around a business domain aligns IT artifacts with the business domain.

MONOLITH
- single process or multiple modules

Distributed Monolith
- multiple services but all services have to deployd at once
- have all the disadvantages of monolith and all disadvantages of distributed services








