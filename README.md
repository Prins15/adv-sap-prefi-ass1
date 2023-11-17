## Assignment in Advanced Systems Integration & Architecture
1. Define Service Oriented Architecture(SOA).
- SOA is an architectural approach that involves organizing a software system into service components, which are both highly flexible and reusable. These services, fundamental units with business relevance, are interconnected to create the overall system. In the realm of SOA, each service is designed with minimal dependency on others, enabling independent implementation without being bound by platform constraints. Additionally, SOA underscores the necessity of standardized interfaces for these services, promoting compatibility and interoperability within the architecture.

2. List and discuss the characteristics of SOA.
- Standardized Service Contracts - Services offered within one there is a service inventory adherence to the same contract design guidelines.
- Loose Coupling - Service agreements impose minimal customer pairing prerequisites and are independently separated from their environment surroundings.
- Abstraction - Service agreements only include the necessary details and the scope of available service information is outlined in service agreements
- Reusability - Agnostic logic is expressed and included in services and could be marketed as a reusable business supplies.
- Autonomy - Services have extensive control over their underlying environment for runtime execution.
- Statelessness - Services reduce the amount of resources used by postponing the administration of state data as needed.
- Discoverability - Services are added to utilizing communicative meta-information that can be used to successfully found and translated.
- Composability - Services work well participants in composition, whatever the size and complexity of the arrangement.

3. Define Microservices.
- Microservices in software development embody an architectural and organizational strategy, constructing software from small, autonomous services communicating via well-defined APIs. These services are overseen by small, self-contained teams. The implementation of microservices architectures offers benefits such as enhanced scalability and faster development, fostering innovation, and expediting the introduction of new features to the market.


4. List and discuss the benefits of using Microservices.
- Improved productivity - An application can be constructed and maintained more easily if it is divided up into smaller, independent pieces.
- Increased scalability - Services as well can be spread across several servers, which lessens the impact of more demanding components on performance.
- Better resiliency - makes it easier to find and fix the underlying cause of performance problems. 
- Optimize business functionality - allows for the adaptation of already-existing services for use in various contexts without having to start from scratch with a new module.

5. List and discuss the similarities and differences of SOA and Microservices.
Similarities:

- Service-Oriented Architecture (SOA) - accepts a variety of technologies as long as they follow specifications.   - Microservices - enables different technologies to be used for every service.

- Service-Oriented Architecture (SOA) - employs reusing services                                                   - Microservices - emphasizes independent, small-scale services

*These common features, which provide flexibility and adaptability in software system construction, are shared by both SOA and Microservices.

Differences:
- Service-oriented architecture (SOA) is a software development approach employing services as components for creating business applications, with each service offering a distinct business capability. These services can communicate across platforms and languages, facilitating reuse and the combination of independent services for complex tasks. Microservices architecture is an evolution of SOA, featuring smaller, specialized software components dedicated to specific tasks. Unlike SOA, which has full business capabilities in each service, microservices address SOA's limitations and enhance compatibility with contemporary cloud-based enterprise environments.
