---
published: true
permalink: /ref-arch-template/
layout: default
filename: ref-arch-template.md
title: Reference Architecture Template
---

The reference architecture (RA) template is designed to aid the development of reference architecture artifacts to support interoperability. For each of the [Federal Enterprise Architecture Framework](http://www.whitehouse.gov/omb/e-gov/fea) common approach (CA) domains, the template is a guide to the relevant interoperability requirements and artifacts to be incorporated for interoperability. The template details interoperability goals in each of the domains, as well as instructions for template usage.

The RA template contains an overview of the interoperability goals for each CA domain and the objectives of the artifacts within the domain. Within each domain listed, the RA template provides an overview of the information to be included in each artifact, and instructions on how to develop each interoperability artifact. Each domain is divided into subsets of the domain: for example, the CA business domain is divided into business processes; business models, mission exchange processes, diagrams and flows, other considerations, etc.

In addition, the RA template has been integrated with the Architecture Framework Alignment Grid) with mnemonics mapping each item in the template to the applicable artifact reference in the Grid. When used in conjunction with the Architecture Framework Alignment Grid, the architecture framework can be updated to include interoperability in each domain.

Annually, OMB will receive business and technology architecture information from each department or agency in the form of a high-level, integrated description of the agency's IT-related strategic goals, business objectives, and enabling IT capabilities to include roadmaps. By leveraging the interoperability baseline provided by the Enterprise Architecture Maturity Measurement Template, OMB can more easily understand the departments' and agencies' progress towards integrating interoperability requirements into their existing architectures while improving their abilities to fulfill strategic priorities.

## Purpose

The intent of the Reference Architecture Template is to provide those building specific mission reference architectures with a mission agnostic approach that will result in an enhanced interoperable reference architecture which is specific to a mission when context is applied. In addition, this template can be used with existing reference architectures to plan for improving interoperability maturity based on the results of the Interoperability Maturity Model. This mission agnostic approach is meant to provide key elements and concepts needed to be addressed to make these resulting architectures interoperable.

According to the [DoD Reference Architecture Description](http://dodcio.defense.gov/Portals/0/Documents/DIEA/Ref_Archi_Description_Final_v1_18Jun10.pdf) document, a common theme among the definitions is that the primary purpose of a Reference Architecture is to guide and constrain the instantiations of solution architectures. In addition, a Reference Architecture should:

* Provide common language for the various stakeholders;

* Provide consistency of technology implementation to solve problems;

* Support the validation of solutions against proven Reference Architecture; and

* Encourage adherence to common standards, specifications, and patterns.

In general, a Reference Architecture is an authoritative source of information about a specific subject or mission area that guides and constrains the instantiations of multiple architectures and solutions.

## Structure and Method

The Reference Architecture Template provides the key elements, aligned to the Common Approach to Federal Enterprise Architecture domains: Business, Infrastructure, Data, Application/Service, Security, and Performance domains, to which the concepts of interoperability are applied.

## How to Use this Template

The Common Approach is divided into topic areas within each domain in order to further aid the reference architecture builders in bringing in the right resource expertise when needed. The elements and concepts spelled out are not meant to be exhaustive in nature but used as a guide in building out mission specific reference architectures to be more interoperable within their larger enterprises. In addition, mnemonics are used in this template that map back to the Architecture Framework Alignment Grid as an aid in generating the required architecture artifacts.

Each domain section has "Overview," "Objective of the Architecture," and "Key Focus Areas" explanation paragraphs that apply specifically to the domain section. The purpose of the paragraphs is to give guidance as to context to be focused on when developing the reference architectures within each of the domains.

The impetus of the template is the domain topic areas that contain elements and concepts to be considered when generating the mission specific reference architectures. The reference architect should approach each domain and examine how the listed elements and concepts apply to their specific mission context. In addition, please reference the Architecture Framework Mapping Grid for further guidance on which artifacts to build using this template as guidance.

## Business/Mission Domain Section

**Alignment with Project Interoperability Tools and Resources:** Operational Capabilities, Exchange Patterns.

**Overview:** Describe the lines of business and organizations and the operational concept to be achieved. Provide the overall vision in a strategic context for the capabilities and a high level scope. Provide a hierarchy of capabilities along with description of the capabilities. Show the planned achievement of the capabilities by time frames and what constrains/policies are being applied.

**Objectives of the Architecture:** Describe how the architecture supports the operational enterprise data and makes it discoverable and searchable, i.e., registry or service inventory. For example: The Identity and Access Management initiative provides enterprise information through the use of a global registry to support naming standards and federated access to support other mission capabilities.

Business Models, Diagrams, and Flows:

* Describe the operational concept to be achieved by the architecture and provide the overall vision in a strategic context for the capabilities. (B1)

* Describe the flow of resources/data exchanged from a business perspective between operational activities. (B6)

* General overview of architecture (description and graphics). (B2)

* Policy and Governance considerations: Provide policies, governance information, or applicable laws that will affect the implementation of the architecture. (B5)

* Architecture Environment considerations: Describe any federation, cloud, mobile considerations in the implementation of the architecture. (B5)

* Define the intended interoperability outcomes for each of the business functions within the architecture. (B4)

Business Processes:

* Establish specific exchange patterns for the architecture. (B6)

* Document internal and external information flows. (B6)

* Establish the authoritative sources of information/data along with agreements. (B7)

* Document any dependencies on other work not included in the reference.

* List assumptions used in development of the reference architecture.

Business/Mission Exchange Processes:

* Provide the exchange specification as they relate to the services which would include applicable technical standards from accepted standards bodies (e.g., ISO, IEEE, and NIST). (B9)

* Build use cases for each type of data exchange.

* Information/Data sharing access agreements established and exposed to users. (B8)

Other Business/Mission Domain Considerations:

* Consult security officer to capture applicable security rules/requirements. The results should be captured as annotations with the applicable artifacts

* Consult privacy officer to capture privacy rules/laws Applicable rules and laws should be noted on artifacts in order to capture them as requirements in the implementation lifecycle

* Consult the modernization plan to ensure alignment Modernization plan considerations should be captured on existing artifacts as discovered or as part of "to-be" artifacts

*Key Focus Area: Business - Capture business requirements, preferably using standards and guidance from organizations to develop diagrams, models and layers of abstractions to depict business analysis completed, business processes and organizational and business service relationships using standard methods (e.g., Business Process Model Notation (BPMN), IDEF0, Unified Modeling Language (UML), etc.). Services should be standardized both within and between agencies whenever possible to enhance interoperability. Standards Development Organizations should be primary source, i.e., IEEE, OMG, OASIS, NIST, and ISO, to enable the use of architecture and business models and analysis with regard to comparison or alternatives.*

## Data Domain Section

**Alignment with Project Interoperability Tools and Resources:** Operational Capabilities, Technical Standards, Technical Capabilities, Exchange Patterns, Exchange Specifications.

**Overview:** Describe what data is available to users and the structure (logical and schema) of the data/information at a level necessary for users to understand both what types of data/information is available and the structure of it.

**Objective of the Architecture:** Describe how the data domain is structured, what standards are used, how data/information can be exchanged, and the data lifecycle description in order for external users to be able to both have access and be able to use the data/information.

Data Considerations:

* Provide the high level data concepts and their logical entity relationships. (D1)

* Describe the data requirements and their relationships to the business process rules. (D2)

* Provide roles and responsibilities of the stakeholders involved with the data processes throughout the data lifecycle. (D4)

* Specify organizational relationships with respect to the data and its lifecycle. (D4)

* Describe the governance structure of the information/data throughout the data lifecycle. (D4)

* Describe the information/data management activities throughout the lifecycle. (D4)

* Specify any privacy restrictions on the information/data throughout the data lifecycle. (B6)

Data Interoperability Considerations:

* Describe the flow of resources/data exchanged in order to capture interoperability requirements. (B6)

* Describe how the information/data is secured throughout the lifecycle. (D3)

* Specify how the information/data is tagged/structured (standards used). (D5)

* Specify information exchanges and exchange format (e.g., NIEM). (D5)

* Specify the repeatable set of tasks that demonstrates the commonly occurring need for the exchange of data/information between the domain and users. (D3)

* Specify/describe the information/data flow to include the tagging of the data, discovery, and retrieval. (D3)

Data Standards and Exposure:

* Provide any necessary or relevant data standards to be considered for interoperability. (D5)

* Provide recommendation and/or constraints with regard to data standards within the architecture environment. (D5)

Information Sharing Agreements:

* Document the relevant information sharing agreements (ISAs) and how they affect the exchange of information between users. (D3)

* Provide a description of the business purpose of the information sharing agreements to include the roles and responsibilities of the data throughout the lifecycle. (D4)

* Provide measureable performance criteria for the data (e.g., storage, delivery, discovery, access requirements).

Other Data Domain Considerations:

* Consult security officer to capture applicable security rules/requirements. The results should be captured as annotations with the applicable artifacts.

* Consult privacy officer to capture privacy rules/laws. Applicable rules and laws should be noted on artifacts in order to capture them as requirements in the implementation lifecycle.

* Consult the modernization plan to ensure alignment. Modernization plan considerations should be captured on existing artifacts as discovered or as part of "to-be" artifacts.

*Key Focus Area: Data - Capture the data considerations from how the data is structured, both logically and physically (if necessary), that enables users access to the data/information with enough specificity to be able to use the data/information. In order to enable interoperable solutions, data and information exchanges should be based on open standards. Privacy considerations with respect to the data exchanges should be designed into every data solution. Capture any relationship between the data and business processes and any organizational or policy considerations that need to be addressed.*

## Application/Services Domain Section

**Alignment with Project Interoperability Toolsand Resources:** Operational Capabilities, Technical Standards, Technical Capabilities, Exchange Patterns, Exchange Specifications.

**Overview:** Describe the technical services supporting the common activities used for discovering, identifying, distributing, protecting, and managing the data/ information needed by external users. Provide any applicable service standards, application architecture approaches such as SOA, or other information required to interact with the applications/service within the domain.

**Objective of the Architecture:** Capture the specifications and functional requirements of the applications/service to the level necessary for external application developers can interface with application/services available to externals.

Application/Service Environment Considerations:

* Identify services and common activities, their service component and the interfaces/ interconnections between the services and data assets that are exchanged. (A1)

* Describe recommended and/or possible implementation approaches (e.g., Cloud, SOA, Mobile) and considerations for approaches to be captured in applicable artifacts.

* Provide standards and/or standards requirements for consideration by the reference architecture. These need not be prescriptive but suggestive and currently utilized within the application class. (A6)

* Describe extensibility approaches for future users/applications in any modernization plan artifacts.

* Describe how the application architecture scales for more users in any modernization plan artifacts.

Application/Service Requirements/Constraints:

* Specify the standards/specifications used by the services to make them discoverable.

* Describe the functions performed by the applications/services and any constraints on the data used and the flow of the data. (A3)

* Describe the data assets used by the applications/services and how the data is exchanged between the services. (A2)

* Describe the data flows being exchanged between services and the attributes of the exchanges. (A4)

* Specify any service standards used by or required by the applications/services. (A6)

* Specify how the "service-level agreements" are enforced (manually or machine-level) and the standard/specification if machine-level. (A6)

Application/Service Provider and User Roles and Responsibilities:

* Specify the provider and user roles and responsibilities with respect to application/service lifecycle (Development – O&M – Retirement). (B4)

* Specify rules/laws with respect to products/data/information generated by the applications/services. (A5)

API Considerations:

* APIs published/exposed so that future users can access and create applications with the information/data, describe how the developers access the APIs. (A6)

Cloud Application/Service Implementation Considerations:

* Describe 'continuity of operations' considerations for information/data flows. (A3)

Mobile Application/Service Implementation Considerations:

* Describe mobile implementation considerations that are unique to the mobile architecture environment in addition to service identification. 

*Key Focus Area: Applications/Services - Describe the applications/services and their interconnections between other services as well as the data assets and the information flows that are being used and exchanged. Applications/service and their external interfaces should be standardized when possible for scalability and interoperability purposes. Specify the service standards used and their applicability both internally, externally and reusability.*

## Infrastructure Domain Section

**Alignment with Project Interoperability Tools and Resources:** Technical Capabilities

**Overview:** Describe what types of voice, data, mobile, and video networks will be required to host the IT systems/applications and to transport associate, data, images, and conversations, as well as "what type of physical infrastructure is needed to support the networks" (e.g., buildings, server rooms, points of presence, and other equipment).

**Objective of the Architecture:** Describe the infrastructure interfaces, i.e., protocols, and interface standards, and networks making external domains and applications/ services interoperable. Infrastructure Interfaces:

* Document physical and logical interfaces. (I1)

* Describe interfaces from an architecture perspective. (I1)

* Describe infrastructure performance requirements. (I1)

Interface Standards:

* Specify any technical standards required or recommended for the architecture. (I2)
* Provide a list of emerging standards that need to be considered along with application timeframes. (I2)

Network Considerations:

Specify any network category and considerations or standards for each of the fabrics listed below:

* SBU
* Secret
* Top Secret

*Key Focus Area: Infrastructure - Capture the interface requirements to the level needed to facilitate interoperability between systems as well as specifying the specific standards used by the interfaces, networks, and platforms that we exposed to externals. In addition, use well documented interfaces built on non-proprietary open platforms using standard platform independent data protocols. Host solutions must be compliant with current federal, state, and local policy and standards. Technology convergence that supports infrastructure consolidation should be pursued wherever possible. Describe any network specifications required by external systems in order to exchange data/information and be able to use it.*

## Security Domain Section 

**Alignment with Project Interoperability Tools and Resources:** Operational Capabilities, Technical Standards, Technical Capabilities, Exchange Patterns, Exchange Specifications.

**Overview:** Describe the security policies and considerations required of the architecture that external users will need to interface and get access to the data/information. Provide the necessary security controls to ensure the protection of data/information as it is exchanged within and across security fabrics.

**Objective of the Architecture:** Describe how the proper security controls are to be used by the architecture to ensure data/information protection and allowing access by externals.

General Security Considerations:

* Describe high-level security needs from an interoperability perspective such as the use of common security standards/protocols.

* Describe how proper security controls are to be used to ensure data protection and ensure data access. (S1)

* Describe the event trace of the interactions of the architecture with regard to security controls. (S2)

Security Interoperability Considerations:

* Describe the identity management system used to allow/deny access to the information/data. Role or attribute based?

* Describe the plan to manage/control your identity accounts and provide access controls to systems (for users, system admins, developers, "super users").

* Describe how new user/developers are granted access to the information/data at all stages of the lifecycle.

* Describe information/data access audit method or standard, include the lifecycle for the storage of the audit data.

Other Security Domain Considerations:

* Consult security officer to capture applicable security rules/requirements. The results should be captured as annotations with the applicable artifacts.

* Consult privacy officer to capture privacy rules/laws. Applicable rules and laws should be noted on artifacts in order to capture them as requirements in the implementation lifecycle.

* Consult the modernization plan to ensure alignment. Modernization plan considerations should be captured on existing artifacts as discovered or as part of "to-be" artifacts.

*Key Focus Area: Security - Provide the activities required demonstrating the flow of security information and security controls allowing external users and applications/services access to data assets. Security controls with respect to interoperability should be considered up front for every technology solution. Consider how security controls affect business services and information flows as well as the design and operation of systems, services, and networks. Provide any security constraints such as required security standards used by the architecture.*

## Performance Domain Section

**Alignment with Project Interoperability Tools and Resources:** Operational Capabilities

**Overview:** Describe the metrics necessary to determine whether the implementation of the architecture is successful. Describe also how the metrics will determine the utility of the resulting architecture.

**Objective of the Architecture:** Provide metrics to be used to measure quantitatively how well the architecture is performing and/or how interoperable, as measured by the interoperability requirements within the Information Interoperability Framework.

Architecture Interoperability Performance Considerations:

* Provide a high-level overview of recommended metrics to be considered that will measure the successes of the architecture.

* Review OMB mandated Exhibit 53 and 300 requirements (applies to federal only) and consider how to show the investments contribution to the architecture's interoperability targets.

Interoperability Performance Metrics:

* Provide metrics by which the architecture's performance can be measured from an interoperability perspective and how will the performance be reported. These metrics should aid in deriving the eventual performance requirements of the reference architecture's underlying systems.

*Key Focus Area: Performance - Provide metrics by which to measure and architecture’s interoperability within and between agencies and levels of government. Metrics could include: percentage of open standards adopted and used by systems in the architecture; percentage of applications /services designed to operate in the cloud or web-enabled. If possible specify how each element of the architecture contributes to the overall goal of interoperability both internally and externally to the architecture. Describe the relationship between investments and their alignment with interoperability goals and how to measure the effectiveness of the investments.*
