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

Coupling and cohesion
High cohesion - low coupling

If a change is to be carried out it is easy to do and there is no need to deploy everything.

One change does not demand a lot of changes here and there.

Cohesion = the code that changes together, stays together.

Coupling
- information hiding
- expose smallest possible of module
- domain coupling
- outside-in thinking. What do service consumers needs.
- Temporal coupling 
- Deployment coupling = everything must be deployed together
    - release train -> release on demand
    - smaller release -> smaller risk
    -> release only what needs to be released
- Domain coupling 
    - What data a single service is given should be minimized

Domain-Driven Design (DDD)
- from:
    Eric Evans, Domain-Driven Design: Tackling Complexity in the Heart of Software (Boston: Addison-Wesley, 2004).
- Aggregate i.e.: Order, Invoice, Stock Item etc. Have life cycle. Should be treated as self-contained units.
- Bounded Context 


2. Planning a Migration

Microservices are being implemented and pushed but in cases the reason is dubious.

"What are you hoping to achieve?"
"Have you considered alternatives to using microservices?"
"How will you know if the transition is working?"









