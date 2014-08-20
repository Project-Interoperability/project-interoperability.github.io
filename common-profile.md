---
published: true
permalink: /common-profile/
layout: default
filename: common-profile.md
title: Interoperability and Use of the Common Profile
---

## ISE Common Profile Framework Description

The ISE Common Profile Framework Description, which we'll refer to as the Common Profile, provides a structured but modular approach in describing a component to promote reuse, standardization, and interoperability across various subject areas and organizations. Simply put, a common profile is a set of instructions that describes how to achieve a desired outcome. Similarly, the Common Profile supports the mission and business needs across government organizations by identifying a base set of elements, specifications, and/or standards so that these organizations can become interoperable through sharing services and information resources. This is accomplished through documenting the mission/business requirements along with the supporting capabilities and the enabling technical modular components. For example, a community of interest made up of six organizations decides to implement a _Common Desktop Gateway_ (business need) to foster employee mobility and cost avoidance across the community. It would be inefficient and challenging if each organization decided only to implement operational and technical components required in support of the business need internal to its organization, thereby achieving no interoperability or cost avoidance. A Common Profile helps avoid this siloed approach by leveraging a common methodology for referencing standards and specifications across multiple organizations. So, a profile for the _Common Desktop Gateway_ would be developed with the consensus of all six organizations where the operational and technical components can interoperate to provide the users 'same look and feel,' as well access to desired services across the community networks.

As the name suggests, a Common Profile is a structure that is accepted across an enterprise or across multiple organizations. To be "common," the profile follows a set governance process that validates profile structure and mandates its use to deliver a specific mission or business need across the enterprise. The profile, once completed, follows a change management process, similar to that of a living document, and must be discoverable across organizations sharing a common (mission or business) interest.

The Common Profile contains three views that are used to identify the mission or business need of the enterprise, along with operational and technical components to achieve that need. The Common Profile views are: Reference View, Technical Guidance View, and Implementation Instance View. These views are defined as follows:

**Reference View:** Serves as the high-level abstract example or reference for the profiled enterprise component. It includes basic attributes, enterprise entities, and guidance information. The reference view is implementation independent, vendor independent, and sometimes technology independent. The reference view should contain applicable mission needs statements, use cases and reference architecture.

**Technical Guidance View:** A set of one or more base standards, and where applicable, the definition of chosen classes, subsets, options, and parameters of those base standards necessary for establishing the behaviors of a particular function or enterprise component. The technical guidance view is vendor independent and includes basic attributes, enterprise entities, implementation references, guidance, and compliance information.

**Implementation Instance View:** Portrays a specific instance of an implementation and defines discrete configurations and parameters for the given instance. It includes basic attributes, enterprise entities, compliance information, and specific methods and techniques. The implementation instance view may or may not be vendor independent. This is the most detailed and specific view of a profile.

Figure 1 shows a conceptual profile called "Cloud Services;" it has three subordinate Technical Guidance Views (Application Hosting, Compute, and Storage). The Application Hosting View has subordinate (nested) Technical Guidance Views for Operating System and Web Services. An Implementation Instance View for Encryption supports two different Technical Guidance Views (Storage and Operating System). This example highlights the flexibility of the profile structure to adapt to particular needs.

Figure 1.

![](/images/common-profile1.png)

The relationship between the Common Profile and the ISE Interoperability Framework is depicted in Figure 2.

Figure 2.

![](/images/common-profile2.png)


The following sections elaborate on the components of the ISE Interoperability Framework and how they align with the components of the Common Profile.

## Reference View

The Reference View (Figure 3) elaborates on ISE Interoperability Framework operational capabilities by providing the basic attributes, enterprise entities, and guidance that is implementation independent, and focuses on describing the mission requirements.

Figure 3.

![](/images/common-profile3.png)


## Technical Guidance View

The Technical Guidance View (Figure 4) elaborates on ISE Interoperability Framework concepts around technical capabilities, technical standards, and exchange patterns. It is a set of one or more base standards, and where applicable, the definition of chosen classes, subsets, options, and parameters of those base standards necessary for establishing the behaviors of particular function or enterprise component. The technical guidance view is vendor independent and includes basic attributes, enterprise entities, implementation references, guidance, and compliance information.

Figure 4.

![](/images/common-profile4.png)

## Implementation Instance View

The Implementation Instance View (Figure 5) elaborates on the exchange specification area. This view focuses on a specific implementation instance and defines discrete configurations and parameters for the given instance. This view is critical as it allows an organization to tailor the technical implementation based on their existing configuration while still being interoperable through the use of Technical Standards. The parameters in this view include basic attributes, enterprise entities, compliance information, and specific methods and techniques. For example, if a Technical Standard is prescribed in the Technical Guidance View for Storage – a Technical Capability – then the configuration to implement that Technical Capability might vary from organization to organization. This variance can be based on type of storage hardware used or the encryption mechanism in a specific organization. The implementation instance view may or may not be vendor independent. This is the most detailed and specific view of a profile.

Figure 5.

![](/images/common-profile5.png)

The content for these components are highly tailored based on the mission use case and capability needs. This builds on the high-level descriptions provided in the exchange profiles. Process Rules, Data, Services, and considerations for the Common Profile are delineated in the table below.

## Considerations for the Common Profile

### Process Rules Considerations

#### Reference View

* Detailed description and purpose of the exchange specification including the mission requirements, mission applications participating in the exchange, and any operational/policy considerations for exchanging, using, and disseminating data
* Key stakeholders and exchange partners, and their roles and contact information
* Change management process (if available)
* Role this exchange plays in a broader business capability—when and how to use this exchange
* What this exchange is, and is not

#### Technical Guidance View

* How to extend or reuse this specific exchange, without losing the semantic meaning of the content or compromising baked-in interoperability requirements
* Description of applicable rules not enforced in the specification (and implementation guidance, if available, providing a clear explanation of how these rules need to be implemented when the exchange is implemented)

#### Implementation Instance View

* Description of rules enforced in the specifications, along with key value lists applicable to this exchange
* Descriptions of any shared services that might be used in processing the exchange, and mechanisms/links on how to access and use the service, MOUs that might be needed, and contact information for service owners

### Data Considerations

#### Reference View

* _None_

#### Technical Guidance View

* Data elements and definitions that describe the data to be shared
* Business rules that may be applicable to the entire data set, or specific data elements
* Based on a data vocabulary, identify any data mappings that may be required between the mission data, and appropriate elements in the vocabulary
* If an XML-based vocabulary is used, like NIEM, this data section of the specification will equate to an IEPD that will include all the descriptive sections and an XML schema (the normative specification)

#### Implementation Instance View

* Data model that may describe the structure of the data model
* Actual exchange model for the data
* Based on the maturity of the exchange partners, mission need, and availability of a standardized methodology for data tagging, there may be additional requirements for tagging specific data elements
* If a standardized methodology is not available, then the rules for tagging are often documented and may be implemented in the interface implementation

### Services Considerations

#### Reference View

* _None_

#### Technical Guidance View

* Type of service – this will include information explaining if the service is synchronous, asynchronous, point-to-point, or multiple endpoints, etc. (certain architecture and implementation decisions are driven based on this information)
* Metadata for service discovery (based on standardized taxonomy, if available) 
* Methodology and standardized tags for metadata tagging for the service specification to indicate identity and access management, security classifications, privacy and civil liberties, use and dissemination, provenance, etc. (if available and applicable) 

#### Implementation Instance View

* Number of endpoints
* Description of endpoints – explanation of the type of endpoints and system components that will be participating in the exchange
* Connection protocols – SOAP web services, RESTful services, queues, etc. 
* Connection parameters, including IP addresses, security/identity assertions, etc.

### Policy Considerations

#### Reference View

* _None_

#### Technical Guidance View

* Description of applicable policies and any available taxonomies/executable formats for the policy that may be used to automate/enforce the policy rules 
* Rules for how tags may be applied, including inter-dependencies, sequencing, and application of these rules 
* Processing rules and instructions for policy enforcement to be applied in the runtime environment 

#### Implementation Instance View

* Describe what policies and rules will be enforced in the specification vs. need to be enforced in code during implementation 
