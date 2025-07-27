# Computer
- Application Architecture
- Architectural Style

## Application Architecture
- Composite Architecture 
- Distributed Application
- Evolving Architecture 
- Hybrid Architecture 
- Modular Architecture

### Distributed Application
- Use many smaller application instead of one big monolith
- `UNIX philosophy` : simple commands that only do one thing and do that thing all the time
- Spreads the components of the application across multiple networked nodes, enabling scalability, fault tolerance, and parallel processing
- commonly used in client-server, microservices, service-oriented architecture (SOA), and peer-to-peer (P2P) networking architecture

## Architectural Style
- Client-Server Architecture 
- Component-Based Architecture 
- Event-Driven Architecture (EDA)
- Layered Architecture 
- Microservices Architecture 
- Monolithic Architecture 
- N-Tier Architecture 
- Peer-to-Peer (P2P) Architecture 
- Service-Oriented Architecture (SOA)
- Space-Based Architecture

### Monolithic Application
- Everything is built into a single application.
- Everything exists in one code base and compiles to one binary

### Microservice Architecture
- Architectural style that structures an application as a collection of services that are Independently deployable and Loosely coupled
- Application is divided into smaller, independent services, each responsible for a specific function
- Breaking monolith up from functions/packages to completely separate programs
- Only need to change one individual microservice if there is an update
- Services communicate with each other through APIs, JSON/REST, gRPC, and over a messaging queue
- Easier to scale and maintain, but harder to write

## Other Apps
- [Microservices with Golang](https://github.com/HidayatRivai2020/Golang_Microservice)
