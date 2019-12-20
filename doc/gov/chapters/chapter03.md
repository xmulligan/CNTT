[<< Back](../)

# 3. Org Structure and Work Streams
<p align="right"><img src="../figures/bogo_ifo.png" alt="scope" title="Scope" width="35%"/></p>

## Table of Contents
* [3.1 Introduction](#3.1)
* [3.2 Org Structure](#3.2)
* [3.3 Work Streams](#3.3)
* [3.4 New Work Stream Policy](#3.4)

<a name="3.1"></a>
## 3.1 Introduction

<a name="3.2"></a>
## 3.2 Org Structure

### Organizational Structure and Work Streams 
This section is dedicated to outlining the relationship between the participants in the Common NFVI Telecom Taskforce. The intended use is to create clarity of ownership and responsibility for the participants.  As background, the scope of all partner organizations are shown. Specific key interfaces and handoffs are indicated. Responsibilities are listed in the sections below in a RACI chart. 

#### Scope
To help guide the discussion of the structure and relationships the mission/charter of the associated organizations are shown:

* GSMA - The GSMA represents the interests of mobile operators worldwide, uniting more than 750 operators with over 350 companies in the broader mobile ecosystem, including handset and device makers, software companies, equipment providers and internet companies, as well as organisations in adjacent industry sectors.
* CNTT - The scope of the CNTT is to establish a Common NFVi Framework document consisting of a global NFVi reference model, reference architecture, and global Virtual Network Function (VNF) certification lifecycle.
* Linux Foundation Networking - The primary mission of the LF Networking Fund is to raise, budget and spend funds and coordinate support for open source and/or open specification projects involved with the movement or communication of data on a network (including, but not limited to, data plane, control plane, analytics, orchestration, and automation technologies for enterprise, cloud, and carrier networks


#### Workflow of CNTT Process
The basic workflow of the CNTT process focuses on gaining alignment by industry players to specify reference models and architectures for use in the telecom infrastructure. From those specifications, build reference implementations for acceptance testing within carrier data centers and networks. Accumulating knowledge and refinements through successive cycles of the workflow. Once sufficient acceptance testing is completed, verification tests are established to verify NVFIs are compliant with reference architecture specifications and badging process is administered for easy marketplace identification. 

While there are many other process steps the basic cycle of CNTT and LFN delivering reference implementations is shown in a diagram below (excerpt from "OVP Webinar" by Rabi Abdel created Oct 8,2019):

[Illustration of organizational structure](https://wiki.lfnetworking.org/download/attachments/25362975/slide17_OVP_Webinar.pdf?version=1&modificationDate=1576870503175&api=v2)

#### Deliverables By Organization
##### GSMA
Key deliverables from GSMA include:

* Long term owner of the reference models
* Maintain Github repos for specifications 


##### CNTT
Key deliverables from CNTT include:

* Specifications of the reference model and reference architecture
* Roadmap of future reference architecture revisions
* Member organization provide select access to labs for OPNFV development/test use as managed by the OPNFV/Pharos project.
* Developers to augment OPNFV teams as needed
* Requirements for reference implementation characteristics
* Delivery and update cadence
* Provide RI and RC specifications
* Marketing and promotional directions


##### LFN OPNFV
Key deliverables from OPNFV/OVP include:

* Open process of RI development/testing, governance, and coordination of OPNFV projects/resources
* Responses to the RM/RA specifications that include specific HW recommendations, manifest and playbook for creation of RI, etc.
* Technical leadership for RI creation and management
* CI toolchain for build/test of RI
* Badging management and acceptance/verification test tooling
* Provide documentation and project artifact archival for all RIs
* Access to HW labs for the CI/development/testing of RI


<a name="3.3"></a>
## 3.3 Work Streams

<a name="3.4"></a>
## 3.4 New Work Streams Policy
In order for CNTT to stay current with new trends in the industry and the introduction of new technologies and processes, there will be scenarios where a new WS for a new specification work is needed to be created within CNTT. Following is CNTT policy of creating a new WS:

- A new Work Stream **Proposal** has to be created and should contain the following information:
  - The nature of the Work Stream proposed (Architecture, Implementation, Certification, else).
  - Detailed scope of the proposed Work Stream.
  - The rationale behind the need for a new Work Stream instead of making it part of an existing Work Stream.
  - The relationship to other Work Streams.
  - The impact on other Work Streams.
  - The relationship to open-source communities and standard setting organisations (if any).
  - Proposed Roadmap.
  - List of committed contributors (at least five) and committed named Work stream Leads and Co-Leads.
  - Endorsement from at least 2 service providers and 2 vendors.
- New Work Stream proposals need to be approved by the Technical Steering Committee during their regular meetings.
- New Work Stream proposals need to be approved and signed off by Governance Steering Committee during their regular meetings.





