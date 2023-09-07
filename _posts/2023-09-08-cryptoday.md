---
layout: post
title:  "8 September 2023, ETH Zurich"
title_extra: "[Swiss Crypto Day](/)"
feature_image: "/assets/swisscryptoday-white.jpg"
permalink: /2023/
date:   2023-06-23 18:00:00 +0100
---


### Announcement

After a 3 year long hiatus, we’re excited to announce that the second Swiss Crypto Day will be taking place at ETH Zürich on Friday 8 September 2023.

##### When: 
8 September 2023, 9:00 - 17:00
 
##### Where: 
CAB G 61, Universitätstrasse 6, 8006 Zürich

##### Program:

|:-------------||-------------|
|  9:00-9:10   || **Opening Remarks** |
|  9:10-9:50   || [Karen Klein (ETH Zürich)](https://foc.ethz.ch/people/karenklein.html) |
|              ||  **A New Rewinding Technique for Proving Adaptive Security** <details close>For many cryptographic primitives, it is relatively easy to achieve selective security (where the adversary commits a-priori to some of the choices to be made later in the attack) but has shown difficult to achieve the more natural notion of adaptive security (where the adversary can make all choices on-the-fly as the attack progresses). A prominent example is the construction of prefix-constrained pseudorandom functions by Goldreich, Goldwasser and Micali [GGM84]. In this talk we discuss the difficulty of proving adaptive security of the GGM construction and how we could finally solve the problem using a novel rewinding technique.This talk is based on joint work with Dennis Hofheinz and Julia Kastner.</details> |
|  9:50-10:30  || [Anu Unnikrishnan (ETH Zürich)](https://www.anu-unnikrishnan.com/) |
|              || **Probabilistic Data Structures in Adversarial Settings**  <details close>Probabilistic data structures (PDS) compactly represent data, at the cost of giving approximate answers to queries about the data. Examples include Bloom filters for membership queries, HyperLogLog for cardinality estimation, and Count-Min sketches for frequency estimation. PDS are commonplace in today's computing systems, finding use in applications such as database query speedup, detection of anomalies in network traffic, certificate revocation systems, and more. While PDS are designed to work reliably under benign inputs, nowadays they are often used in settings where adversaries can gain benefit from carefully selecting inputs. In this talk, I’ll discuss the security issues of deploying PDS in adversarial settings, and how to protect them.</details>  |
| 10:30-11:00  || Znünipause |
| 11:00-11:40  || [Julia Hesse (IBM Research - Zürich)](https://research.ibm.com/people/julia-hesse) |
|              || **Security Analysis of the WhatsApp End-to-End Encrypted Backup Protocol** <details close>WhatsApp is an end-to-end encrypted (E2EE) messaging service used by billions of people. In late 2021, WhatsApp rolled out a new protocol for backing up chat histories. The E2EE WhatsApp backup protocol (WBP) allows users to recover their chat history from passwords, leaving WhatsApp oblivious of the actual encryption keys. The WBP builds upon the OPAQUE framework for password-based key exchange, which is currently undergoing standardization. While considerable efforts have gone into the design and auditing of the WBP, the complexity of the protocol’s design and shortcomings in the existing security analyses of its building blocks make it hard to understand the actual security guarantees that the WBP provides. In this work, we provide the first formal security analysis of the WBP. Our analysis in the universal composability (UC) framework confirms that the WBP provides strong protection of users’ chat history and passwords. It also shows that a corrupted server can under certain conditions make more password guesses than what previous analysis suggests.</details>|
| 11:40-12:20  || [Daniel Collins (EPFL)](https://ic-people.epfl.ch/~dcollins/) |
|              || **Cryptographic Administration for Secure Group Messaging** <details close>Many real-world group messaging systems delegate group administration to the application level, failing to provide formal guarantees related to group membership. Taking a cryptographic approach to group administration can prevent both implementation and protocol design pitfalls that result in a loss of confidentiality and consistency for group members. In this work, we introduce a cryptographic framework for the design of group messaging protocols that offer strong security guarantees for group membership. To this end, we extend the continuous group key agreement (CGKA) paradigm used in the recently completed IETF MLS group messaging standardisation process and introduce the administrated CGKA (A-CGKA) primitive. Our primitive natively enables a subset of group members, the group admins, to control the addition and removal of parties and to update their own keying material in a secure manner. We embed A-CGKA with a novel correctness notion which provides guarantees for group evolution and consistency, and a security model that prevents even corrupted (non-admin) members from forging messages that add new users to a group. Moreover, we present two efficient and modular constructions of group administrators that are correct and secure with respect to our definitions. Finally, we propose, implement, and benchmark an efficient extension of MLS that integrates cryptographic administrators. Our constructions admit little overhead over running a CGKA and can be extended to support advanced admin functionalities.</details>|
| 12:30-13:30  || Lunch |
| 13:30-14:10  || [Ioana Nedelcu (Google)](linkedin.com/in/ioana-teodora-nedelcu-197360193) |
|              || **Tink - A Journey of Secure and User-Friendly Applied Cryptography at Google** <details close>The talk aims to explore the evolution of Tink, the open-source cryptography library developed by Google over the last few years, and highlight its significant impact on the field of applied cryptography, while focusing on its design goals, successes, challenges, and future directions. The presentation will emphasize Tink's role as a tool that empowers individuals without deep cryptographic expertise to incorporate strong secure practices seamlessly into their applications. Focusing on the importance of secure, easy-to-use, and difficult-to-misuse cryptographic tools, we will delve into Tink's robust features -such as keys, keysets and comprehensive support for key management, but we will also address some suboptimal decisions and challenges faced during its development. In the final, we will touch upon the future roadmap of Google's cryptographic library.</details>|
| 14:10-14:50  || [Paul Bottinelli (NCC Group)](https://www.linkedin.com/in/paulbottinelli/) |
|              || **Crypto Vulnerabilities in the Wild** <details close>In this talk, Paul will present a few selected cryptography vulnerabilities identified through security reviews conducted by the Cryptography Services team at NCC Group. The presentation will start with an exploration of security flaws found in blockchain deployments, including a biased ChaCha20-based Random Number Generator due to erroneous programming language translation and an issue related to a missing parameter in the Fiat-Shamir computation of a Verifiable Random Function (VRF) leading to the break of its uniqueness property. The speaker will also discuss an ECDSA signature forgery arising from a missing step in the verification process, frequently affecting even modern threshold ECDSA implementations, as well as a TLS authentication bypass leveraging a poor state-machine design. This presentation will highlight the range of issues discovered during cryptography reviews and hopefully help cryptographers and developers avoid such errors.</details> |
| 14:50-15:20  || Zvieripause |
| 15:20-16:00  || Tapas Pal (NTT Corporation Japan & Univ. of St. Gallen) and [Katerina Mitrokotsa (Univ. of St. Gallen)](https://www.unisg.ch/en/university/about-us/organisation/detail/person-id/2e889d58-6b54-431b-ae0e-3198ed46444a/)|
|              || **Inner Product Functional Encryption for the Real World** <details close>Functional encryption (FE) is an advanced cryptographic primitive that enables elegant access control over encrypted data. Predicate inner product functional encryption (P-IPFE) is essentially attribute-based IPFE (AB-IPFE) which additionally hides attributes associated to ciphertexts.  In P-IPFE, a message x is encrypted under an attribute w and a secret key is generated for a pair (y,v) such that recovery of <x,y> requires the vectors w,v to satisfy a linear relation. We call a P-IPFE unbounded if it can encrypt unbounded length attributes and message vectors, producing an input-specific ciphertext size. We construct the first unbounded zero and non-zero predicate IPFE (UZP-IPFE) which recovers <x,y> if <w,v> is zero and non-zero respectively from standard and well-established assumptions. Our proposed P-IPFE can be useful in many realistic settings e.g. for Hamming distance-based biometric authentication and cloud-assisted computing, while providing strong privacy guarantees.</details> |
| 16:00-16:40  || [Alessandro Chiesa (EPFL)](https://people.epfl.ch/alessandro.chiesa?lang=en) 
|              || **Subquadratic SNARGs in the Random Oracle Model** <details close>In a seminal work, Micali (FOCS 1994) gave the first succinct non-interactive argument (SNARG) in the random oracle model (ROM). The construction combines a PCP and a cryptographic commitment, and has several attractive features: it is plausibly post-quantum; it can be heuristically instantiated via lightweight cryptography; and it has a transparent (public-coin) parameter setup. However, it also has a significant drawback: a large argument size. In this talk I will describe a construction that achieves a smaller argument size. This is the first progress on the Micali construction since it was introduced over 25 years ago. This is joint work with Eylon Yogev.</details> |
| 16:40-16:50  || **Closing Remarks** |
| | | |


##### Registration: 

Please be advised that registration for this event is limited (i.e. limited seating and food). <b>Registration closes on August 25. If your plans change and you are no longer able to attend, we ask that you email us at `swisscryptoday23@gmail.com` by September 6</b> so that we can offer your registration to someone on the waitlist. We look forward to seeing you all there!

[Registration Link](https://forms.gle/jxq9RizniwxsyXR16)

Once you have registered, we will confirm your participation or spot on the waitlist by email.

##### Mailing list:

To subscribe to the mailing list, please visit [list.inf.unibe.ch](https://list.inf.unibe.ch/postorius/lists/swisscryptoday.list.inf.unibe.ch/) or send an empty email to: `swisscryptoday-join@list.inf.unibe.ch`.
