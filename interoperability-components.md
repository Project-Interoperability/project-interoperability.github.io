---
published: true
permalink: /interoperability-components/
layout: default
filename: interoperability-components.md
title: ISE Interoperability Framework Components
---


![](/images/common-profile2.png)

For a detailed description of Exchange Patterns, *Visit the [Exchange Patterns](/exchange-patterns) page.*
## Operational Capabilities

ISE Operational Capabilities are the reference implementations of functional and technical standards and services coupled with the appropriate policy, process, training, outreach, and other infrastructure components. Operational Capabilities provide the mission context or need that drives other components of the ISE interoperability framework. The alignment to the mission need is critical to ensure the operational and technical investments for interoperability also enable mission requirements. To support the mission need, Operational Capabilities may contain elements that include, but are not limited to, operational policy, requirement definitions, use cases, business cases, implementation guidance, sustenance strategies, and any inter-/intra-agency memorandums of understanding (MOUs). These combined elements validate the need for technical capabilities and standards to exist and interoperate across the ISE, at the same time, providing top-down and bottom-up traceability.

Operational Capabilities, however, do no dictate how a capability is to be achieved at the technical level. This ensures maximum design freedom for the operational and acquisition teams as well as flexibility for the technical team to drive interoperability through approved Technical Capabilities and supporting Technical Standards – explained in the next sections.

## Technical Capabilities

ISE Technical Capabilities constitute detailed technical descriptions that provide a conceptual view into the technical implementation and the role of technology. Technical Capabilities, also referred to as Technical Services, are divided into categories of like functionality based on the needs of the organization and updated as the needs change. Technical Capabilities, such as 'Structured Data Management Services' are mainly abstract in nature but their impact is in exposing if two Technical Capabilities are interoperable through the use of [Technical Standards and Specifications](http://project-interoperability.github.io/standards-specifications/). Technical Capabilities: 1) address and support operational needs and requirements, 2) provide reference implementations of one or more technical standards and specifications, and 3) lead to the required technical functionality to realize Operational Capabilities. The goal of Information Interoperability Framework is to encourage interoperability of Technical Capabilities not only internally but across organizations. This allows the ISE participants to:

* Identify new capabilities or re-use existing ones to minimize capability gaps
* Promote interface standardization across technical capabilities to maximize interoperability and reduce maintenance and operation activities; and
* Recognize and embrace new technology paradigms by assessing maturity and establishing roadmap for Technical Capabilities.

As described, the most common types of services and Technical Capabilities applicable to information interoperability include, but are not limited to: discovery, messaging, mediation, security, audit (monitoring), collaboration, enterprise service management, and storage. As stated above, Technical Capabilities may be referred to as Technical Services and can be implemented within an organization or implemented as a [shared service](https://cio.gov/wp-content/uploads/downloads/2013/04/CIOC-Federal-Shared-Services-Implementation-Guide.pdf) across multiple organizations.

The Technical Capabilities often are mission agnostic, as they are modular building blocks that can be linked internally or externally to other Technical Capabilities to enable sharing and interoperability. This practice is important to the interoperability and the exchange pattern discussion and recommends that services should be developed with fundamental characteristics for discovery, building, or extending services for citizens, specific groups of citizens, organizations, or multiple organizations. However, based on an organization's maturity, some of these services may be specialized for specific applications or generalized for a larger service area to promote reuse and interoperability. The table below provides a list of Technical Capabilities and Technical Services along with their descriptions.

## Technical Capabilities and Services

* **Discovery:** Metadata, person, service, and content discovery. Information Interoperability Framework recognizes that the ISE mission partners have different mission applications and needs, and store information about standards, persons, and services differently. However, there is a need for a common taxonomy that helps mission partners find these capabilities consistently.
* **Messaging:** Notifications, alerts, and enterprise messaging.
* **Mediations:** Protocol adaptation and data transformation.
* **Security:** Policy decision (SAML), retrieval (XACML), administration, certificate validation, principle attribute services, and public key infrastructure (PKI).
* **Audit:** Robust auditing capabilities to support accountability, provide discrete non-repudiation, and enhance transparency in security effectiveness.
* **Collaboration:** Conferencing, person discovery, voice over internet protocol (VOIP), collaborative workspaces, and broadcasting.
* **Enterprise Service Management:** Monitoring and quality of service (QoS) of critical resources, service-level agreement (SLA) compliance, exception detection and handling, service utilization, and distributed service management.
* **Storage:** Data source integration and enterprise content delivery network.

## Technical Standards

Technical Standards are intrinsic elements of operational and technical capabilities that are utilized for defining information exchange patterns and information exchange specifications. Technical Standards enable interoperability through advancing design and implementation so that [ISE participants can communicate, exchange data, and make use of the information being shared](http://ise.gov/sites/default/files/ise-asm300-ctiss-issuance.pdf). The ISE standards are technical and foundational in nature and are either specific to a mission need or expansive to tackle challenges across various communities. Technical Standards relating to a mission are developed in conjunction with practitioners from that mission area. An example of this is the ISE effort to promote standards such as [Common Alerting Protocol (CAP)](http://docs.oasis-open.org/emergency/cap/v1.2/CAP-v1.2-os.html) used to disseminate Alerts across the Federal, State, Local, and Private Industry stakeholders. Inversely, Technical Standards relating to capabilities across various communities and organization require general agreement to encourage interoperability rather than fragmentation. An example of these Technical Standards includes the ISE effort to promote Federal Identity, Credential, and Access Management (FICAM) across the Federal Government.

Technical standards are developed by industry organizations, specifically standards development organizations (SDOs), in cooperation with government and industry stakeholders. Technical standards are usually published as a normative standard specification (e.g., [National Information Exchange Model (NIEM),](http://www.ise.gov/national-information-exchange-model-niem) Extensible Mark-up Language (XML), or Web Services Specifications (WSS) that is used to define and measure conformance to interoperability. With the help of these tools, ISE participants focus on standards ranging from data, exchange protocols, services, and metadata standards. However, Information Interoperability Framework does not attempt to dictate how mission applications or tools implement the agreed upon standards.

The Exchange Pattern tool in Project Interoperability describes the relationship between Technical Standards and Exchange Specifications.
