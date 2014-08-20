---
published: true
permalink: /ref-arch-data/
layout: default
filename: ref-arch-data.md
title: Data Domain Reference Architecture Template
---

The reference architecture (RA) templates are designed to aid the development of reference architecture artifacts to support interoperability. To learn more about the purpose, structure, method, and how to use these templates, visit the main [Reference Architecture Template](/ref-arch-template) page.

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

## Architecture Framework Alignment Grid

| **ISE Interoperability Framework: Minimum Requirements for Interoperability** | **ISE Interoperability Framework: Artifact Description** | **FEAF** | **DoDAF/UAF** | **GRA Service Specification Package v 1.0.0** | **IC-related (based on ICEA PAG)** | **TOGAF** |
| Mechanism for identifying and categorizing candidate assets for sharing | (D1) Provide the high-level data concepts and their relationships | • Knowledge Management Plan <br/> • Data Asset Catalog <br/> • Provider-to-Consumer Matrix | • [DIV-1: Conceptual Data Model] | • Domain Vocabulary | •&nbsp;Conceptual Data Model | • Phase C: Information Systems Architecture – Data <br/> • Application Principals, Data Principals |
| Framework for capturing data elements and the relationship between them (semantics) | (D2) Document the data requirements and their relationships, as well as the structural business process rules and metadata where necessary | • Logical Data Model | • [DIV-2: Logical Data Model] | • Message Definitions Mechanism | • Logical Data Model | • Architecture Definitions Document |
| Approach for documenting exchange patterns | (D3) Show the repeatable set of tasks that help accomplish the commonly occurring need for exchange of data/information between exchanging partners, as well as the data relationships and how the data relates to the business activities and their rules/policies | • Business Process Diagram <br/> • Logical Data Model <br/> • Data Flow Diagram | • [OV-5b: Operational Activity Model] <br/> • [DIV-1: Conceptual Data Model] <br/> • [DIV-2: Logical Data Model] <br/> • [OV-3: Operational Resource Flow Matrix] <br/> • [OV-2: Operational Resource Flow Description] | • Message Exchange Patterns |  • Activity Diagram <br/> • Conceptual Data Model <br/> • Logical Data Model <br/> •&nbsp;Information Resource Flow Description <br/> •&nbsp;Information Resource Flow Matrix | • Activity Model <br/> • Baseline and Target Data Descriptions <br/> • Information Exchange Matrix |
| Principles and roles and responsibilities for data managements and stewardship | (D4) Show organizational relationships with respect to the data and its lifecycle | • Knowledge Management Plan | • [OV-4: Organizational Relationships Chart] (along with narrative) | | •&nbsp;Operational Concept Description | • Data Management, Data Migration, and Data Governance |
| Technical standards to design and implement information sharing capabilities in ISE systems | (D5) Provide any necessary or relevant data standards to be considered for interoperability | • Technical Standards Profile | • [StdV-1 Standards Profile] | | • Relevant Mandated Standards | |

