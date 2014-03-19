---
published: true
permalink: /standards-specifications/
layout: default
filename: standards-specifications.md
title: Standards and Specifications Framework
---

The ISE Standards and Specifications Framework, a tool taken from the ISE Information Interoperability Framework (I2F), provides the descriptive mechanics to develop components and processes necessary to identify and normalize standards to achieve interoperability. The ISE Standards and Specifications Framework describes interoperable information exchange attributes beginning with standardized requirements and definitions. As multiple mission partners recognize their needs, similar capabilities can evolve into common practices that can then be standardized and reused to meet a host of mission needs. Recognizing that specific processes and requirements vary across jurisdictional boundaries, we need to standardize information sharing exchanges into patterns that enable interoperability. The standardization of these exchanges into patterns supports extensibility across unique jurisdictions. Creating standards for interoperability needs supports flexible and robust enterprises. For example, common components of the standards and specifications framework include the development of business and functional requirements along with specific technical requirements for identity and access control (role-based), policy, privacy, conformance, and compliance.  

## Standards Analysis

The convergence of information sharing capabilities and interoperability is essential to standards requirements analysis, as business needs and new technology may require standards that support the implementation of one or more information sharing capabilities.

The ISE Standards and Specifications Framework will:

* Define a framework for understanding standards, the function they serve, what stakeholders are involved, and the relationship between standards;
* Organize standards by function, stakeholder, and content;
* Identify frameworks of mutually supportive standards;
* Group existing and proposed standards by functional area; and,
* Create a model for standards frameworks.

For information exchange to occur, there are typically four key components of that exchange, which you can see in the chart below.

[chart one coming soon]

## Functional Profiles

Functional profiles represent standards, mechanisms, and processes for the consistent documenting and modeling of business requirements. These standards help better define requirements for functional and technical standards and are useful in modeling these requirements. As the requirements and the associated models mature, this helps to identify and articulate commonality in requirements among communities of interest and drive a meaningful discussion toward alignment with an eventual goal of convergence. This leads to national models where requirements are uniformly agreed upon, and these requirements form functional standards.

The chart below provides an example of such a profile.

[chart two coming soon]

In this example, the [UML](http://en.wikipedia.org/wiki/Unified_Modeling_Language) framework is an example of coherent and mutually supportive sets of capabilities that satisfy the needs of a stakeholder group. The data component of this exchange will be [NIEM](http://niem.gov), and NIEM UML profile-based modeling tools will be utilized to develop the requirements and associated models for this exchange. From a services perspective, in the justice and public safety community, the [GRA](https://it.ojp.gov/gra) is the prevalent standard adopted by the community to specify the services components of their exchange. While the GRA is a services specification, there is no associated model to model these services. This identifies a gap in modeling tools that minimizes manual development of the services specification.

On the policy aspects of this framework, there is no clearly defined standard. The justice and public safety community is starting to use their own Global Federated Identity and Access Management Framework; there is no tooling support for this standard. On the process side of this framework, there are tools available that offer support for process modeling, but no real profile that allows for developing domains models for justice and public safety.

## Technical Profiles

Technical profiles represent the actual technical standards developed by the standards development organizations (such as [OASIS](https://www.oasis-open.org/) or [OMG](http://www.omg.org/)), or derivatives of those standards that help address the functional requirements defined using the functional profiles. For a given set of functional profiles, there might be more than one technical profile that addresses the specific needs for that exchange. The chart below provides an example of such a profile.

[chart three coming soon]

In this example, the [XML](http://en.wikipedia.org/wiki/XML)/web services framework is an example of coherent and mutually supportive sets of capabilities that satisfy the needs of a stakeholder group. The actual technical specification standard that powers NIEM is the [W3C Schema Specification](http://www.w3.org/XML/Schema), which is also the normative representation for NIEM. Similarly, from a services perspective, the underlying technical specification for GRA is the WS* set of OASIS standards. If a practitioner has specific [MQ](http://en.wikipedia.org/wiki/Message_queue)-based asynchronous messaging requirements, there might be another option here for an MQ-based service specification. On the policy aspects of this framework, there are a number of options that might be used. The Global Federated Identity and Access Management Framework addresses identity policy requirements; there may also be a need to address privacy policies. There is no specific standard that addresses that today, but [XACML](http://en.wikipedia.org/wiki/XACML) is a solid alternative to help meet those requirements. On the process side of this framework, there are stable standards that help with process representations, but nothing specific to address the need for this domain. In this scenario, more than one technical profile addresses one functional framework.

## Implementation Profiles

Implementation profiles represent the actual reference implementations for the functional and technical profiles. Implementation profiles are instrumental in developing reference implementations that prove the functional and technical profiles. These implementations are often tool-specific and driven by the internal development environments for the participating agencies. The below provides an example of such a profile.

[chart 4 coming soon]

In this example, there might be two or more implementation profiles, but the most common ones in use are based on a [JEE](http://en.wikipedia.org/wiki/Java_Platform,_Enterprise_Edition) or [.NET](http://en.wikipedia.org/wiki/.NET_Framework) framework. The underlying tooling and development capabilities will also vary based on the framework. However, since the focus of the information sharing standards is primarily limited to the sharing of information in motion, the actual details of implementation of this framework almost becomes irrelevant.
