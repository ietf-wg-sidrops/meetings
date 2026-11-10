# IETF 126 SIDROps Agenda

### Chairs:  
- Russ Housley ( housley AT vigilsec.com )
- Luigi Iannone ( ggx AT gigix.net )

SECRETARY: Krishnaswamy Ananthamurthy (kriswamy AT cisco.com)

---

### Session I
- #### Tuesday Session I, November 17, 2026 - 90 Minutes 

    - [**09:00 - 10:30 San Francisco (PST)**](https://www.worldtimebuddy.com/?qm=1&lid=5391959,5128581,100,2988507,1816670,2147714&h=2988507&date=2026-11-17&sln=18-19.5&hf=0)
        - 12:00 -> 13:30 EST (New York)
        - 17:00 -> 18:30 UTC 
        - 18:00 -> 19:30 CET (Paris)
        - 01:00 -> 02:30 CST (Beijing - **This is November 18**)
        - 04:00 -> 05:30 AEDT (Sydney - **This is November 18**)

    - ***Room: [Golden Gate 4-5](https://datatracker.ietf.org/meeting/127/floor-plan?room=golden-gate-4-5)***


### Session II 
- #### Wednesday Session IV, November 18, 2026 - 60 Minutes

    - [**16:00 - 17:30 San Francisco (PST)**](https://www.worldtimebuddy.com/?qm=1&lid=5391959,5128581,100,2988507,1816670,2147714&h=2988507&date=2026-11-19&sln=1.5-2.5&hf=0)
        - 19:30 -> 20:30 EST (New York)
        - 00:30 -> 01:30 UTC (**This is November 21**)
        - 01:30 -> 02:30 CET (Paris  - **This is November 19**)
        - 08:30 -> 09:30 CST (Beijing - **This is November 19**)
        - 11:30 -> 12:30 AEDT (Sydney - **This is November 19**)

    - ***Room: [Golden Gate 7-8](https://datatracker.ietf.org/meeting/127/floor-plan?room=golden-gate-7-8)***

--- 
###  AGENDA SESSION I

#### 0. Administration
-  Speakers: Russ/Luigi/Krishna
    - Agenda Bashing
    - Status reports for WG drafts
        - 5 Minutes (Cumulative Time: *5 Minutes*)
<br><br>


###  AGENDA SESSION I (Tuesday)


#### 1. RPKI Terminology
- Speaker: Chairs 
    - Duration: 5 minutes (Cumulative Time: *10 Minutes*)
- Expected outcome: Check Adoption Consensus
- Abstract: The Resource Public Key Infrastructure (RPKI) is defined in dozens of different RFCs.  The terminology used by implementers and developers of RPKI protocols, and by operators of RPKI systems, can at times be inconsistent, leading to confusion.  In an effort to improve consistency in this respect, this document provides a single location for definitions of commonly-used RPKI terms.
- Datatracker link(s): 
    - [draft-yan-sidrops-rpki-terminology](https://datatracker.ietf.org/doc/draft-yan-sidrops-rpki-terminology/) 

#### 2. Introduction to RPKI Doctors
- Speaker: Job Snijders
    - Duration: 10 minutes (Cumulative Time: *20 Minutes*)
- Expected outcome: community feedback
- Abstract: Explain objective and approach of RPKI Doctors review team
- Datatracker link: 
    - [https://datatracker.ietf.org/group/rpkidoctors/about/](https://datatracker.ietf.org/group/rpkidoctors/about/)


#### 3. RPKIViews project update
- Speaker: Job Snijders
    - Duration: 10 minutes (Cumulative Time: *30 Minutes*)
- Expected outcome: community feedback
- Abstract: RPKIViews' open data archives play a vital role towards understanding the dynamics of the global RPKI. In this talk I'd like to share an update on the state of the project and announce a new (free) service for protocol designers, researchers, and other interested parties.


#### 4. Post-Quantum Cryptography for the RPKI
- Speaker: Tomoki Yoshikawa
    - Duration: 10 minutes (Cumulative Time: *40 Minutes*)
- Expected outcome: Community feedback / call for WG adoption
- Abstract: This draft investigates the use of post-quantum cryptography in the RPKI, covering experimental implementations, performance evaluations, and migration considerations. The presentation will summarize the updates in -03 and seek community feedback on the document's direction and WG adoption.
- Datatracker Link: 
    - [draft-yoshikawa-sidrops-pqc-rpki](https://datatracker.ietf.org/doc/draft-yoshikawa-sidrops-pqc-rpki/)
 

#### 5. Mixed Algorithm Certificate Chains in the RPKI
- Speaker: Job Snijders
    - Duration: 15 minutes (Cumulative Time: *55 Minutes*)
- Expected outcome: community feedback / call for WG adoption
- Abstract: Discussion on the concept of using mixed signing algorithm certificate chains in the RPKI. Permitting a second (widely supported) signing algorithm in the RPKI allows for smaller signatures in the short term and gaining operational experience towards PQ transitions in the long term. 


#### 6. BGP Signed Origin Delegation Attestation (SODA)
- Speaker: Shenglin(Forrest) Jiang
    - Duration: 10 minutes (Cumulative Time: *65 Minutes*)
- Expected outcome: community feedback
- Abstract: Using SODA, a validator performing Route Origin Validation (ROV) can determine whether an ROV-Invalid result reflects an authorized delegation rather than a route hijack.
- Datatracker link: [draft-jiang-idr-bgp-soda](https://datatracker.ietf.org/doc/draft-jiang-idr-bgp-soda/)


#### 7. Information Asymmetry and Deployment Gaps in RPKI-based Route Origin Validation
- Speaker: Weiqiang Cheng
    - Duration: 10 minutes (Cumulative Time: *75 Minutes*)
- Expected outcome: community feedback
- Abstract:This draft analyzes RPKI/ROV deployment gaps and cross-plane information asymmetry, describes operational side effects, and frames the problem space for future work, without proposing new protocols.
- Datatracker Link: 
    - [draft-cheng-sidrops-rpki-rov-gap-analysis](https://datatracker.ietf.org/doc/draft-cheng-sidrops-rpki-rov-gap-analysis/)


#### 8. Source Pre-validation in RPKI ROV
- Speaker: Mingqing Huang
    - Duration: 10 minutes (Cumulative Time: *85 Minutes*)
- Expected outcome: community feedback
- Abstract: This document defines a BCP for source pre-validation: an originating AS checks its intended BGP announcement against its local RPKI cache before sending it to eBGP neighbors. The goal is to reduce the number of self-inflicted invalid routes, improve global routing stability, and encourage wider and more confident deployment of ROV drop policies across the Internet - including the long tail of stub and small regional ASes.
- Datatracker Link: 
    - [draft-huang-sidrops-source-pre-validation/](https://datatracker.ietf.org/doc/draft-huang-sidrops-source-pre-validation/)

#### Buffer 5 Minutes (Cumulative Time: 90 Minutes)


###  AGENDA SESSION II (Wednesday)

#### 9. IPv6 Mapping Prefix PDU for the RPKI-Router Protocol
- Speaker: Guozhen Dong
    - Duration: 10 minutes (Cumulative Time: *100 Minutes*)
- Expected outcome: call for WG adoption
- Abstract:The draft defines a new Protocol Data Unit (PDU) type for the RPKI to Router Protocol to convey Mapping Origin Authorization (MOA) information from RPKI caches to routers.
- Datatracker Link: 
    - [draft-dong-sidrops-rpki-rtr-moa-pdu](https://datatracker.ietf.org/doc/draft-dong-sidrops-rpki-rtr-moa-pdu/)

#### 10. Considerations for Incremental Validation in RPKI Relying Parties
- Speaker: Yingying Su, Yirong Yu
    - Duration: 10 minutes (Cumulative Time: *110 Minutes*)
- Expected outcome: community feedback
- Abstract: This document describes the operational problem and design space for incremental validation in RPKI Relying Parties (RPs), and discusses general correctness and security considerations for reusing previously computed validation state. The goal is to reduce redundant validation work after incremental repository synchronization. The correctness objective is to produce the same validated payload output as full validation for the same repository snapshot, trust anchor set, validation policy, validation time, and applicable RPKI validation rules. This document does not specify a particular algorithm or cache structure, change RPKI object formats, repository synchronization protocols, or validation semantics, or require RPs to implement incremental validation.
- Datatracker Link: 
    - [draft-su-sidrops-rpki-rp-incremental-validation](https://datatracker.ietf.org/doc/draft-su-sidrops-rpki-rp-incremental-validation/)


#### 11. Push Mode Extension for the RPKI to Router Protocol
- Speaker: Liyan Gong
    - Duration: 10 minutes (Cumulative Time: *120 Minutes*)
- Expected outcome: community feedback
- Abstract: This document defines a push mode extension for RTR that allows RPs to proactively push RPKI data updates to routers, either periodically or event-driven.  
- Datatracker link: 
    - [draft-gong-sidrops-rtr-push](https://datatracker.ietf.org/doc/draft-gong-sidrops-rtr-push/)


#### 12. Route Origin Authorization via Protected Delegation of Internet Number Resources
- Speaker: Joseph Gersch
   - Duration: 10 minutes (Cumulative Time: *130 Minutes*)
- Expected outcome: community feedback
- Abstract: RPKI provides cryptographic route-origin authorization, but its hierarchical authority model gives a superior authority no way to permanently divest itself of control over a delegated resource. This draft explores a different property: a holder may elect a protected delegation boundary beyond which superior authorities can no longer reclaim the resource, suppress the holder's effective origin authorizations, or create competing allocation or route-origin authority. It specifies a hierarchical IPv4/IPv6 resource registry that enforces this at state-transition time and derives conventional VRPs for ROV, with conflict and precedence rules for coexistence with RPKI-derived authority. Routers and the RPKI itself are unchanged. The mechanism can also cover resources RPKI does not protect today, including legacy space. Experimental -00; feedback sought on whether protected delegation is a useful property, on the RPKI coexistence/precedence semantics, and on the trust, recovery and finality tradeoffs.
- Datatracker Link: 
    - [draft-gersch-sidrops-sovereign-roots](https://datatracker.ietf.org/doc/draft-gersch-sidrops-sovereign-roots/)

#### 13. Export of BGP Prefix Origin Validation in IP Flow Information Export (IPFIX)
- Speaker: Xueyan Song
   - Duration: 5 minutes (Cumulative Time: *135 Minutes*)
- Expected outcome: community feedback
- Abstract:The draft defines an IPFIX Information Element to export the RPKI-based BGP Prefix Origin Validation state (valid/invalid/not-found) for the active Loc-RIB route. It gives operators standardized visibility into ROV outcomes alongside flow monitoring, helping detect hijacks/misconfigurations and bridging SIDR operations with existing IPFIX tooling. 
- Datatracker Link: 
    - [draft-liu-sidrops-ipfix-bgp-pov](https://datatracker.ietf.org/doc/draft-liu-sidrops-ipfix-bgp-pov/)

#### Buffer 15 Minutes (Cumulative Time: 150 Minutes)
