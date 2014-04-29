---
published: true
permalink: /ref-arch-business/
layout: default
filename: ref-arch-business.md
title: Business/Mission Domain Section Reference Architecture Template
---

The reference architecture (RA) templates are designed to aid the development of reference architecture artifacts to support interoperability. To learn more about the purpose, structure, method, and how to use these templates, visit the main [Reference Architecture Template](/ref-arch-template) page.

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

### Architecture Framework Alignment Grid

| **ISE Interoperability Framework: Minimum Requirements for Interoperability** | **ISE Interoperability Framework: Artifact Description** | **FEAF** | **DoDAF/UAF** | **GRA Service Specification Package v 1.0.0** | **IC-related (based on ICEA PAG)** | **TOGAF** |
| Alignment of ISE participant architecture capabilities to ISE relevant interoperability and information sharing policies and guidance | • (B1) Describe the operational concept to be achieved <br/> • (B2) Provide the overall vision in a strategic context for the capabilities and a high-level scope <br/> • (B3) Provide a hierarchy of capabilities along with a description of the capabilities <br/> • (B4) Show the planned achievement of the capabilities by time frames and what constrains/policies are being applied | • Business Operating Plan <br/> • Business Service Catalog <br/> • Concept Overview Diagram <br/> • Strategic Plan | • [CV-1: Vision](http://dodcio.defense.gov/dodaf20/dodaf20_cv1.aspx) <br/> • [CV-2: Capability Taxonomy](http://dodcio.defense.gov/dodaf20/dodaf20_cv2.aspx) <br/> • [CV-3 Capability Phasing](http://dodcio.defense.gov/dodaf20/dodaf20_cv3.aspx) or [PV‑2 Project Timelines](http://dodcio.defense.gov/dodaf20/dodaf20_pv2.aspx) (for Portfolio Management) <br/> • [OV-1: High-level Operational Concept Graphic](http://dodcio.defense.gov/dodaf20/dodaf20_ov1.aspx) | • Business Process Models <br/> • Capabilities <br/> •&nbsp;Provisioning Model | •&nbsp;Operational Concept Description <br/> • Capability Description <br/> • Capability Taxonomy <br/> • Enterprise Guidance Matrix | • Phase A: Architecture Vision, Scope, Stakeholder Management, Communications Plan <br/> • Phase B: Business Architecture, Baseline Descriptions, Business Models, Information Exchange Matrix, Business Node Activities |
| Standards and approaches for capturing business requirements and modeling business processes and information flows | <br/> • (B5) Capture business requirements, preferably using standards from organizations (NIST, IEEE, ISO, etc.) that enable enterprise architecture models and analysis with regard to likewise comparisons between lines of business and organizations <br/> • (B6) Describe the information exchanges and their attributes <br/> • (B7) Document the data requirements and the structural business process rules | Business Process Diagram Logical Data Model | • [DIV-2: Logical Data Model](http://dodcio.defense.gov/dodaf20/dodaf20_div2.aspx) <br/> • [OV-2: Operational Resource Flow Description](http://dodcio.defense.gov/dodaf20/dodaf20_ov2.aspx) <br/> • [OV-3: Operational Resource Flow Matrix](http://dodcio.defense.gov/dodaf20/dodaf20_ov3.aspx) <br/> • [OV-5b: Operational Activity Model](http://dodcio.defense.gov/dodaf20/dodaf20_ov5ab.aspx) | • Enterprise Integration Patterns | • Activity Business Process Diagram <br/> •&nbsp;Operational Concept Description <br/> • Logical Data Model <br/> •&nbsp;Information Resource Flow Description <br/> •&nbsp;Information Resource Flow Matrix | • Business Process Models, Node Connectivity Diagrams, Information Exchange Matrix |
| Considerations for Information Sharing Agreements (ISAs) | (B8) Document the relevant ISAs and how these affect the exchange of information between users | Business Process Diagram | • [OV-2: Operational Resource Flow Description](http://dodcio.defense.gov/dodaf20/dodaf20_ov2.aspx) <br/> • [OV-3: Operational Resource Flow Matrix](http://dodcio.defense.gov/dodaf20/dodaf20_ov3.aspx) <br/> • [OV-6a: Operational Rules Model](http://dodcio.defense.gov/dodaf20/dodaf20_ov6a.aspx) | • Information Model <br/> • Message Exchange Patterns | •&nbsp;Information Resource Flow Description <br/> •&nbsp;Operational Rules Matrix <br/> • Enterprise Guidance Matrix | • Activity Models, Service Levels, Boundaries and Contracts |
| Exchange Specifications and their relation to technical standards and services within a specific mission context. | (B9) Provide the exchange specifications as they relate to the services, to include applicable technical standards from accepted standards bodies (ISO, IEEE, NIST, NIEM) | Technical Standards Profile | • [StdV-1 Standards Profile](http://dodcio.defense.gov/dodaf20/dodaf20_stdv1.aspx) | • Service Interaction Profiles | • Relevant Mandated Standards | • Architecture Definitions, Architecture Requirement Specifications |
