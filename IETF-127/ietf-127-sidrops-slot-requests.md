# Requests for SIDROps agenda time @ IETF 127

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

#### Introduction to RPKI Doctors
- Speaker: Job Snijders
- Desired duration: 10 minutes
- Expected outcome: community feedback
- Abstract: Explain objective and approach of RPKI Doctors review team
- Datatracker link: [https://datatracker.ietf.org/group/rpkidoctors/about/](https://datatracker.ietf.org/group/rpkidoctors/about/)

#### Mixed Algorithm Certificate Chains in the RPKI
- Speaker: Job Snijders
- Desired duration: 15 minutes
- Expected outcome: community feedback / call for WG adoption
- Abstract: Discussion on the concept of using mixed signing algorithm certificate chains in the RPKI. Permitting a second (widely supported) signing algorithm in the RPKI allows for smaller signatures in the short term and gaining operational experience towards PQ transitions in the long term.   
- Datatracker link: To be posted

#### Source Pre-validation in RPKI ROV
- Speaker: Mingqing Huang
- Desired Duration: 10 minutes
- Expected outcome: community feedback
- Abstract: This document defines a BCP for source pre-validation: an originating AS checks its intended BGP announcement against its local RPKI cache before sending it to eBGP neighbors. The goal is to reduce the number of self-inflicted invalid routes, improve global routing stability, and encourage wider and more confident deployment of ROV drop policies across the Internet - including the long tail of stub and small regional ASes.
- Datatracker Link: [https://datatracker.ietf.org/doc/draft-huang-sidrops-source-pre-validation/](https://datatracker.ietf.org/doc/draft-huang-sidrops-source-pre-validation/)
#### BGP Signed Origin Delegation Attestation (SODA)
- Speaker: Shenglin(Forrest) Jiang
- Desired duration: 5 minutes
- Expected outcome: community feedback
- Abstract: Using SODA, a validator performing Route Origin Validation (ROV) can determine whether an ROV-Invalid result reflects an authorized delegation rather than a route hijack.
- Datatracker link: [https://datatracker.ietf.org/doc/draft-jiang-idr-bgp-soda/](https://datatracker.ietf.org/doc/draft-jiang-idr-bgp-soda/)

#### Push Mode Extension for the RPKI to Router Protocol
- Speaker: Liyan Gong
- Desired duration: 10 minutes (Friday Sesion)
- Expected outcome: community feedback
- Abstract: This document defines a push mode extension for RTR that allows RPs to proactively push RPKI data updates to routers, either periodically or event-driven.  
- Datatracker link: [[https://datatracker.ietf.org/doc/draft-gong-sidrops-rtr-push/](https://datatracker.ietf.org/doc/draft-gong-sidrops-rtr-push/)]

#### Considerations for Incremental Validation in RPKI Relying Parties
- Speaker: Yingying Su, Yirong Yu
- Desired Duration: 10 minutes (including Q&A)
- Expected outcome: community feedback
- Abstract: This document describes the operational problem and design space for incremental validation in RPKI Relying Parties (RPs), and discusses general correctness and security considerations for reusing previously computed validation state. The goal is to reduce redundant validation work after incremental repository synchronization. The correctness objective is to produce the same validated payload output as full validation for the same repository snapshot, trust anchor set, validation policy, validation time, and applicable RPKI validation rules. This document does not specify a particular algorithm or cache structure, change RPKI object formats, repository synchronization protocols, or validation semantics, or require RPs to implement incremental validation.
- Datatracker Link: https://datatracker.ietf.org/doc/draft-su-sidrops-rpki-rp-incremental-validation/

#### Post-Quantum Cryptography for the RPKI
- Speaker: Tomoki Yoshikawa
- Desired Duration: 10 minutes (including Q&A)
- Expected outcome: Community feedback / call for WG adoption
- Abstract: This draft investigates the use of post-quantum cryptography in the RPKI, covering experimental implementations, performance evaluations, and migration considerations. The presentation will summarize the updates in -03 and seek community feedback on the document's direction and WG adoption.
- Datatracker Link: https://datatracker.ietf.org/doc/draft-yoshikawa-sidrops-pqc-rpki/

#### RPKIViews project update
- Speaker: Job Snijders
- Desired duration: 10 minutes
- Expected outcome: community feedback
- Abstract: RPKIViews' open data archives play a vital role towards understanding the dynamics of the global RPKI. In this talk I'd like to share an update on the state of the project and announce a new (free) service for protocol designers, researchers, and other interested parties.


#### Information Asymmetry and Deployment Gaps in RPKI-based Route Origin Validation
- Speaker: Weiqiang Cheng
- Desired Duration: 10 minutes
- Expected outcome: community feedback
- Abstract:This draft analyzes RPKI/ROV deployment gaps and cross-plane information asymmetry, describes operational side effects, and frames the problem space for future work, without proposing new protocols.
- Datatracker Link: [https://datatracker.ietf.org/doc/draft-cheng-sidrops-rpki-rov-gap-analysis/](https://datatracker.ietf.org/doc/draft-cheng-sidrops-rpki-rov-gap-analysis/)


#### Route Origin Authorization via Protected Delegation of Internet Number Resources
- Speaker: Joseph Gersch
- Desired Duration: 10 minutes (including Q&A)
- Expected outcome: community feedback
- Abstract: RPKI provides cryptographic route-origin authorization, but its hierarchical authority model gives a superior authority no way to permanently divest itself of control over a delegated resource. This draft explores a different property: a holder may elect a protected delegation boundary beyond which superior authorities can no longer reclaim the resource, suppress the holder's effective origin authorizations, or create competing allocation or route-origin authority. It specifies a hierarchical IPv4/IPv6 resource registry that enforces this at state-transition time and derives conventional VRPs for ROV, with conflict and precedence rules for coexistence with RPKI-derived authority. Routers and the RPKI itself are unchanged. The mechanism can also cover resources RPKI does not protect today, including legacy space. Experimental -00; feedback sought on whether protected delegation is a useful property, on the RPKI coexistence/precedence semantics, and on the trust, recovery and finality tradeoffs.
- Datatracker Link: [https://datatracker.ietf.org/doc/draft-gersch-sidrops-sovereign-roots/](https://datatracker.ietf.org/doc/draft-gersch-sidrops-sovereign-roots/)

#### Export of BGP Prefix Origin Validation in IP Flow Information Export (IPFIX)
- Speaker: Xueyan Song
- Desired Duration: 5 minutes (Friday session)
- Expected outcome: community feedback
- Abstract:The draft defines an IPFIX Information Element to export the RPKI-based BGP Prefix Origin Validation state (valid/invalid/not-found) for the active Loc-RIB route. It gives operators standardized visibility into ROV outcomes alongside flow monitoring, helping detect hijacks/misconfigurations and bridging SIDR operations with existing IPFIX tooling. 
- Datatracker Link: [https://datatracker.ietf.org/doc/draft-liu-sidrops-ipfix-bgp-pov/](https://datatracker.ietf.org/doc/draft-liu-sidrops-ipfix-bgp-pov/)
   
#### IPv6 Mapping Prefix PDU for the RPKI-Router Protocol
- Speaker: Guozhen Dong
- Desired Duration: 10 minutes
- Expected outcome: call for WG adoption
- Abstract:The draft defines a new Protocol Data Unit (PDU) type for the RPKI to Router Protocol to convey Mapping Origin Authorization (MOA) information from RPKI caches to routers.
- Datatracker Link: https://datatracker.ietf.org/doc/draft-dong-sidrops-rpki-rtr-moa-pdu/
  
