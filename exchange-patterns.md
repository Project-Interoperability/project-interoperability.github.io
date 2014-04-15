---
published: true
permalink: /exchange-patterns/
layout: default
filename: exchange-patterns.md
title: Exchange Patterns
---

ISE exchange patterns provide generic solutions to help demonstrate a commonly occurring need for exchange of data or information. A pattern is a description of a core function within an information sharing transaction, and should be described and cataloged along with interoperability technical standards and services requirements as part of an information exchange specification.

An exchange pattern may be developed by different groups within or between organizations depending on the maturity of the organization(s). While most organizations are becoming proficient at defining information exchanges, interoperability often entails an evolved governance model that requires different groups within the organization to agree on the interoperability requirements. Furthermore, the governance model establishes a standardized way of developing patterns that project teams may implement as they develop their mission-specific applications.

The following sections provide details on components of an exchange pattern, and their relationship(s).  The ISE exchange profile used to document the core components of the ISE exchange patterns for an information sharing transaction is the context of the process rules, data, services, and policy related to the exchange pattern.  The ISE exchange specification applies the principles of the context for an exchange into specific technical specifications, standards, and mechanisms necessary to develop interfaces for the exchange.  A federation is an organization of interoperating networks or service providers that apply common governance and processes to implement interoperable information sharing that implements ISE exchange profiles, patterns, and specifications.

## Conceptual Exchange Model

The Conceptual Exchange Model (Figure 1) is a high-level architecture model that aligns three basic information sharing patterns (query/response, broadcast – alerts/warning/notification, and workflow). The Model aligns mechanisms associated with interoperability requirements where more than one exchange pattern is combined to address specific information exchange needs. The orchestration and choreography information exchange hubs are represented in the more complex patterns relating to coordination and messaging broker services.

Figure 1.

![](/images/exchange-patterns1.png)

## Standardized interfaces and Interoperability

In the context of the ISE I2F, Interfaces are protocols or specifications used to transfer information between systems. The concept of interfaces, application program interfaces (APIs), or end points represent the points where technical components of an information exchange interact.  This interaction can be within the information flow of a single system, or it can be at a point that serves as a boundary to the system—but any interface is characterized primarily as a point where a handoff of information occurs—regardless of what exchange pattern the handoff reflects.  Documenting each of these interfaces with the specific technical information necessary to develop another service to interact with that interface is key to achieving interoperability, and is the purpose of the ISE exchange specification.

The ISE exchange profile, pattern, and specification focus on these points for information handoff because they are the point of maximum return for enhancing information exchange between systems without interfering with the solution architecture that system owners deem most appropriate.  As long as the implementation of the information exchange interface an API, or end point is properly documented, the freedom of the system owners and architects is maximized to choose the network or system architecture most appropriate for meeting their mission or business need—whether it be an open source application, proprietary COTS software, data center appliance, or cloud-based utility—so long as that solution is capable of translating its data into the structure required by the interface documented in the ISE exchange specification.  The use and clear documentation of established standards and protocols enables whatever solution architecture is chosen to achieve interoperability with other diverse  solution architectures and systems.

The ISE exchange profile will document the business-level aspects of the interface for the exchange pattern, allowing for a reference architecture or technical guidance view into the interface sufficient to allow executives, program managers, and business owners to understand the function and purpose of the interface as part of the exchange pattern.  The exchange specification, on the other hand, will contain the technical implementation details necessary to establish an instance of the interface, or to interact with it, and is described at the level that a solution architect, enterprise architect, or developer would need to understand how the interface should be implemented.

## Query/Response Pattern

The query/response pattern (Figure 2) is the most common type of information exchange transaction. A sharing partner (service consumer) initiates a request, and a second partner (service provider) may respond to that request with either the requested information or call to a specific resource to obtain the information.

Figure 2.

![](/images/exchange-patterns2.png)

## Broadcast Pattern

A broadcast exchange pattern (Figure 3) can be an independent alert, warning, or notification exchange pattern that is disseminated to a varied set of mission partners across multiple mission areas to communicate details of a specific incident or event(s), and even solicit real-time operational assistance with specific event or case related actions.

Figure 3.

![](/images/exchange-patterns3.png)

Exchange patterns for broadcast messages will include similar elements as documented in the query/response pattern. However, these elements will be further elaborated to define implementation options, including architecture context and associated messaging depending on the type of broadcast. These options would include (along with architectural impact) situations where a service provider broadcasts messages to specific service consumers in a point-to-point messaging pattern, or in a publish-and-subscribe construct where the service provider publishes the broadcast message to a subscription service. These subscription services manage downstream technical requirements capabilities like mediation and transformation services, content-based routing, etc. In most cases there is a system-level acknowledgement that confirms that the message was delivered successfully, with no real mission-specific responses expected as part of this pattern.

## Workflow Pattern

Workflow pattern (Figure 4) exchanges are typically part of an organization’s operational environment where information is routinely moved across mission partners to accomplish day-to-day operational requirements. An example of such an exchange would be a police department sharing complaint information with a court’s case management system. This exchange initiates the creation of a case on the court’s docket and improves operational efficiencies by minimizing redundant data entry and associated data re-entry errors.

Figure 4.

![](/images/exchange-patterns4.png)

## Coordination Pattern(s) – Orchestration and Choreography 

Orchestration is accomplished through the widespread deployment of standardized and composable services, each of which encapsulates a segment of the enterprise and expresses it in a consistent manner. Orchestration is the mechanism to define the sequencing interdependencies of multiple services leading to consolidated/enriched response to the endpoint. 

Choreography is accomplished by defining how messages should flow among interconnected applications and services to ensure optimum interoperability. Choreography includes tools for defining how multiple parties collaborate in peer-to-peer, service-oriented business transactions.  Choreography can be abstract - exchanged messages defined by data type and transmission sequence; portable - defining the data type, transmission sequence, structure, control methods, and technical parameters; or concrete - similar to portable choreography, but including the source and destination (e.g., URLs) as well as security information.

Orchestration shows the complete behavior of each service, whereas the choreography combines the interface behavior of each service.

One possible scenario:

An initial request leads to a number of similar or related responses from multiple sources (Figure 5). A request may trigger the query of similar information from multiple sources, and the responses are consolidated, i.e., orchestrated, to provide a uniform view (if semantically possible) for the service consumer.

Figure 5.

![](/images/exchange-patterns5.png)

An initial request (Figure 5) leads to a number of similar or related responses, often with enriched data.  The request is based on a predefined sequence of services, where a response from one query provides input parameters for subsequent services.  Figure 6 depicts the choreography pattern, the coordination of these query responses into input parameters as they flow through subsequent services. The choreography of these services might generate alerts and warnings based on specific data inputs, events, or thresholds. These exchanges are fairly complex and incorporate a number of different types of technical patterns and capabilities.

Figure 6.

![](/images/exchange-patterns6.png)

## Exchange Profile(s): Elements and Attributes

The standards relevant to information sharing and interoperability requirements, as abstracted in the exchange patterns are categorized as part of an ISE Exchange Profile, consisting of, but not limited to, the following elements: Process Rules, Data, Services, and Policy. These elements align to the attributes necessary for interoperable services between one or more information systems.

## Process Rules: Context and Use

Process rules represent the purpose and scope of the sharing content. Process rules are defined as the rules associated with the exchange profile that allow the exchange package, such as an Information/Exchange Package (IEP) in the form of a XML schema, to play a role in a workflow or a complex multi-exchange environment. Process rules in a workflow might require a digital signature, provide output via reports, notifications etc., or support multiple events (business rules) in a given workflow. The process rules section of the ISE exchange profile may include the following attributes:

* High level description and purpose of the exchange
* Key stakeholders and participants, and their roles
* Exchange definitions in a broader business capability
* Normalized information of the exchange content
* Mechanisms to reuse and extend the exchange as needed to meet specific mission applications without compromising the semantic meaning of the content or the interoperability requirements
* Description of rules and enforced implementation guidance, if available
* Description of any shared services that might be used in processing the exchange

## Data: Context and Use

Data represents the mission information that needs to be shared and how it is represented. Data (or information) interoperability is initiated as the exchange partners agree on a common (and accurate) vocabulary that represents the business needs and preserves the semantic meaning of the information being exchanged. An example of a common vocabulary is the [National Information Exchange Model (NIEM).](https://www.niem.gov/Pages/default.aspx)

Data interoperability is achieved when the exchange partners or the community agrees upon an information exchange package to reflect their specific mission needs. These include standards for vocabularies, ontologies, and models that represent the information that enables clear and unambiguous communication between infrastructure domains, irrespective of the technology products and/or solutions used. The content is produced and consumed without losing the intended semantics and meaning of the exchanged message. Data standards are applicable to a wide range of elements to include raw collected data, messages, and published documents and records. An example of a data standard is the [Geographic Markup Language (GML).](http://www.opengeospatial.org/standards/gml)

Data is a significant component of the pattern; the specific data elements are mission and exchange requirement specific, and best described in the ISE exchange specification section. The data section of an ISE exchange profile, in contrast to the ISE exchange specification, may include the following attributes:

* Description of the type or categories of data to be included in the pattern
* Recommendations/suggestions for specific data standards that may be used
* Methodology and standardized [1] tags for metadata tagging of the payload, and fine grain tagging for specific data elements to indicate identity and access management, security classifications, privacy and civil liberties, use and dissemination, provenance, etc. (if available and applicable)

As federal systems implement compliance with [EO 13587](http://www.whitehouse.gov/the-press-office/2012/12/19/national-strategy-information-sharing-and-safeguarding) and [NSISS](http://www.whitehouse.gov/the-press-office/2011/10/07/executive-order-structural-reforms-improve-security-classified-networks-) requirements for automated, policy-based access control, the data section should additionally include descriptions of sources of automated access control rules that apply to the data, including a link to the authorities for those rules listed in the exchange profile policy section that are intended to be enforced in access controls for the data.

## Services: Context and Use

Services represent how mission information is shared and provide the mechanism that specifies the technical protocols, and communication headers, parameters and attributes, etc. At this level, services may be abstracted to reflect components that need to be addressed consistently for information sharing. These components would include information about service endpoints, connection protocols, and metadata/taxonomy that enables service discovery, and mediation. However, within the mission, and the architectural context, services may be implemented in a number of diverse technology constructs like Web Services, Restful Services, Message Queues (MQ), etc. Attributes of the services section of the ISE exchange profile may include:

- Type of service
- Number of endpoints
- Description of endpoints
- Connection protocols
- Connection parameters including IP addresses, security/identity assertions, etc.
- Metadata for service discovery (based on standardized taxonomy, if available)
- Methodology and standardized tags for metadata tagging of the service specification to indicate identity and access management, security classifications, privacy and civil liberties, use and dissemination, provenance, etc.

## Policy: Context and Use

Policy represents the metadata associated with an exchange that describes rules associated with discovery, sharing, security classification, use, and dissemination of data. Policies may be applied to the entire data exchange, or may be more granular where different types of policies are applied to specific data elements or datasets. Typical application of policies includes tagging of data and services for personally identifiable information, application of identity and access control rules, etc. Attributes of the policy section of the exchange profile may include:

- Description of applicable policies;
- Methodology referenced in previous description of data and services; and,
- Rules around how tags may be applied including interdependencies, sequencing, and application of these rules.

## Exchange Specifications

The exchange specification is the instantiation of an exchange pattern, and once implemented, correctly enables real interoperability. While the ISE exchange profile provides the structure that enables interoperability and provides key considerations and questions to be asked during implementation (explaining the business considerations for executives, program managers, or business owners), an ISE exchange specification is where developers, solution architects, and enterprise architects go to document or find specific information that is provided for the exchange to be implemented.

The exchange specification—an executable, implementable view of an exchange pattern—is based upon specific requirements and supports specific assumptions about the expected deployment architecture or runtime environment. Exchange specifications extend the abstract concepts in the exchange patterns by:

Applying the business (i.e., mission) requirements, rules, and/or policies for mission-specific use; defining the data structures, tags, and other relevant attributes (policy) of the information to be shared (data); and specifying the mechanism involved in the exchange of the information (services).

Exchange specifications may be developed in collaboration with mission partners by applying mission context to the technical standards. Once adopted by a community of interest, exchange specifications significantly enable interoperability across agencies and jurisdictions within that community.

An exchange specification may be developed by a project team with a specific need to implement that capability, or may be a joint effort across multiple teams with a common need. This requires a mature governance model to ensure adequate change control management. An exchange specification is (i.e., becomes) the contract between service producers and consumers that is used to develop interfaces. Even a minor change in the specification without appropriate change management may break operational systems and capabilities. In many cases this type of governance is also provided by industry consortia and standards bodies that help develop some of these exchange specifications into national standards available for use by multiple organizations.

See our [Standards and Specifications](http://project-interoperability.github.io/standards-specifications/) for additional information on the implementation view of exchange specifications, related to the common profile.

## Federation 

A [Federation](http://en.wikipedia.org/wiki/Federation_%28information_technology%29) is multiple computing and/or network providers agreeing upon standards of operation in a collective fashion. Federation helps define the rules of engagement, MOUs, common operating processes, and technical standards and specifications that allow all members of the federation to participate and leverage the capabilities offered by the member organizations.

## Federated Identities Pattern

Federating identities in information technology is the process of linking a person's electronic identity and attributes, which are stored across multiple distinct [identity management](http://en.wikipedia.org/wiki/Identity_management "Identity management") systems, within a trust framework agreed to by the participants in the federation. The trust framework establishes the ground rules for participants, as elaborated in the federation's agreed-upon governance documents, documented processes, and technical specifications. The federated users are able to access multiple capabilities offered by participants by asserting their trusted identities and specific attributes without the need to provision each user in each of the participant systems.

Federation is enabled through the use of open industry standards and/or openly published specifications, such that multiple parties can achieve interoperability for common use. Typical use involves web-based single sign-on, cross-domain user account provisioning, cross-domain entitlement management, and cross-domain user attribute exchange.

## Identity Exchange Pattern

A specific example of a non-generic information exchange pattern is an identity exchange pattern. Identity is a constant for enterprise systems that inevitably involves coordination of at least several query/response exchange patterns, but typically is far more complicated in the enterprise and involves a complex coordination pattern. As identity management for user authentication evolves into more elaborate systems for identity, credentialing, and access management, analyzing identity in the context of exchange patterns helps to highlight the conceptual points in the identity process where an interface could be exposed to: 1) improve the strength of the user's system identity, 2) to apply that strongly authenticated identity to the network security processes (for instance, by providing better user tracking for audit and continuous diagnostics and monitoring), and 3) to provide fine-grained policy-based access control to sensitive resources on the system. For instance, strong authentication is one of the Federal Cybersecurity Cross-Agency Priority Goals for FY13, and the _National Strategy on Information Sharing and Safeguarding_ makes improving identity, credential, and access management one of the top five priority objectives for the federal government. As these conceptual points for potential interfaces in an exchange are identified, developers, enterprise architects, and solution architects are enabled to more effectively adapt their system by identifying the interfaces and additional exchange patterns needed to evolve their mission applications, and security processes, as well as locate where in the system those interfaces and patterns need to be applied.

## Federating Identities

The federation of identity describes the technologies and standards which enable the portability of identity information across otherwise autonomous security domains. The ultimate goal of identity federation is to enable users of one domain to securely access data or systems of another domain seamlessly, and without the need for completely redundant user administration. Identity federation comes in a variety of instantiations, including "user-controlled" or "user-centric" scenarios, as well as enterprise-controlled or business-to-business scenarios.

An advantage of approaching identity as an aggregation of exchange patterns is that the interfaces and patterns identified internal to the system can be leveraged to facilitate participation in identity federations. Developers, enterprise architects, and solution architects can use the exchange patterns identified for their own systems to either take advantage of existing interfaces or to create the new interfaces or exchange pattern instantiations necessary to exchange identity information with other federated systems.

Figure 7

![](/images/exchange-patterns7.png)

## Federated Queries Pattern

A federated query is an implementation of the orchestration pattern, as explained above in the Coordination Patterns, where a user is able to access multiple repositories based on a single query. Figure 8 shows a simple federated query pattern. This pattern is one of many published [service oriented architecture patterns](http://soapatterns.org/) normalized by an international community of architects and practitioners.

![](/images/exchange-patterns8.png)
