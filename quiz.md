## Long Quiz in Advanced Systems Integration & Architecture
1. Define Service Oriented Architecture (SOA).
-   Service Oriented Architecture is known for its enterprise-wide approach for software development. What he does is collect reusable software components, or services. This service has codes and data that can be used for specific business functions and these services can communicate with each other over a network, they used standard protocol to provide the functionality of the entire application. Architectural frameworks create a reusable service that can be operated using standard protocol. Also supports the new generation of agile applications that are made for business, application, and technical services.  Architectural frameworks allow us to create external or business partnerships interfaces to project inter-enterprise integration.


2. List and discuss the characteristics of SOA.

-	Standardized service Contracts: It stated its service description or rules or protocol. Services use this to state their purpose or rules, services capabilities, and use standard protocol or standardized service contracts.
-	Loose Coupling: Services optimized their relationship with each other by creating a specific type of relationship that do specific task with this it eliminates the dependency with each other.

-	Abstraction: 
o	This encapsulates or hides its logic/code from the users. 
o	Avoid irrelevant information. 
o	Hides irrelevant information about service.
o	Makes the weakly associated components work.
o	Has a significant role in designing a service composition.

-	Service reusability: Logic or method that can be reused for other services get divided to get its maximum use.

-	Autonomy:

o	Services need to have access to logic/code they encapsulate through abstraction.
o	It needs to have an ability to independently stand for their own logic without getting affected by outside influence.
o	Services must have been isolated.
o	With these you gain benefits of 
	Reliability
	Behavioral predictability

-	Statelessness:
o	The services should be independent.
o	Incorporate state management deferral extensions within the goal.
o	Increase service scalability.
o	Support the service logic and improve its reuse.
-	Discoverability:
o	Services need to be discoverable in a service registry.
o	Services need to have appropriate information for discovery which can also connect with humans.
o	Store metadata in service registry.
-	Composability:
o	Service breaks big problem to small problem. To help with Reusability principle.
o	Service execution should be efficient, and each process needs to be in good condition.
-	Interoperability:
o	Services should use standard methods that anyone can be able to use the service.
o	With all of this, this is also called as principle.


3. Define Microservices.
-	Microservices architectures are made up with loosely relationship, reusable, and specialized with components. Microservices are typically built as individual applications. This way it made them agile, scalable, and resilient as possible. Microservices more likely found in cloud-native architectural approach by using them, teams can update code efficiently use different stacks for different components and scale the component independently with this method it reduces the waste and the cost associated with having to scale applications with much more efficient to load each individual features. Microservices architecture is a cloud-based approach where a single application is built as a collection of loosely coupled and independently deployable services. Every service has its own data model and database in addition to its own stack. Message brokers, event streaming, and REST APIs are how services communicate with one another. Services are categorized by constrained contexts and business capabilities.

Microservices provide many advantages, such as simpler code changes, the freedom for teams to use various technology stacks, and the capacity to scale individual components separately, which lowers waste and expenses related to scaling complete systems.


4. List and discuss the benefits of using Microservices.

-	Independently deployable: 

o	The most important characteristics of microservices is that because of how smaller and independently microservices are compared to SOA.
o	Microservices fit today’s trend with their feature of being small, cross functional around one service or a collection of services and have them to work as agile fashion.
o	The small size of the services with each boundary and communication patterns makes it easier to understand, making its user understand the code much better. With this the contribution to the services might get faster and will benefit the efficiency and morale of the employees.

-	Right tool for the job:

o	In n-tier architectural pattern, an application is commonly shared with stack, and a large relational database but this architectural pattern has its drawbacks. Significant drawbacks are every component of an application shared the same stack, database, and data model even if there is a better tool or much more efficient to use for the job of certain elements.
o	While Microservices model components are deployed independently and just communicate with some sort of combination of event streaming. So, it’s possible for the stack of every component of the service to be optimized for specific services that the application might need. Technology changes all the time so smaller services might be the most efficient thing to use because it is much easier to scale and less expensive to upgrade with much more advanced technology as it becomes available.

-	Precise scaling

o	Microservices individual services can be individually deployed but they can also be individually scaled. The result benefits its user with the proper use it can lessen required infrastructure rather than monolithic applications because they are able to scale only a component that need to be upgraded rather than the entire application needs to be scaled in the case of monolithic application.

-	Microservices and cloud services

o	Microservice are not exclusive for cloud computing but there are important reasons why they applied microservices to it. The reason for it being applied is because of how microservices are getting popular amongst other architectural styles and cloud being popular hosting for this new generation of technology.
o	The benefits of microservices architecture are utilization and cost benefits associated with deploying and scaling components individually. These benefits would still be seen around on premises infrastructure while the real optimization is found when combined with small, independent scalable components coupled with on demand, pay per use infrastructure.
o	Secondly, the most important benefit of microservices is that each component can be easily adapted to the stack efficiently for a specific job. Stack proliferation can lead to serious complexity and overhead when you manage it on your own but when you consume the supporting stack as cloud services can reduce the number of challenges while managing. It is not recommended to do your own microservices, especially when just starting out but it is not impossible.

5. List and discuss the similarities and differences of SOA and Microservices.

-	The similarities of SOA and Microservices are they both made the loosely coupled, reusable, and have their components specialized.

-	Size and scope: When it comes to size and scope Microservices are much more focused on smaller tasks while SOA services are designed to operate with large and enterprise-wide reuse.
-	SOA is intended for enterprise-wide concept which enables the loosely coupled interface to be reused and make the other application to be reuse functionality in other applications. While microservices architecture is an application scoped concept which do enables the internal of a single application to be broken up into single pieces. With this concept it can be easily changed, scaled, and administered an application.
-	Reusability: When it comes to reusability in SOA, the reuse of integrations at the level of enterprise level is the primary goal of the architecture. While the microservices architecture creates microservices components that are reused at runtime throughout an application which led to the application being dependent that reduce agility and resilience. Microservices components way is getting copied and reused the code and accept the data duplication to help improving decoupling.
-	Synchronous calls: The reusable advantage of the SOA stands in this because of the availability of it across the enterprise with the use of API. While microservices applications, synchronous calls call a real time dependency which results to loss of resilience. It may also have a latency which impacts performance. In the entire microservice application communication patterns are based on asynchronous communication, such as event sourcing in which a publish model are used to enable microservices component to remain up to date on the changes happens in the data in another component.
-	Data duplication: The SOA services aims to synchronous get hold and changes directly to its primary source, which improves efficiency when it comes to maintaining complex data synchronization pattern. While microservices applications have local access to all the data that it needs for it to be independent from other microservices and other applications even if it means the need of data duplication which can cause complexity. So, it needs to be handled and maintained well for it to gain the advantages which were microservices features.
-	Communication: The microservices architecture and each service deployed independently with built in communication protocol. While SOA, each service must have shared a common communication protocol for it to work to each other. It is called an ESP, but it has its own weakness, because it can also became the single point of failure for the entire enterprise and when it also slows down the whole enterprise can be affected.
-	Interoperability: Microservices use lightweight messaging protocols while SOA open to much more diverse messaging protocols.
-	Service granularity: Microservices are made up for their specialized services that are designed to do one thing very well. While SOA can handle small, specialized services to enterprises-wide services.
-	Speed: SOA simplify development and troubleshooting. However it also became its weakness and it tends to slow down the operation more than Microservices. Microservices tends to duplicate to minimalize sharing of application.

6. Define Web Services.

-	Web services are part of software that connects itself to the internet with the use of standardized messaging system. It is self-contained, modular, dynamic and can be described, published, located or invoked with the use of a network to produce a product, process and supply chain of a business. Web services is a collection of open protocols and standard that can be used for exchanging data between applications or system over a network. Even if the software is created to multiple programming language it can be process with the use of standardized messaging system to be interpreted by other computers.	

7. List and discuss the benefits of using Web Services.

-	A web service is a managed code unit that may be remotely initiated via HTTP to provide built-in functionality across the network. This enables the functionality of the program to be used by other apps when they are exposed. 

-	Regardless of the technology being utilized, web services encourage interoperability by making communication and data sharing among various applications easier. All the way up to the Service Transport, XML Messaging, Service Description, and Service Discovery levels of their protocol stack, they use standard protocols. 

-	This standardization adds to the platform and technology freedom of applications while improving communication dependability.

-	It implies low-cost operation because it uses SOAP over HTTP protocol, this uses the low-cost internet to be use for implementing web services.

8. List and discuss the characteristics of Web Services.

-	XML-Based:

o	These web services share a language of XML that can be termed as a shared code facilitating their communication with each other. Just as everyone would agree on using a universal interpreter so that communication was available on any device. Imagine technology pieces like they are some people that can speak in one particular language such as English so that they make peace among themselves.

-	Loosely Coupled:

o	It's like being able to make changes on one side, like getting a new phone, and the other side still understands and works with it.

-	Coarse-Grained:

o	Think of it as asking for huge, bundled services and not minutely refined services.

-	Synchronous or Asynchronous:

o	Synchronous is just like having a conversation live when you ask they simply respond back to you. At the same time, asynchronous resembles voicemails; one leaves the reply late after.


-	Supports Remote Procedure Calls (RPCs):

o	When making a web service request, one computer simply tells another computer to carry out an action on its behalf. It’s just as if you called over a neighbor to deliver something to your house.

-	Supports Document Exchange:

o	XML is like a universal language that not only communicates simple data but also handles complex documents. These documents can be as basic as telling someone's address or as intricate as describing an entire book or a detailed request for a quotation.

9. List and discuss the distinct roles in Web Services Architecture.

-	Creator 
o	 It is the creator that generates a web service that shall be accessible by any clients wanting to take advantage of the same.

-	Requestor
o	 A client application seeking service is called a requestor; it is also known as a client. Client applications may be written in .NET, java, or any other programming language and seek for certain function through a web service.

-	 Broker 
o	It’s an application that gives users access to the UDDI That is why I have mentioned the UDDI is used by the client application so that it may find out how is the web service located.

10. List and discuss the Web Services Components.

-	SOAP is a markup language that uses XML format to exchange data between computer systems.
o	SOAP as an acronym is used to mean simple object access protocol.
o	It is an application layer protocol used as a means of connecting different applications.
o	It is cross-platform compatible, meaning it can run on any OS.
o	This specification details how you can encode an HTTP header and an XML file to communicate with two computers.
o	It acts as an open, language and platform neutral.
o	One of its advantages is it can go past server firewalls.

-	WSDL is a language based on XML, which defines web service and their access method.
WSDL refers to Web Service Definition language.
o	It is a markup language specified in XML.
o	It describes how web services are accessed.
o	Businesses can also list themselves and their services online as this is a key aspect of UDDI.
o	It is a way of helping people and business reach the service.

-	UDDI is a standardized description, publication, and finding web services.
o	 Abbreviated as UDDDI, it means Universal Integration.
o	An open framework, which is independent of platform.
o	One of the three that is observed by SOAP and WSDL foundation standards of web services.
o	Web-services description language describes its interfaces for webservices.
o	 A specification for a distributed registry of web services.

