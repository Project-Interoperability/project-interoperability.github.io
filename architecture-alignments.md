---
published: true
permalink: /architecture-alignments/
layout: default
filename: architecture-alignments.md
title: Alignment to Architecture Frameworks
---

Project Interoperability recognizes that mission partners are aligned with different architecture frameworks, though the underlying concepts and principles may be very similar. These frameworks are referenced here so that ISE participants can understand how the interoperability requirements can be put in context of existing enterprise architecture efforts. Project Interoperability provides a higher-level mechanism to align reference architectures. Overviews of common architecture frameworks used by ISE constituents are provided in the [Architecture Framework descriptions](/architecture-frameworks/).

The intent of the Project Interoperabilityis not to drive convergence of architecture frameworks to one, but to foster alignment among these frameworks from an ISE interoperability perspective. OMB's [Common Approach to Federal Enterprise Architecture (FEA)](http://www.whitehouse.gov/omb/e-gov/fea) is available, and U.S. Government mission partners are expected to align with the domains it outlines. Project Interoperability normalizes architectural framework differences by describing interoperability needs, requirements, and alignment in the context of the domains in the Common Approach. This meets the needs of ISE stakeholders and core participants.

## Common Approach (CA) – Architecture Domains

The architecture domains articulated in the [Common Approach to Federal Enterprise Architecture](http://www.whitehouse.gov/omb/e-gov/fea) essentially describe the architecture domains used to support a variety of business and technical needs. Those domains are business, data, performance, security, infrastructure, and applications and systems.

## Alignment of Common Approach to Project Interoperability

The following sub-sections provide a high-level description of the Common Approach domains—Business, Data, Applications and Systems, Infrastructure, Security, and Performance—and their applicability to the ISE.

### Business Domain

The business domain addresses business/mission objectives of a specific architecture or system effort. This section is most relevant to the Operational Capabilities. Areas within the business domain that would be applicable to address interoperability include:

* Alignment of ISE participant architectures to ISE-relevant interoperability and information sharing policies and guidance,

* Mission vision, objectives, and requirements,

* Standards and approaches for capturing business requirements and modeling business processes and information flows,

* Lines of business, capabilities, and activities,

* Common information exchanges for a specific mission scenario/use case, and

* Capture information sharing requirements, constraints, and rules between partners.

### Data Domain

In the data domain, Project Interoperability plays a major role in defining the interoperability requirements. Relevant context includes the relationship to the sections on exchange patterns, technical standards, technical capabilities, and exchange specifications. The data domain builds on the operational context and defines why information needs to be exchanged. The exchange patterns abstract out the interoperability requirements and provide a foundation for how the exchange will be implemented. Technical standards are enablers that provide the vocabularies for sharing to assure that the semantic meaning and the context of the data is not lost during transition and transformation. Technical capabilities provide the architectural context within which the exchange is executed. All of these components focus on the abstracted interoperability framework. The actual data constructs for an information exchange are defined during the process of developing the exchange specification, where technical vocabulary standards are applied to define the data exchange content model and includes:

* Mechanism for identifying and categorizing candidate assets for sharing,

* Framework for capturing data elements and the relationship between them (semantics),

* How the data is structured, what standards are used, and how data/information can be exchanged so users are able to both have access to and use the data/information,

* Technical standards to design and implement information sharing capabilities into ISE systems,

* Approach for documenting exchange patterns,

* Data/information flow to include the tagging of the data, discovery, and retrieval, and

* Principles, roles, and responsibilities for data management and stewardship.

### Applications and Systems Domain

The applications and systems are part of the reference implementation context and should be addressed at the reference architecture level. However, the definition and alignment with exchange patterns during the process of specification development is a critical consideration for achieving interoperability. These considerations align to the international community of business analysts, developers, and architects, whereas the goal of [_intrinsic interoperability_](http://en.wikipedia.org/wiki/Service-orientation_design_principles) is a fundamental concept and accomplished via the _service-oriented_ design approach. This approach encompasses an evolution of design and development practices to achieve agnostic, componentized services as build once and reused many, e.g., [service reusability, predictability, discoverability, abstraction, and standardized contracts](http://serviceorientation.com/serviceorientation/service_orientation_and_interoperability). Applications and systems implications for interoperability include:

* Service standards and frameworks (e.g., service metadata and protocol standards, service-oriented architecture, standard application programming interfaces (APIs)),

* Specifications and functional requirements of the applications/services to the level necessary so external application developers can interface with applications/services, and

* Recommended and/or possible implementation approaches (e.g., cloud, SOA, mobile).

### Infrastructure Domain

The infrastructure domain is a significant enabler in information sharing. While important to interoperability, infrastructure is localized to the sharing partner agencies and should be addressed within the reference architecture sections or during the implementation phase. Architecture implications for interoperability include:

* Interfaces (protocols and interface standards) and networks making internal and external domains and applications/services interoperable,

* Flow or routing of information between network connections and/or across security fabrics/domains,

* Practical design-patterns as groups of technology packets that work well together to support system deployment, and

* Standards, platforms, and products to increase interoperability across partners.

### Security Domain

The ISE plays a major role in defining the interoperability requirements within and across multiple security enclaves. Relevant context includes operational capability, exchange patterns, technical standards, technical capabilities, and exchange specifications. This domain also defines other key concepts around identity, access, and authorization of users to enable secure, authorized access to the right information. The operational context defines why information needs to be protected (security, privacy, classification, etc.). Further, the exchange patterns abstract out the interoperability requirements, provide a foundation for security requirements, and demonstrate how the exchange may be implemented. Technical standards are enablers that provide the technology standards for safeguarding information at rest, and in motion. Technical capabilities provide the architectural context within which the exchange is executed and protected. This will include definition of data tagging at the endpoints and at the fine grain content level. Security implications for interoperability include:

* Proper security controls to ensure the protection of information as it is exchanged within and across security fabrics,

* Access authorization controls to protect shared data assets,

* Metadata to tag the data and describe its pedigree, lineage, source, timeliness, confidence, or other attributes associated with trust, and

* Digital security rules, guidelines, and standards for securely exchanging data and services.

### Performance Domain

The performance domain addresses specific performance requirements among exchanging mission partners in alignment with mission priorities. These are often addressed at the actual implementation level. However, there may be some business sensitivities that will require these requirements to be addressed. Relevant ISE context includes operational capability.

### Common Approach Alignment to the ISE I2F

Interoperability requirements are defined and need to be addressed for each of the domains. Interoperability is achieved when requirements clearly articulate attributes for data, exchange mechanisms, and/or services. The table below delineates the minimum common architecture domain artifacts required for interoperability when utilizing existing architecture frameworks. Project Interoperability focuses on driving the definition of common artifacts and concepts for information interoperability, with the expectation that domain-specific interoperability will be addressed as part of the reference architectures.

![](/images/common-approach.png)

ISE mission partners are aligned with different existing architecture frameworks. It may not be necessary to address all capabilities outlined in each domain of the common approach. Some capabilities will be addressed as part of the reference implementation. The table above defines the initial alignment of the ISE and the common approach. Consistency in how ISE participants address these interoperability requirements within each domain will assist in coordinating activities to define the nationwide ISE capabilities.
