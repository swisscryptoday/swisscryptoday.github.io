---
layout: post
title:  "2 September 2024, University of St. Gallen"
title_extra: "[Swiss Crypto Day](/)"
feature_image: "/assets/swisscryptoday-white.jpg"
# category: "Active Event"
permalink: /2024/
date:   2024-06-10 10:00:00 +0100
---

<!-- ##### Place holder -->

We are excited to announce that the third Swiss Crypto Day will be held at the University of St. Gallen on Monday, September 2nd, 2024.

##### When: 
September 2nd, 2024, 9:00 - 17:10
 
##### Where:
SQUARE at the University of St. Gallen, Guisanstrasse 20, 9010 St. Gallen

<!-- {% include map.html id="1Ef6r_PHZlfq69foHlJxZIfdtJtlJTL8" title="SQUARE at the University of St. Gallen" %} -->

<!-- You are invited to submit a proposal for presentations on the following submission form.

[Call for Presentations/Nominations](https://forms.gle/4tu2idJWzqbUBCah8)

The deadline for submissions is **July 10th**.

Decisions will be communicated by **July 25th**. -->

##### Program:

|:-------------||-------------|
|  9:00-9:15   || **Opening Remarks** |
|  9:15-9:45   || [Nan Cheng (University of St. Gallen)](https://nancheng.me/) |
|              || **Communication Optimization in SS-FSS Hybrid 2PC** <details close>Calculating the distance between two non-normalized vectors X and Y using cos(X,Y), and comparing it to a predefined threshold τ, is crucial in privacy-sensitive applications such as biometric authentication, identification, machine learning algorithms (e.g., linear regression, k-nearest neighbors), and typo-tolerant password-based authentication. To enhance secure computation efficiency in this context, we propose a communication optimization method utilizing a novel building block, CondEval, conditionally (depends on a boolean secret sharing) evaluate a function secret sharing gate in one round. CondEval is designed to operate effectively in both semi-honest and malicious settings. By evaluating protocols derived from CondEval in the context of voice-based biometric authentication, the results demonstrated notable efficiency improvements over existing SOTAs. In this talk, I will give a step-by-step introduction to this technique and show its impact in practical application.</details> |
|  9:50-10:30  || [Chen Da-Liu Zhang (Uni Luzern)](https://sites.google.com/view/chendaliu/about-me?authuser=0) |
|              || **Asynchronous Multi-Party Computation with Linear Communication and Optimal Resilience**  <details close>Secure multi-party computation (MPC) allows a set of parties to jointly compute a function over their private inputs. The seminal works of Ben-Or, Canetti and Goldreich [STOC '93] and Ben-Or, Kelmer and Rabin [PODC '94] settled the feasibility of MPC over asynchronous networks. Despite the significant line of work devoted to improving the communication complexity, current protocols with information-theoretic security and optimal resilience communicate \Omega(n^4C) field elements for a circuit with C multiplication gates. In contrast, synchronous MPC protocols with O(nC) communication have long been known. In this work we provide the first asynchronous MPC protocol with optimal resilience and linear O(nC) communication. The protocol makes black-box use of an asynchronous complete secret-sharing (ACSS) protocol, where the cost per multiplication reduces to the cost of distributing a constant number of sharings via ACSS, improving a linear factor over the state of the art by Choudhury and Patra [IEEE Trans. Inf. Theory '17]. Instantiating the ACSS with the concurrent work by Ji, Li and Song [CRYPTO '24] achieving linear cost per sharing, the result follows.</details>  |
| 10:15-10:45  || break |
| 10:45-11:15  || [Anna-Lena Horlemann (University of St. Gallen)](http://user.math.uzh.ch/trautmann/Home.html) |
|              || **TBD** <details close></details>|
| 11:15-11:45  || Abhinaba Mazumder and Michael Schaller (UZH) |
|              || **Information Set Decoding for Convolutional Codes** <details close>We present generic decoding algorithms for McEliece type systems that use (non-tail-biting) convolutional codes and show how to use them to reduce the security of two proposed cryptosystems. We were able to successfully recover many of the errors used in the encryption in less than 10 hours.</details>|
| 11:45-12:15  || [Luca De Feo (IBM)](https://defeo.lu/) |
|              || **The Isogeny Toolbox** <details close></details>|
| 12:15-13:15  || Lunch |
| 13:15-13:45  || [Anwar Hithnawi (ETH Zürich)](https://pps-lab.com/people/anwarhithnawi/) |
|              || **Democratizing Privacy-Preserving Computation** <details close></details>|
| 13:45-14:15  || [Florian Tramer (ETH Zürich)](https://www.floriantramer.com/) |
|              || **Stealing a Generative AI's Secrets (responsibly)** <details close>Companies that develop generative AI tools such as ChatGPT keep most development and deployment details secret. We typically don't know what the underlying model looks like (or how big it is), what it was trained on, or what safety measures are applied. In this talk, I'll show how we reverse-engineered such secrets from various production systems, and draw some connections to cryptographic problems. I'll conclude with a discussion of responsible disclosure practices in today's AI world, and how we might improve them.</details> |
| 14:15-14:35  || break |
| 14:35-15:05  || Francesco Regazzoni (USI/SUPSI)|
|              || **TBD** <details close></details> |
| 15:05-15:35  || [Tommaso Giagliardoni (Kudelski security/Nagra)](https://gagliardoni.net/) 
|              || **2024 update on Shufflecake: plausible deniability is even sweeter** <details close>Shufflecake is an open-source data encryption tool that allows creation of hidden volumes on a storage device in such a way that it is very difficult, even under forensic inspection, to prove the existence of such volumes. This is useful for people whose freedom of expression is threatened by repressive authorities or dangerous criminal organizations, in particular: whistleblowers, investigative journalists, and activists for human rights in oppressive regimes. You can consider Shufflecake a "spiritual successor" of tools such as TrueCrypt and VeraCrypt, but vastly improved: it is fast, supports any filesystem of choice, and can concurrently manage multiple layers of nested decoy volumes, so to improve user experience and make deniability of the existence of these partitions really plausible. Shufflecake is the result of a multi-year research aimed at solving fundamental limitations of plausible deniability tools. It is under active development, and after the initial success (DEF CON Demo Labs, ACM CCS, and others) the community of contributors is growing, bringing new ideas and results to the table. In this talk we will present the history and limitations of other existing solutions, we will show how Shufflecake works and solves such limitations, and we will highlight recent improvements, both theoretical and practical. In particular, we will announce the release of the "Lite" version of Shufflecake, and we will present the official roadmap and plans for the release of the first Shufflecake-powered fully hidden OS.</details> |
| 15:35-15:55  || break |
| 15:55-16:25  || [Giacomo Fenzi (EPFL)](https://gfenzi.io/) 
|              || **STIR: Reed–Solomon Proximity Testing with Fewer Queries** <details close>We present STIR (Shift To Improve Rate), an interactive oracle proof of proximity (IOPP) for Reed–Solomon codes that achieves the best known query complexity of any concretely efficient IOPP for this problem. For λ bits of security, STIR has query complexity O(log d+λ· loglog d), while FRI, a popular protocol, has query complexity O(λ·log d) (including variants of FRI based on conjectured security assumptions). STIR relies on a new technique for recursively improving the rate of the tested Reed–Solomon code. We provide an implementation of STIR compiled to a SNARK. Compared to a highly optimized implementation of FRI, STIR achieves an improvement in argument size that ranges from 1.25× to 2.46× depending on the chosen parameters, with similar prover and verifier running times. For example, in order to achieve 128 bits of security for degree 226 and rate 1/4, STIR has argument size 114 KiB, compared to 211 KiB for FRI.</details> |
| 16:25-16:55  || [Ziyi Guan (EPFL)](https://ziyiguan.github.io/) 
|              || **Security Bounds for Proof-Carrying Data from Straightline Extractors** <details close>Proof-carrying data (PCD) is a widely used cryptographic primitive that can be obtained by recursively-composing SNARKs or related primitives. However, these constructions do not come with security analyses that yield useful concrete security bounds. In this work we show that the PCD obtained from SNARKs with straightline knowledge soundness has essentially the same security as the underlying SNARK. In this setting, recursive composition incurs no security loss. As a notable application, our work offers an idealized model that provides useful, albeit heuristic, guidance for setting the security parameters of recursive STARKs currently used in blockchain systems. Based on https://eprint.iacr.org/2023/1646.pdf, joint work with Alessandro Chiesa, Shahar Samocha, and Eylon Yogev. </details> |
| 16:55-17:10  || **Closing Remarks** |
||||

##### Registration:

Please be advised that registration for this event is limited (i.e. limited seating and food). <b>Registration closes on August 25th. If your plans change and you are no longer able to attend, we ask that you email us at `swisscryptoday24@gmail.com` by August 31th</b> so that we can offer your registration to someone on the waitlist. We look forward to seeing you all there!

[Registration Link](https://forms.gle/iiNT9zUUwfecXcpY9)

Once you have registered, we will confirm your participation or spot on the waitlist by email.

##### Mailing list:
To subscribe to the mailing list, please visit [list.inf.unibe.ch](https://list.inf.unibe.ch/postorius/lists/swisscryptoday.list.inf.unibe.ch/) or send an empty email to: `swisscryptoday-join@list.inf.unibe.ch`.
