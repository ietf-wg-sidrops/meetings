# IETF 125 SIDROps Agenda

### Chairs:  
- Russ Housley ( housley AT vigilsec.com )
- Luigi Iannone ( ggx AT gigix.net )

SECRETARY: Krishnaswamy Ananthamurthy (kriswamy AT cisco.com)

---


### Thursday Session III, March 19, 2026 - 120 Minutes

- **14:00 - 16:00 Shenzhen (CST)**
    - 23:00 -> 01:00 PDT (San Francisco **Note: Starts March 18**)
    - 02:00 -> 04:00 EDT (New York)
    - 06:00 -> 08:00 UTC 
    - 07:00 -> 09:00 CET (Paris)
    - 17:00 -> 19:00 AEDT (Sydney)

***Room: [Shangri-la Ballroom 2](https://datatracker.ietf.org/meeting/125/floor-plan?room=shangri-la-ballroom-2)***

--- 
###  AGENDA

#### 0. Administration
-  Speakers: Russ/Luigi/Krishna
    - Agenda Bashing
    - Status reports for WG drafts
        - 5 Minutes (Cumulative Time: 5 Minutes)
<br><br>


#### 1. The RPKISPOOL format data materialization as used in RPKIViews
- Speaker: Job Snijders
    - Duration: 20 minutes including Q&A
    - Abstract: Share information on how RPKIViews uses Tar, Zstd, and CCR for continuous raw data captures of the global RPKI
    - Datatracker links: https://datatracker.ietf.org/doc/draft-ietf-sidrops-rpki-ccr/ and https://datatracker.ietf.org/doc/draft-snijders-rpkispool-format/
        - 20 Minutes (Cumulative Time: 25 Minutes)

#### 2. A Profile for Mapping Origin Authorizations (MOAs)
- Speaker: Chongfeng Xie
    - Desired Duration: 10 minutes including Q&A
    - Datatracker Link: https://datatracker.ietf.org/doc/draft-ietf-sidrops-moa-profile/
        - 10 Minutes (Cumulative Time: 35 Minutes)

#### 3. Update on the Erik Synchronization Protocol
- Speaker: Job Snijders
    - Duration: 15 minutes including Q&A
    - Abstract: Share progress update on what changed in Erik Synchronization specification since last meeting
    - Datatracker: https://datatracker.ietf.org/doc/draft-ietf-sidrops-rpki-erik-protocol/
        - 15 Minutes (Cumulative Time: 50 Minutes)

#### 4. YANG Data Model for RPKI to Router Protocol
- Speaker: Jishnu Roy
    - Duration: 10 minutes including Q&A
    - Abstract: This document defines YANG data models for configuring and managing Resource Public Key Infrastructure (RPKI) to Router Protocol
    - Datatracker Link: https://datatracker.ietf.org/doc/draft-ietf-sidrops-rtr-yang/03/
        - 10 Minutes (Cumulative Time: 60 Minutes)


#### 5. RPKI Repository Delta Protocol (RRDP) Delta File Retention Policy
- Speaker: Libin Liu  
    - Duration: 10 minutes including Q&A  
    - Datatracker Link: https://datatracker.ietf.org/doc/draft-liu-sidrops-rrdp-delta-retention-policy/ 
        - 10 Minutes (Cumulative Time: 70 Minutes)

#### 6. TLS Authentication for BGP
- Speaker: Jeffrey Haas, Bob Beck
    - Desired Duration: 10 minutes including Q&A
    - Abstract: A PKI for BGP TLS authentication.
    - Datatracker Link: https://datatracker.ietf.org/doc/draft-hbq-bgp-tls-auth/
       - 10 Minutes (Cumulative Time: 80 Minutes)

#### 7. ASPA-based AS_PATH Verification for BGP Export
- Speaker: Jia Zhang
    - Desired Duration: 10 minutes including Q&A
    - Datatracker Link: https://datatracker.ietf.org/doc/draft-zhang-sidrops-aspa-egress/
        - 10 Minutes (Cumulative Time: 90 Minutes)

#### 8. RPKI-based Validation with Prioritized Resource Data
- Speaker: Jia Zhang / Chongfeng Xie
    - Desired Duration: 15 minutes including Q&A
    - Datatracker Link: https://datatracker.ietf.org/doc/draft-zhang-sidrops-prioritized-route-validation/
        - 15 Minutes (Cumulative Time: 105 Minutes)

#### 9. Update to SOA based SAV
- Speaker: Minglin Jia
    - Desired Duration: 15 minutes including Q&A
    - Abstract: Report revisions to the SOA profile and usage documents in response to prior feedback, with deployability improving efforts.
    - Datatracker Link:
        - https://datatracker.ietf.org/doc/draft-ren-sidrops-soa-profile/
        - https://datatracker.ietf.org/doc/draft-ren-sidrops-soa-usage/
        - 15 Minutes (Cumulative Time: 120 Minutes)


#### 120 Minutes (Cumulative Time: 120 Minutes)

---
---

### IF (BY ANY CHANCE) TIME ALLOWS

#### A.1. A Profile for ROV Deployment Transparency
- Speaker: Sitong Ling
    - Desired Duration: 10 minutes including Q&A
    - Datatracker Link: https://datatracker.ietf.org/doc/draft-ling-sidrops-rov-tag-profile/
    
#### A.2. RPKI-based BGP Origin Attestation
- Speaker: Mingqing Huang
    - Desired Duration: 15 minutes including Q&A
    - Datatracker Link: https://datatracker.ietf.org/doc/draft-huang-idr-bgp-origin-attestation/

#### A.3. Operational Monitoring of RPKI Repositories Health and Safety
- Speaker: Yonghong Fu
    - Desired Duration: 10 minutes including Q&A
    - Datatracker Link: https://datatracker.ietf.org/doc/draft-fu-sidrops-rpki-repositories-monitoring/

#### A.4. RPKI to Router Protocol over QUIC
- Speaker: Jishnu Roy
    - Duration: 10 minutes including Q&A
    - Datatracker Link: https://datatracker.ietf.org/doc/draft-liu-sidrops-rpki-rtr-over-quic/

#### A.5. Risk of Stealthy BGP Hijacking under Incomplete Adoption of Route Origin Validation (ROV)
- Speaker: Yi Xu
    - Desired Duration: 20 minutes including Q&A
    - Abstract: This document describes how incomplete adoption of ROV makes stealthy BGP hijacking less visible on the control plane while still capable of diverting traffic.
    - Datatracker Link: https://datatracker.ietf.org/doc/draft-li-sidrops-stealthy-hijacking/

#### A.6. Structural Vulnerabilities in ASRank under Adversarial Conditions
- Speaker: Yi Xu
    - Desired Duration: 15 minutes including Q&A
    - Abstract: This document analyzes the structural vulnerabilities of ASRank, the most widely used algorithm for inferring Autonomous System (AS) business relationships from BGP routing data.
    - Datatracker Link: https://datatracker.ietf.org/doc/draft-xu-sidrops-asrank-vulnerabilities/

### A.7 Selectively Synchronizing RPKI Data to Routers
- Speaker: Yu Fu
    - Desired Duration: 5 minutes including Q&A
    - Abstract: The RTR protocol synchronizes all verified RPKI data to routers. The documents propose to extend SLURM or the existing RTR protocol to support selective data synchronization, so that the router only receives the data it actually needs.
    - Datatracker Link:  https://datatracker.ietf.org/doc/draft-fu-sidrops-enhanced-slurm-filter/ and https://datatracker.ietf.org/doc/draft-geng-sidrops-rtr-selective-sync/
