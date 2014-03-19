---
published: true
permalink: /attribute-exchange/
layout: default
filename: attribute-exchange.md
title: Attribute Exchange
---

[Attribute-based access control (ABAC)](http://csrc.nist.gov/projects/abac/) is one of several methods of access control. ABAC defines an access control policy in terms of a user’s organic attributes (such as users who are Federal employees, who are managers and above, who are in agency X or Y). 

Systems must know these attributes in order to implement ABAC. When a user accesses a system within their own organization, the system can retrieve the attributes from the local source. But when the user from one organization is accessing a system from another organization, there must be mechanism for these attributes to be conveyed – or exchanged – in a trusted manner. 

If you want more information, these sources might be helpful:

* [SAML Attribute Sharing Profile for X.509 Authentication-based Systems](https://www.oasis-open.org/committees/download.php/18058/sstc-saml-x509-authn-att)
* [Guide to Attribute Based Access Control (ABAC) Definition and Considerations](http://nvlpubs.nist.gov/nistpubs/specialpublications/NIST.sp.800-162.pdf)
* [Security Markup Language (SAML) 2.0 Identifier and Protocol Profiles for Backend Attribute Exchange (BAE) v2.0](https://www.idmanagement.gov/sites/default/files/documents/BAE_v2_SAML2_Profile_Final_v1.0.0.pdf)
