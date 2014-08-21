---
published: true
permalink: /ref-arch-security/
layout: default
filename: ref-arch-security.md
title: Security Domain Reference Architecture Template
---

The reference architecture (RA) templates are designed to aid the development of reference architecture artifacts to support interoperability. To learn more about the purpose, structure, method, and how to use these templates, visit the main [Reference Architecture Template](/ref-arch-template) page.

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

### Architecture Framework Alignment Grid

| **ISE Interoperability Framework: Minimum Requirements for Interoperability** | **ISE Interoperability Framework: Artifact Description** | [**FEAF**](http://www.whitehouse.gov/sites/default/files/omb/assets/egov_docs/common_approach_to_federal_ea.pdf) | [**DoDAF**/**UAF**](http://dodcio.defense.gov/dodaf20.aspx) | **GRA Service Specification Package v 1.0.0** | **IC-related (based on ICEA PAG)** | [**TOGAF**](http://pubs.opengroup.org/architecture/togaf9-doc/arch/) |
| Assuring proper security controls are in place to ensure the protection of information as it is exchanged within and across security fabrics | • (S1) Show how the proper security controls are to be used to ensure data protection, as well as data access <br/> • (S2) Event trace can provide service/system details on interactions; only provide if more detail is needed as these take some time to develop | • Security Controls Catalog (Core) <br/> • Certification and Accreditation Documentation | • OV-5b: Operational Activity Model <br/> • SvcV-10c Services Event-Trace Description <br/> • DoD Information Assurance Accreditation Process | • Behavior Model <br/> • Service Policy and Service Contracts | • Same as DoDAF artifacts | • Preliminary Phase <br/> • Business Rules for Handling the Data and Information <br/> • Written and Published Security Policy <br/> • Codified Data Information Asset Ownership <br/> • Risk Analysis <br/> • Data Classification |
| Implement access authorization controls to protect shared data assets | | • Security Controls Catalog | • DoD Information Assurance Accreditation Process | • Service Interfaces | • Uses DoDAF/UAF artifacts | • Disaster Recovery and Continuity Plans |

