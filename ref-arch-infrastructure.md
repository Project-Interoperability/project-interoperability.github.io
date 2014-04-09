---
published: true
permalink: /ref-arch-data/
layout: default
filename: ref-arch-data.md
title: Data Domain Reference Architecture Template
---

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

### Architecture Framework Alignment Grid

| ISE Interoperability Framework: Minimum Requirements for Interoperability | ISE Interoperability Framework: Artifact Description | FEAF | DoDAF/UAF | GRA Service Specification Package v 1.0.0 | IC-related (based on ICEA PAG) | TOGAF |
| External network connectivity that affects interoperability | (I1) Document the external interface connections | Network Diagram | [SvcV-1 Services Context Description](http://dodcio.defense.gov/dodaf20/dodaf20_services1.aspx) [SvcV-2 Services Resource Flow Description](http://dodcio.defense.gov/dodaf20/dodaf20_services2.aspx) | Provisioning Model | x | Phase D: Technology Architecture |
| The standards at the infrastructure-external interface and technical standards profile | (I2) List the technical standards that apply to services/solutions (I3) List of emerging standards that need to be considered along with timeframes | Technical Standards Profile Technology Forecast | [StdV-1 Standards Profile](http://dodcio.defense.gov/dodaf20/dodaf20_stdv1.aspx) [StdV-2 Standards Forecast](http://dodcio.defense.gov/dodaf20/dodaf20_stdv2.aspx) | Service Model | Relevant Standard Matrix | Environment and Location Diagrams Platform Decomposition Diagram Processing Diagram Network Computing Hardware Diagram Communications Engineering Diagram |
