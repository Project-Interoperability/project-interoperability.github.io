---
published: true
permalink: /ep-use-case/
layout: default
filename: ep-use-case.md
title: Exchange Patterns Use Case
---

## National Virtual Pointer System

### Background

In an effort to identify investigative overlaps and to increase efficiency and officer safety, Regional Information Sharing Systems (RISS) centers and High Intensity Drug Trafficking Areas (HIDTAs), in partnership with the Drug Enforcement Administration (DEA), the International Justice and Public Safety Network (Nlets), and the National Alliance of State Drug Enforcement Agencies (NASDEA,) developed the [National Virtual Pointer System](http://www.gao.gov/assets/660/653527.pdf) to connect law enforcement officers who may be investigating the same or related cases.

NVPS is a system that connects multiple existing investigative target deconfliction databases by granting access to participating federal, state, local, and tribal law enforcement agencies through any one of the participating systems. Once agents and officers enter the subjects of their current investigations into their target deconfliction database, the [system automatically notifies them](http://www.ncirc.gov/documents/public/supplementaries/law_enforcement_intelligence.pdf) if another NVPS participant is investigating the same target. The systems do not directly communicate with each other but are connected to the NVPS message hub, which validates and routes data if the mandatory minimal data elements are submitted as part of the target deconfliction database entry.

### Scenario Participants

Organizations and their Information Sharing Networks: 

* **Junction City, KS Police Department:** Local databases and the Kansas State Intelligence System (available via RISSNET)
* **Kansas City DEA Interdiction Task Force:** DEA NDPIX entry via DOJ Network routed to the NVPS Message Hub via Nlets and RISSNET.
* **DEA New Jersey Field Office:** DEA NDPIX notification via DOJ Network routed from the NVPS Message Hub via Nlets and RISSNET.

### Scenario Steps

1. A Junction City, Kansas police officer arrested a suspect for dealing methamphetamine. A check of local record databases and the Kansas State Intelligence System provides no matching information. The investigation however shows drug movement through the Kansas City International Airport, and contact is made with the airport interdiction team.
2. Agent A of the Kansas City Drug Enforcement Administration Interdiction Task Force was assigned to the case.
3. Agent A enters her contact information and the suspect's basic data into the National Drug Pointer Index (NDPIX). As an NVPS participant, the record entry automatically spawns an NVPS query to all NVPS participants
4. The record travels through encrypted tunnels from the DOJ network to the NVPS message hub over two proprietary intranets: RISSNET secure intranet and Nlets.
5. The NVPS message hub proxies the message and launches queries to all participating deconfliction systems.
6. The NVPS message hub receives pointer index information from another deconfliction system, indicating a matching case involving the suspect.
7. The NVPS message hub sends a message to the originating system indicating the match and how to contact the other investigating agency. The message shows up as notifications on the originating system.
8. Simultaneously, another NVPS message is generated and sent to Agent B at the DEA New Jersey Field Division (Targeted deconfliction system) alerting him of the Kansas City inquiry.
9. Once notifications are reviewed, they are not stored on the NVPS message hub.
10. Coordinating between the Junction City Police Department, the Kansas City DEA Interdiction Task Force, and the New Jersey Field [Division resulted in the identification of additional members](http://www.statetechmagazine.com/article/2007/09/pointing-the-way) of the drug trafficking organization and subsequent arrests.

### Project Interoperability Concepts Used

Operational Capabilities

For this use case, the Operation Capabilities statement is: "_The NVPS operational capabilities enable law enforcement officers to engage in target deconfliction with officers across the country."_

Please see the section on Operational Capabilities for more information.

### Technical Capabilities

Technical capabilities used in this NVPS scenario include:

- Discovery
- Messaging
- Collaboration
- Storage
- Note: All applications and systems accessed in the scenario utilized the following capabilities:
- Security
- Auditing
- Mediation
- Enterprise Service Management
- See Technical Capabilities for more information

### Technical Standards

Technical standards used in this NVPS scenario include:

- NVPS message: Built to GJXDM 3.0.3.
- NLETS message: Built to GJXDM-compliant format.
- NDPIX message: Built as text-based parsed format.
- See technical standards for more information.

### Exchange Patterns

- The following exchange patterns identify the basic types of message exchanges within the NVPS use case scenario, and reflect what content should be included in the ISE common profile description for the exchange patterns.

A. The originating system creates a target record for deconfliction which is routed to the NVPS message hub.

![](Exchange%20Patterns%20Use%20Case_files/image001.png)

B. The NVPS message hub routes the target record for **Query** to the interfaces of connected target deconfliction systems.

C. Target deconfliction system B **responds** to the NVPS message hub's query with pointer index information of a matching case.

![](Exchange%20Patterns%20Use%20Case_files/image002.png)

D. The NVPS message hub routes the **response**, which includes the point of contact information for the matching case, to the originating system.

![](Exchange%20Patterns%20Use%20Case_files/image003.png)

E. The NVPS message hub also routes the **response** to the matching entity.

![](Exchange%20Patterns%20Use%20Case_files/image004.png)

F. The originating system and matching system receives a notification **Alert** and displays it as a message.

![](Exchange%20Patterns%20Use%20Case_files/image005.png)

G. The matching system receives a notification Alert and displays it as a message.

![](Exchange%20Patterns%20Use%20Case_files/image006.png)

H. The originating and matching case officers contact each other and share investigative details as appropriate.

![](Exchange%20Patterns%20Use%20Case_files/image007.png)

### Exchange Profiles

For each topic identified below, the question posed describes what content to provide for the related exchange profile sub-section.

* **Process: What business process allowed this scenario to occur? ** Participants agreed to required and optional data elements, exchange methodology, and use of message hub as broker.

* **Data: What is exchanged? ** Basic officer, agency, and target information. There are required and optional data elements. The optional data elements are just other identifying data about the target.

* **Services: How is information shared (e.g., XML, Web Service-based system)? ** XML based web service using GJXDM3, Nlets XML, and NDPIX text format.

* **Policy: What are the terms and conditions that allow this scenario to occur? ** NVPS Policy and Technical requirements established by the NVPS Coordinating Committee (NVPS CC) and the NVPS Technical Working Group (NVPS TWG).

* **Exchange Specifications ** These are the rules for exchange of information used in the NVPS. These requirements are developed by the participants and users of the systems and information.
