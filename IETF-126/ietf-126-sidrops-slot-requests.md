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

#### Post-Quantum Cryptography for the RPKI
* Speaker: Tomoki Yoshikawa
* Desired Duration: 10 minutes (including Q&A)
* Expected outcome: Community feedback on the proposed scope, algorithm selection, and migration approach.
* Abstract: This draft discusses the use of post-quantum signature algorithms in the RPKI, with ML-DSA-65 as the primary candidate. The presentation will introduce the proposal, initial evaluation results, and open migration considerations.
* Datatracker Link: https://datatracker.ietf.org/doc/draft-yoshikawa-sidrops-pqc-rpki/


