# Requests for SIDROps agenda time @ IETF 126

## How to make a slot request:

Create a Pull Request appending, at the end of this very file, the request using the format:

---
#### Title Here
- Speaker: Your Name
- Desired Duration: in minutes (including Q&A)
- Expected outcome: The main objective of the presentation, e.g. community feedback, adoption, WGLC, etc.
- Abstract: abstract of the document. 
- Datatracker Link:  link to related document(s) in the Datatracker 
---

### Current Pending Requests

#### Update on Erik Synchronisation
- Speaker: Job Snijders
- Desired duration: 15 minutes
- Expected outcome: community feedback
- Abstract: Erik Synchronization is a data replication system using Merkle trees, a content-addressable naming scheme, concurrency control using monotonically increasing sequence numbers, and HTTP transport. The protocol's design is intended to be efficient, fast, easy to implement, and robust in the face of partitions or faults in the network.
- Datatracker link: https://datatracker.ietf.org/doc/draft-ietf-sidrops-rpki-erik-protocol/

#### IPv6 Mapping Prefix PDU for the RPKI-Router Protocol
- Speaker: Guozhen Dong 
- Desired Duration: 10 minutes (including Q&A)
- Expected outcome: Community feedback 
- Datatracker Link: https://datatracker.ietf.org/doc/draft-dong-sidrops-rpki-rtr-moa-pdu/

#### A Profile for Source Prefix Authorizations (SPAs)
- Speaker: Kamiel Braet
- Desired Duration: 10 in minutes (including Q&A)
- Expected outcome: Community feedback on the proposed RPKI SPA Profile of Source-Selective BGP usage
- Abstract: This draft defines the RPKI SPA profile that enables prefix holder to authorize source prefixes for source constraint routing usage.
- Datatracker Link:  https://datatracker.ietf.org/doc/draft-braet-sidrops-spa-profile/

#### ASPA Document Cluster Coordination
- Speaker: various, Job Snijders to lead discussion
- Desired duration: 15 minutes
- Expected outcome: help progress ASPA cluster towards WGLC
- Abstract: ASPA can be used for detection and mitigation of BGP route leaks. What todo items remain?
- Datatracker link: [draft-ietf-sidrops-aspa-profile](https://datatracker.ietf.org/doc/draft-ietf-sidrops-aspa-profile/]) + [draft-ietf-sidrops-aspa-verification](https://datatracker.ietf.org/doc/draft-ietf-sidrops-aspa-verification/) + [draft-ietf-sidrops-8210bis](https://datatracker.ietf.org/doc/draft-ietf-sidrops-8210bis/)

#### Source Address Validation Using SOAs
- Speaker: Minglin Jia
- Desired Duration: 10 minutes (including Q&A)
- Expected outcome: community feedback
- Abstract: This update simplifies SOA by publishing only AS-level service profiles in RPKI, using them to establish channels for further SAV information exchange, thereby reducing repository storage and update-latency impacts.
- Datatracker Link: 
  - https://datatracker.ietf.org/doc/draft-ren-sidrops-soa-profile/
  - https://datatracker.ietf.org/doc/draft-ren-sidrops-soa-usage/
  
#### Update on Autonomous System Relationship Authorization (ASRA) Drafts
- Speaker: K. Sriram
- Desired duration: 15 minutes
- Expected outcome: Community feedback on the proposed ASRA drafts  
- Abstract: ASRA fills in a significant gap in the ASPA method by adding the capability to detect fake links in the AS_PATHs in BGP Updates propagated from providers to customers. ASRA achieves this by allowing an AS to register additional AS relationships, i.e., customers and lateral peers. It is complementary to ASPA.
- Datatracker link: (1) draft-geng-sidrops-asra-profile: https://datatracker.ietf.org/doc/draft-geng-sidrops-asra-profile/ (2) draft-sriram-sidrops-asra-verification https://datatracker.ietf.org/doc/draft-sriram-sidrops-asra-verification/

#### RPKI Relying Party Benchmarking Methodology
- Speaker: Lancheng Qin
- Desired Duration: 10 minutes (including Q&A)
- Expected outcome: community feedback
- Abstract: This document defines a benchmarking methodology for evaluating RPKI Relying Party (RP) implementations in controlled laboratory environments. The methodology focuses on whether RP implementations correctly perform required validation steps and on the performance of these operations.
- Datatracker Link: 
  - https://datatracker.ietf.org/doc/draft-qin-bmwg-rpki-rp-bench/
  
#### Post-Quantum Cryptography for the RPKI
* Speaker: Tomoki Yoshikawa
* Desired Duration: 10 minutes (including Q&A)
* Expected outcome: Community feedback on the proposed scope, algorithm selection, and migration approach.
* Abstract: This draft discusses the use of post-quantum signature algorithms in the RPKI, with ML-DSA-65 as the primary candidate. The presentation will introduce the proposal, initial evaluation results, and open migration considerations.
* Datatracker Link: https://datatracker.ietf.org/doc/draft-yoshikawa-sidrops-pqc-rpki/


#### PAVA (PAth VAlidation): an alternative to ASPA
- Speaker: Maxence Fléchier
- Desired Duration: 10 minutes (including Q&A)
- Expected outcome: Community feedback on the proposed algorithm, focus of the work and limitations
- Abstract: This draft defines a new scheme for PATHSEC that makes use of the DNS to distribute information safely using a unique representation of AS relationships depending on the NLRI. It also describes a new verification algorithm.
- Datatracker Link:  https://datatracker.ietf.org/doc/draft-flechier-sidrops-pava/

#### Information Asymmetry and Deployment Gaps in RPKI-based Route Origin Validation
- Speaker: Weiqiang Cheng
- Desired Duration: 10 minutes (including Q&A)
- Expected outcome: community feedback
- Abstract:This draft analyzes RPKI/ROV deployment gaps and cross-plane information asymmetry, describes operational side effects, and frames the problem space for future work, without proposing new protocols.
- Datatracker Link: https://datatracker.ietf.org/doc/draft-cheng-sidrops-rpki-rov-gap-analysis/

#### Risk of Stealthy BGP Hijacking under Incomplete Adoption of Route Origin Validation (ROV)
- Speaker: Yi Xu
- Desired Duration: 10 minutes including Q&A
- Abstract: This document describes how incomplete adoption of ROV makes stealthy BGP hijacking less visible on the control plane while still capable of diverting traffic.
- Datatracker Link: https://datatracker.ietf.org/doc/draft-li-sidrops-stealthy-hijacking/

#### BGP Communities for Security Policy Intent
- Speaker: Yangfei Guo
- Desired Duration: 5 minutes (including Q&A)
- Expected outcome: community feedback
- Abstract: This draft defines BGP security Large Communities to convey ROV policies to downstream networks.
- Datatracker Link: https://datatracker.ietf.org/doc/draft-guo-idr-bgp-security-policy-community/

#### Requirements for Resource Public Key Infrastructure (RPKI) Relying Parties
- Speaker: Yingying Su
- Desired Duration: 10 minutes (including Q&A)
- Expected outcome: community feedback
- Abstract: This document provides a single reference point for requirements for RP software for use in RPKI. It cites requirements that appear in several RPKI RFCs and related specifications, making it easier for implementers to become aware of these requirements. This document updates RFC8897 to reflect changes to the requirements and guidance specified in the relevant RPKI standards.
- Datatracker Link: 
  - https://datatracker.ietf.org/doc/draft-su-sidrops-rpki-rp-requirements/

#### A Publication-Point-Based Incremental Validation Procedure for RPKI Relying Parties
- Speaker: Yingying Su
- Desired Duration: 10 minutes (including Q&A)
- Expected outcome: community feedback
- Abstract: This document describes a publication-point-based incremental validation procedure for RPKI RPs. The procedure is intended to reduce redundant validation work after incremental repository synchronization, while preserving the same validation result as a full top-down validation over the same repository snapshot, trust anchor set, validation policy, and validation time. This document does not change the syntax or validation semantics of any RPKI object.
- Datatracker Link: 
  - We will upload soon.
  
#### RPKI to router protocol over QUIC
- Speaker: Jishnu Roy
- Desired Duration: 10 minutes (including Q&A)
- Expected outcome: Community feedback on the proposal
- Abstract: The Resource Public Key Infrastructure (RPKI) to Router Protocol provides a simple but reliable mechanism to receive cryptographically validated RPKI prefix origin data and router keys from a trusted cache. QUIC provides practical and secure semantics for the RTR protocol, particularly fast connection establishment and multi-stream carrying, thereby reducing the time required to complete RTR data synchronization. 
- Datatracker Link:  https://datatracker.ietf.org/doc/draft-liu-sidrops-rpki-rtr-over-quic/03/

#### Source Pre-validation in RPKI ROV
- Speaker: Mingqing Huang
- Desired Duration: 10 minutes 
- Expected outcome: community feedback
- Abstract: This document defines a BCP for source pre-validation: an originating AS checks its intended BGP announcement against its local RPKI cache before sending it to eBGP neighbors. The goal is to reduce the number of self-inflicted invalid routes, improve global routing stability, and encourage wider and more confident deployment of ROV drop policies across the Internet - including the long tail of stub and small regional ASes.
- Datatracker Link:  https://datatracker.ietf.org/doc/draft-huang-sidrops-source-pre-validation/

#### RPKI-based Validation with Prioritized Resource Data
- Speaker: Jia Zhang / Nan Geng
- Desired Duration: 8 minutes (including Q&A)
- Expected outcome: Community feedback on the updated framework and guidance on next steps
- Abstract: This draft discusses how operators may use signed RPKI data together with supplemental or locally configured routing-security data in local validation and filtering workflows. It focuses on priority-safe handling, so that supplemental data can support local routing policy without changing or silently overriding authoritative RPKI semantics. The presentation will summarize the latest updates, clarify the deployment models and operational trade-offs, and ask the working group for feedback on terminology, document scope, and next steps.
- Datatracker Link: https://datatracker.ietf.org/doc/draft-zhang-sidrops-prioritized-route-validation/
