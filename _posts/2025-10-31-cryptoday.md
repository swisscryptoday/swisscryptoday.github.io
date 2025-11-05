---
layout: post
title:  "31 October 2025, École Polytechnique Fédérale de Lausanne"
title_extra: "[Swiss Crypto Day](/)"
feature_image: "/assets/swisscryptoday-white.jpg"
# category: "Active Event"
permalink: /2025-10/
date:   2025-07-07 10:00:00 +0100
---

<!-- ##### Place holder -->

![Smiling Pumpkin](../assets/2025/pumpkin.svg){: style="height: 25vh; float: left;"}

We are excited to announce that the fifth Swiss Crypto Day, Halloween Edition, 
will be held at the [École Polytechnique Fédérale de Lausanne](https://www.epfl.ch)
on Friday, October 31st, 2025, 10am to 4pm.

<!-- Next year's Swiss Crypto Day will be organized at [USI](https://www.usi.ch/en). --> 

<!-- ##### When -->
<!-- September 2nd, 2024, 9:00 - 17:10 -->
 
<!-- ##### Where -->
<!-- SQUARE at the University of St. Gallen, Guisanstrasse 20, 9010 St. Gallen -->


### Program

|:-------------||-------------|
| 10:30AM ||Tako Boris Fouotsa (EPFL)|
|||[**PRISMO: A Quaternion Signature for Isogeny Group Actions**](/assets/2025/epfl/01%20-%20Boris%20-%20Swiss%20Crypto%20Day.pdf)|
|||<details close>"Isogeny group action based signatures are obtained from a sigma protocol with high soundness error, say 1/2 for its most basic variant. One needs to independently repeat the sigma protocol several times to reduce the soundness error to negligible. These repetitions come with a considerable efficiency and size overhead. On the other hand, quaternion isogeny-based signatures such as PRISM are directly obtained from a sigma protocol with a negligible soundness error. The secret key in PRISM is a random supersingular isogeny, and PRISM is insecure when the secret  isogeny arises from the supersingular isogeny group action setting. In this talk, we present PRISMO, a variant of PRISM  suited for secret isogenies that arise from the supersingular isogeny group action setting. PRISMO uses a sigma protocol whose soundness error is negligible without requiring parallel repetitions. PRISMO, when compared to existing group action signatures such as CSI-FiSh (with the same public key size),  is about 3x faster for key generation, 273x faster for signing and 4900x faster for verification,  while also being  29x more compact (signature size).</close>|
| 11:00AM || Bryan Ford (EPFL) | 
|||[**Usable coercion-resistant e-voting in Votegral**](/assets/2025/epfl/02%20-%20Bryan%20-%20Votegral.pdf)|
|||<details close>"Online voting is convenient and flexible, but amplifies the risks of voter coercion and vote buying. Votegral’s registration component, TRIP, gives voters a kiosk in a privacy booth with which to print real and fake credentials on paper, eliminating dependence on trusted hardware in credential issuance. The voter learns and can verify in the privacy booth which credential is real, but real and fake credentials thereafter appear indistinguishable to others. Only voters actually under coercion, a hopefully-rare case, need to trust the kiosk. To achieve verifiability, each paper credential encodes an interactive zero-knowledge proof, which is sound in real credentials but unsound in fake credentials. Voters observe the difference in the order of printing steps, but need not understand the technical details. Experimental results with our prototype suggest that Votegral is practical and sufficiently scalable for real-world elections. User-visible latency of credential issuance in TRIP is at most 19.7 seconds even on resource-constrained kiosk hardware, making it suitable for registration at remote locations or on battery power. A companion usability study indicates that TRIP’s usability is competitive with other E-voting systems including some lacking coercion resistance, and formal proofs support TRIP’s combination of coercion-resistance and verifiability. </details>|
| 11:30AM || Cecilia Boschini (ETHZ) |
||| [**Security Amplification of Threshold Signatures in the Standard Model**](/assets/2025/epfl/03%20-%20Cecilia%20Boschini%20-%20Advanced%20KEM%20Concepts.pdf) |
||| <details close>The current standardization calls for threshold signatures have highlighted the need for appropriate security notions providing security guarantees strong enough for broad application. In this talk we will focus in particular on strong unforgeability. After an overview of how such a property can be defined, we show how to extend an existing construction for single-user signatures from chameleon hash functions to the threshold setting. Towards this goal, we introduce a game-based definition for threshold chameleon hash functions (TCHF) and provide a construction of TCHF that is secure under DDH in the standard model.</details> |
| 12:00PM || Lunch |
| 01:30PM || Giulio Malavolta (Bocconi University) |
||| [**How to Verify that a Small Device is Quantum, Unconditionally**](/assets/2025/epfl/04%20-%20Giulio%20Malavolta%20-%20Is%20it%20quantum.pdf) |
||| <details closed>A proof of quantumness (PoQ) allows a classical verifier to efficiently test if a quantum machine is performing a computation that is infeasible for any classical machine. We propose a new approach for constructing PoQ protocols where soundness holds unconditionally assuming a bound on the memory of the prover, but otherwise no restrictions on its runtime. Our protocols are heavily inspired by techniques developed in the context of cryptographic protocols, and they can be interpreted as a new exponential separation between classical and quantum computing. Based on a joint work with Tamer Mour.</details> |
| 02:00PM || Antonio Sanso (Ethereum Foundation) |
||| [**Breaking Poseidon with Graeffe: Root-Finding for Fun (and No Profit)**](/assets/2025/epfl/05%20-%20Antonio%20Sanso%20-%20Poseidon.pdf) |
||| <details close>This talk explores how the Graeffe root-finding method can be used to break reduced-round instances of the Poseidon and Poseidon2 permutations over NTT-friendly prime fields. We present an algorithm that efficiently isolates single roots of the high-degree polynomials arising from these constructions, leveraging the classical Graeffe transform. Applied to bounty challenges proposed by the Ethereum Foundation, our approach demonstrates practical preimage recovery across multiple security levels. These results shed new light on the algebraic structure of Poseidon-style designs and highlight subtle risks in permutation-based cryptographic primitives.</details> |
| 02:15PM || Ziyi Guan (EPFL) |
||| [**Relativized Succinct Arguments in the ROM Do Not Exist**](/assets/2025/epfl/06%20-%20Ziyi%20Guan%20-%20RSA%20in%20the%20ROM.pdf) |
||| <details close>"A relativized succinct argument in the random oracle model (ROM) is a succinct argument in the ROM that can prove/verify the correctness of computations that involve queries to the random oracle. We prove that relativized succinct arguments in the ROM do not exist. Relativized SNARGs are a powerful primitive that, e.g., can be used to obtain constructions of IVC (incrementally-verifiable computation) and PCD (proof-carrying data) based on falsifiable cryptographic assumptions. Our results rule out this approach for IVC and PCD in the ROM. Based on [joint work with Annalisa Barbara and Alessandro Chiesa](https://eprint.iacr.org/2024/728), accepted to TCC2025.</details> |
| 02:30PM || Michael Vergoz (MySwissKeeper) |
||| [**Post-Quantum Hybridization: Designing Resilient Cryptographic Transitions**](/assets/2025/epfl/07%20-%20Michael%20Vergoz%20-%20PQC.pdf) |
||| <details closed> The transition to post-quantum cryptography (PQC) presents a dual challenge: classical algorithms (RSA, ECC) are vulnerable to future quantum attacks, yet PQC algorithms remain young, complex, and occasionally brittle, some already broken using classical methods (e.g., SIKE in 2022). In this uncertain landscape, cryptographic hybridization has emerged as a strategic and technically viable solution, endorsed by NIST as a transitional practice. This talk explores how combining classical and post-quantum algorithms can build redundancy and mitigate the risk of catastrophic failures. We will discuss both signature and encryption hybridization schemes, highlighting the simplicity of signature concatenation (e.g., ECDSA + Dilithium) versus the intricate key fusion processes in encryption (e.g., ECDH + Kyber with HKDF). We will present real-world implications, including the complexity of managing hybrid X.509 chains, OCSPs, and PKI structures.Finally, we introduce Hyperproof, a modular hybrid cryptographic framework integrating PQC within wallets, HSMs, and PKI stacks—designed to address the interoperability, performance, and verification challenges of the hybrid era. This session is ideal for security architects, implementers, and researchers focused on resilient cryptographic infrastructures in the face of quantum uncertainty.</details> |
| 02:45PM || Giacomo Fenzi (EPFL) |
||| [**Linear-Time Accumulation Schemes**](/assets/2025/epfl/08%20-%20Fenzi%20Giacomo%20-%20Warp.pdf) |
||| <details closed>Proof-carrying data (PCD) is a powerful cryptographic primitive for computational integrity in a distributed setting. State-of-the-art constructions of PCD are based on accumulation schemes (and, closely related, folding schemes). We present WARP: the first accumulation scheme with linear prover time and logarithmic verifier complexity. Our scheme is hash-based (secure in the random oracle model), plausibly post-quantum secure, and supports unbounded accumulation depth. We achieve our result by constructing an interactive oracle reduction of proximity that works with any linear code over a sufficiently large field. Along the way, we introduce a new notion of straight line round-by-round knowledge soundness that is compatible with linear error correcting codes without efficient (error-tolerant) decoding algorithms. Based on https://eprint.iacr.org/2025/753.pdf</details>|
| 03:00PM || Coffee |
| 03:30PM || Felix Günther (IBM) |
||| [**Advanced KEM Concepts: (Hybrid) Obfuscation and Verifiable Decapsulation**](/assets/2025/epfl/09%20-%20Felix%20G++nther%20-%20Advanced%20KEM%20Compositions.pdf) |
||| <details close>Key encapsulation mechanisms (KEMs) enable shared secrets over public networks and underpin quantum-safe systems. Yet standardized schemes such as ML-KEM do not always fit protocol requirements, and secure implementations can be brittle. This talk presents two techniques to close that gap. 1) (Hybrid) Obfuscation. Some deployments require KEM public keys or ciphertexts to be indistinguishable from random bytes (e.g., Tor's obfs4 or PAKEs such as EKE). We introduce Kemeleon: encodings that map ML-KEM public keys and ciphertexts to random-looking strings, by now adopted as CFRG Internet-Draft. We also show how to combine classical and post-quantum obfuscated KEMs: unlike hybrid key exchange, hybrid obfuscation is subtle, and we give a nested construction with provable security from deployed schemes. 2) Verifiable Decapsulation. Missing verification steps can silently break security, as seen in Apple's ""goto fail"" bug. FO-based KEMs rely on a re-encryption check that implementations may omit; this occurred in HQC (and downstream liboqs), remaining unnoticed for 19 months. We propose making the check verifiable by folding an unpredictable confirmation code from encryption into key derivation, ensuring re-encryption is indeed performed. Applied to ML-KEM and HQC, this adds minimal overhead and catches the HQC bug in basic tests.</details>|
| 04:00PM || Francesca Falzon (ETHZ) |
||| [**Learning from Functionality Outputs: Private Join and Compute in the Real World**](/assets/2025/epfl/10%20-%20Franzesca%20Falzon%20-%20PJC.pdf) |
||| <details closed>Private Join and Compute (PJC) is a two-party protocol recently proposed by Google for various use-cases, including ad conversion (Asiacrypt 2021) and which generalizes their deployed private set intersection sum (PSI-SUM) protocol (EuroS&P 2020). PJC allows two parties, each holding a key-value database, to privately evaluate the inner product of the values whose keys lie in the intersection. While the functionality output is not typically considered in the security model of the MPC literature, it may pose real-world privacy risks, thus raising concerns about the potential deployment of protocols like PJC. In this work, we analyze the risks associated with the PJC functionality output. We consider an adversary that is a participating party of PJC and describe four practical attacks that break the other party's input privacy, and which are able to recover both membership of keys in the intersection and their associated values. Our attacks consider the privacy threats associated with deployment and highlight the need to include the functionality output as part of the MPC security model.</details> |

### Mailing list

To subscribe to the mailing list, please visit [list.inf.unibe.ch](https://list.inf.unibe.ch/postorius/lists/swisscryptoday.list.inf.unibe.ch/) or send an empty email to: `swisscryptoday-join@list.inf.unibe.ch`.
