---
published: true
permalink: /common-profile.md
layout: default
filename: common-profile.md
title: Interoperability and Use of the Common Profile
---

### ISE Common Profile Framework Description

The ISE Common Profile Framework Description, which we'll refer to as the Common Profile, provides a structured but modular approach in describing a component to promote reuse, standardization, and interoperability across various subject areas and organizations. Simply put, a common profile is a set of instructions that describes how to achieve a desired outcome. Similarly, the Common Profile supports the mission and business needs across government organizations by identifying a base set of elements, specifications, and/or standards so that these organizations can become interoperable through sharing services and information resources. This is accomplished through documenting the mission/business requirements along with the supporting capabilities and the enabling technical modular components. For example, a community of interest made up of six organizations decides to implement a _Common Desktop Gateway_ (business need) to foster employee mobility and cost avoidance across the community. It would be inefficient and challenging if each organization decided only to implement operational and technical components required in support of the business need internal to its organization, thereby achieving no interoperability or cost avoidance. A Common Profile helps avoid this siloed approach by leveraging a common methodology for referencing standards and specifications across multiple organizations. So, a profile for the _Common Desktop Gateway_ would be developed with the consensus of all six organizations where the operational and technical components can interoperate to provide the users 'same look and feel,' as well access to desired services across the community networks.

As the name suggests, a Common Profile is a structure that is accepted across an enterprise or across multiple organizations. To be "common," the profile follows a set governance process that validates profile structure and mandates its use to deliver a specific mission or business need across the enterprise. The profile, once completed, follows a change management process, similar to that of a living document, and must be discoverable across organizations sharing a common (mission or business) interest.

The Common Profile contains three views that are used to identify the mission or business need of the enterprise, along with operational and technical components to achieve that need. The Common Profile views are: Reference View, Technical Guidance View, and Implementation Instance View. These views are defined as follows:

**Reference View:** Serves as the high-level abstract example or reference for the profiled enterprise component. It includes basic attributes, enterprise entities, and guidance information. The reference view is implementation independent, vendor independent, and sometimes technology independent. The reference view should contain applicable mission needs statements, use cases and reference architecture.

**Technical Guidance View:** A set of one or more base standards, and where applicable, the definition of chosen classes, subsets, options, and parameters of those base standards necessary for establishing the behaviors of a particular function or enterprise component. The technical guidance view is vendor independent and includes basic attributes, enterprise entities, implementation references, guidance, and compliance information.

**Implementation Instance View:** Portrays a specific instance of an implementation and defines discrete configurations and parameters for the given instance. It includes basic attributes, enterprise entities, compliance information, and specific methods and techniques. The implementation instance view may or may not be vendor independent. This is the most detailed and specific view of a profile.

Figure 1 shows a conceptual profile called "Cloud Services;" it has three subordinate Technical Guidance Views (Application Hosting, Compute, and Storage). The Application Hosting View has subordinate (nested) Technical Guidance Views for Operating System and Web Services. An Implementation Instance View for Encryption supports two different Technical Guidance Views (Storage and Operating System). This example highlights the flexibility of the profile structure to adapt to particular needs.

Figure 1.

The relationship between the Common Profile and the ISE Interoperability Framework is depicted in Figure 2.

Figure 2.

The following sections elaborate on the components of the ISE Interoperability Framework and how they align with the components of the Common Profile.

### Reference View

The Reference View (Figure 3) elaborates on ISE Interoperability Framework operational capabilities by providing the basic attributes, enterprise entities, and guidance that is implementation independent, and focuses on describing the mission requirements.

Figure 3.

### Technical Guidance View

The Technical Guidance View (Figure 4) elaborates on ISE Interoperability Framework concepts around technical capabilities, technical standards, and exchange patterns. It is a set of one or more base standards, and where applicable, the definition of chosen classes, subsets, options, and parameters of those base standards necessary for establishing the behaviors of particular function or enterprise component. The technical guidance view is vendor independent and includes basic attributes, enterprise entities, implementation references, guidance, and compliance information.

### Implementation Instance View

The Implementation Instance View (Figure 5) elaborates on the exchange specification area. This view focuses on a specific implementation instance and defines discrete configurations and parameters for the given instance. This view is critical as it allows an organization to tailor the technical implementation based on their existing configuration while still being interoperable through the use of Technical Standards. The parameters in this view include basic attributes, enterprise entities, compliance information, and specific methods and techniques. For example, if a Technical Standard is prescribed in the Technical Guidance View for Storage – a Technical Capability – then the configuration to implement that Technical Capability might vary from organization to organization. This variance can be based on type of storage hardware used or the encryption mechanism in a specific organization. The implementation instance view may or may not be vendor independent. This is the most detailed and specific view of a profile.

Figure 5.

The content for these components are highly tailored based on the mission use case and capability needs. This builds on the high-level descriptions provided in the exchange profiles. Process Rules, Data, Services, and considerations for the Common Profile are delineated in the table below.

### Considerations for the Common Profile
