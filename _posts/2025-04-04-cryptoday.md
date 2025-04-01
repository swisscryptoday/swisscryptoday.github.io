---
layout: post
title:  "4 April 2025, Università della Svizzera italiana"
title_extra: "[Swiss Crypto Day](/)"
feature_image: "/assets/swisscryptoday-white.jpg"
# category: "Active Event"
permalink: /2025/
date:   2025-04-04 10:00:00 +0100
---

<!-- ##### Place holder -->

<!-- We are excited to announce that the third Swiss Crypto Day will be held at the Università della Svizzera italiana on Friday, April 4th, 2025. -->



<p></p>

<!-- Next year's Swiss Crypto Day will be organized at [USI](https://www.usi.ch/en). --> 

<!-- ##### When -->
<!-- September 2nd, 2024, 9:00 - 17:10 -->
 
<!-- ##### Where -->
<!-- SQUARE at the University of St. Gallen, Guisanstrasse 20, 9010 St. Gallen -->


##### Program



|:-------------||-------------|
|  10:00-10:30 || **Registrations & Welcome Coffee** |
|  10:30-10:35 || **Opening Remarks** |
|  10:35-12:05 || **Session 1** |
|  10:35-11:05 || Guillaume Endignoux (Google)  |
|              || **Post Quantum Cryptography in Tink** <details close>Tink is a multi-language, cross-platform, open source library that provides secure and easy-to-use cryptographic APIs, created and maintained by cryptographers and security engineers at Google (https://developers.google.com/tink). In this talk, we will discuss how we are approaching the transition to post-quantum cryptography in Tink. In particular, we'll see how the baked-in key rotation architecture enables smooth rotation towards other algorithms. We'll also discuss where new challenges arise and how we're tackling them. For example, how to model the concept of a Key Encapsulation Mechanism (KEM), and how to best expose it as an API that follows our easy-to-use & hard-to-misuse philosophy.</details> |
| 11:05-11:35  || Lenka Marekova  (ETH Zurich) |
|              || **Analysis of the Telegram Key Exchange** <details close>We describe, formally model, and prove the security of Telegram's key exchange protocols for client-server communications. Our security proofs reduce the security of the protocols to that of their cryptographic building blocks, but the subsequent analysis of those building blocks requires the introduction of a number of novel security assumptions, reflecting many design decisions made by Telegram that are suboptimal from the perspective of formal analysis. In this talk, I'll discuss the difficulties we encountered on the way as well as the broader lessons about protocol design that can be taken from our work. This talk is based on joint work with Martin R. Albrecht, Kenny Paterson, Eyal Ronen, and Igors Stepanovs.</details> |
| 11:35-12:05  || Subhadeep Banik  (USI Lugano) |
|              || **The TEA-3 Encryption Algorithm** <details close>We present a number of observations on TEA-3, a stream cipher used in TETRA radio networks that was kept secret until recently. While the same also holds for the six other TETRA encryption algorithms, we pick TEA-3 to start with, as (i) it is not obviously weakened as TEA-1,4,7 but (ii) in contrast to TEA-2 it is approved for extra-European emergency service, and (iii) as already noted by Meijer et al at USENIX23 the TEA-3 design surprisingly contains a non-bijective S-box. Most importantly, we show that the 80-bit non-linear feedback shift register operating on the key decomposes into a cascade of two 40-bit registers. Although this hints at an intentional weakness at first glance, we are not able to lift our results to a practical attack. Also we shed some light as to why the length of the initial vector used in the cipher is limited to 29 bits. </details> |
| 12:05-14:00  || **Lunch Break** |
| 14:00-15:00  || **Session 2 (Short Talks)** |
|              || Nan Cheng (Univ of St Gallen) **Mixed-protocol multi-party secure computation**<details close>The advantage of mixed-protocol multi-party secure computation frameworks lies in their ability to utilize different sharing types optimally for diverse tasks. A key module in these frameworks are Boolean-to-arithmetic secret sharing conversion protocols, which transfer a secret value from Boolean secret sharing to arithmetic secret sharing. This conversion process can either take in the Boolean secret sharing of a bit or a secret binary string. In this talk, I will introduce an innovative correlated random tuple for this task in the semi-honest three-party (3PC) setting. This tuple provides the basis for building Boolean-to-arithmetic share conversion protocols. When it comes to concrete efficiency, the proposed B2A protocol shows superior performance compared to the existing state-of-the-art in ABY3 (CCS ’18). It achieves this by reducing the total required communication from 2ℓ bits per party to 4ℓ/3 + 1 bits (including 4ℓ/3 bits in the setup phase, and 1 bit in the online phase) per party, while maintaining a single round of optimized communication. </details> |
|              || Mia Filić (ETH Zurich) **Probabilistic data structures**<details close>Probabilistic data structures (PDS) are compact representations of high-volume data that provide approximate answers to queries about the data. They are commonplace in today’s computing systems, finding use in databases, networking and more. While PDS are designed to perform well under benign inputs, they are frequently used in applications where inputs may be adversarially chosen. This may lead to a violation of their expected behaviour, for example an increase in false positive rate. In this talk, we focus on PDS that handle approximate membership queries (AMQ). We consider adversarial users with the capability of making adaptive insertions, deletions and membership queries to AMQ-PDS, and analyse the performance of AMQ-PDS under such adversarial inputs. We argue that deletions significantly empower adversaries, presenting a challenge to enforcing honest behaviour when compared to insertion-only AMQ-PDS. By leveraging simulation-based security definitions, we then quantify how much harm can be caused by adversarial users to the functionality of AMQ-PDS. Our resulting bounds only require calculating the maximal false positive probability and insertion failure probability achievable in our novel honest setting. We apply our results to well-known Cuckoo filters and Counting filters. We show how to protect these AMQ-PDS by replacing or composing the hash functions with keyed pseudorandom functions in their construction. This strategy involves establishing practical bounds for the probabilities mentioned above. We demonstrate how to achieve security against adversarial users making both insertions and deletions. We also comment on interesting future directions and their applications. </details> |
|              || Zijing Di (EPFL) **Quantum Rewinding for IOP-Based Succinct Arguments**<details close>We analyze the post-quantum security of succinct interactive arguments constructed from interactive oracle proofs (IOPs) and vector commitment schemes. We prove that an interactive variant of the BCS transformation is secure in the standard model against quantum adversaries when the vector commitment scheme is collapsing. Our security reduction relies on quantum rewinding to extract a quantum IOP adversary (a quantum algorithm) that is almost “as good as” the given quantum argument adversary. We contribute a quantum rewinding strategy that overcomes limitations of prior work on the post-quantum security of Kilian’s succinct interactive argument, which is instead based on probabilistically checkable proofs (PCPs). As an application of our results, we obtain post-quantum secure succinct arguments, in the standard model (no oracles), with the best asymptotic complexity known. </details> |
|              || Christian Knabenhans (EPFL) **On the Fiat–Shamir Security of Succinct Arguments from Functional Commitments**<details close>We study the security of a popular paradigm for constructing SNARGs, closing a key security gap left open by prior work. The paradigm consists of two steps: first, construct a public-coin succinct interactive argument by combining a functional interactive oracle proof (FIOP) and a functional commitment scheme (FC scheme); second, apply the Fiat–Shamir transformation in the random oracle model. Prior work did not consider this generalized setting nor prove the security of this second step (even in special cases). We prove that the succinct argument obtained in the first step satisfies state-restoration security, thereby ensuring that the second step does in fact yield a succinct non-interactive argument. This is provided the FIOP satisfies state-restoration security and the FC scheme satisfies a natural state-restoration variant of function binding (a generalization of position binding for vector commitment schemes). Moreover, we prove that notable FC schemes satisfy state-restoration function binding, allowing us to establish, via our main result, the security of several SNARGs of interest (in the random oracle model). This includes a security proof of Plonk in the ROM, based on a standard falsifiable assumption. </details> |
|              || Ziyi Guan (EPFL) **Breaking Verifiable Delay Functions in the Random Oracle Model**<details close>This work resolves the open problem of whether verifiable delay functions (VDFs) can be constructed in the random oracle model. A VDF is a cryptographic primitive that requires a long time to compute (even with parallelization), but produces a unique output that is efficiently and publicly verifiable. We prove that VDFs do not exist in the random oracle model. This also rules out black-box constructions of VDFs from other cryptographic primitives, such as one-way functions, one-way permutations and collision-resistant hash functions. Prior to our work, Mahmoody, Smith and Wu (ICALP 2020) prove that perfectly unique VDFs (a much stronger form of VDFs) do not exist in the random oracle model; on the other hand, Ephraim, Freitag, Komargodski, and Pass (Eurocrypt 2020) construct VDFs in the random oracle model assuming the hardness of repeated squaring. Our result is optimal -- we bridge the current gap between previously known impossibility results and existing constructions. We initiate the study of proof of work functions, a new cryptographic primitive that shares similarities with both VDFs and proof of works. We show that a stronger form of it does not exist in the random oracle model, leaving open the fascinating possibility of a random-oracle-based construction. </details> |
|              || Nicholas Brandt (ETH Zurich) **Unbiasable Verifiable Random Function from Generic Assumptions**<details close>We present conceptually simple constructions of verifiable random functions (VRF) that fulfill strong notions of unbiasability recently introduced by Giunta and Stewart [Eurocrypt24]. VRFs with such strong properties were previously only known in the random oracle model or from the decisional Diffie-Hellman assumption with preprocessing. In contrast, our constructions are based on generic assumptions and are thus the first to be plausibly post-quantum secure.</details> |
|              || Giacomo Borin (IBM Research Zurich) **PRISM: Simple And Compact Signatures From Large Prime Degree Isogenies**<details close>The problem of computing an isogeny of large prime degree from a supersingular elliptic curve of unknown endomorphism ring is assumed to be hard both for classical as well as quantum computers. Using the hash-and-sign paradigm, we show how to derive from this problem a signature scheme with a very simple and flexible signing procedure, comparable to SQIsign in efficiency, but amenable for more complex advanced constructions.</details> |
|              || Ziyi Guan (EPFL) **Relativized Succinct Arguments in the ROM Do Not Exist**<details close>A relativized succinct argument in the random oracle model (ROM) is a succinct argument in the ROM that can prove/verify the correctness of computations that involve queries to the random oracle. We prove that relativized succinct arguments in the ROM do not exist. The impossibility holds even if the succinct argument is interactive, and even if soundness is computational (rather than statistical). This impossibility puts on a formal footing the commonly-held belief that succinct arguments require non-relativizing techniques. Moreover, our results stand in sharp contrast with other oracle models, for which a recent line of work has constructed relativized succinct non-interactive arguments (SNARGs). Indeed, relativized SNARGs are a powerful primitive that, e.g., can be used to obtain constructions of IVC (incrementally-verifiable computation) and PCD (proof-carrying data) based on falsifiable cryptographic assumptions. Our results rule out this approach for IVC and PCD in the ROM.</details> |
|              || Ryan Rueger (IBM/TUM) **PEGASIS: Practical Effective Class Group Action using 4-dimensional Isogenies**<details close>Many cryptographic primitives can be instantiated from group actions, however, for advanced constructions, the action must be unrestricted; that is, it must be possible to evaluate the action on arbitrary group elements efficiently, not just polynomially many generators. Using 4-dimensional isogenies, we unrestrict the action of CSIDH whilst scaling better than the SCALLOP family, yielding the first unrestricted post-quantum cryptographic group action that is both practically and asymptotically efficient. Our proof-of-concept sagemath implementation beats the state-of-the-art of unrestricted actions, taking 1.5s (resp. 122s) to evaluate at 128bits (resp. 1000bits) of classical security; whilst only being slower by a factor of 40 in comparison to the C implementation of CSIDH (which is restricted). Allowing for high classical security parameters encourages belief in quantum resistance of the construction.</details> |
|              || Jenit Tomy (Univ of St Gallen) **BUFFing Threshold Signature Schemes**<details close>We explore advanced security notions for threshold signature schemes, focusing on Beyond Un-Forgeability Features (BUFF). The BUFF properties protect against attacks based on maliciously chosen keys, e.g., expropriating a message-signature pair under a new public key (called exclusive ownership). We formalize these notions in the threshold setting and examine their relationships. We then present a generic compiler that transforms any threshold signature scheme to satisfy exclusive ownership, and message-bound signature properties with minimal overhead. This talk is based on joint work with Marc Fischlin and Katerina Mitrokotsa.</details> |
| 15:00-15:30  || **Break** |
| 15:30-17:00  || **Session 3** |
| 15:30-16:00  || Bertram Poettering (IBM Zurich)|
|              || **Digital Signatures with Outsourced Hashing** <details close> Most practical signature schemes follow the hash-then-sign paradigm: First the (arbitrarily long) message is mapped to a fixed-length hash value, then a signing core derives the signature from the latter. As it is implementationally attractive, practitioners routinely exploit this structure by decoupling the two steps and distributing them among different entities; for instance, industry standards like PKCS#11 specify how security smartcards implement exclusively the core, leaving the hashing to their (untrusted) environment. At the same time, the classic security notions for signature schemes don’t consider such a decoupling, and thus don’t cover attacks involving, for instance, providing the core with maliciously chosen hash values. We show how the functional separation of hashing and core in signature schemes can be systematized, so that implementational demands (in the spirit of PKCS#11) and, hopefully, security can be met simultaneously. We accompany this foundational work with a case study of a variety of standardized (EC)DLP based signatures. Surprisingly, as we show, their security varies across the full spectrum between universally forgeable and provably unforgeable. For instance, for the same scheme, we demonstrate universal forgeries when instantiated with 224-bit ECC (using an attack that completes in milliseconds), while we establish strong unforgeability for the 256-bit ECC case. Many schemes become completely insecure when the hash function is instantiated with SHA3 instead of with SHA2. </details>|
| 16:00-16:30  || Jayamine Alupotha  (University of Bern) |
|              || **Anonymous Self-Credentials and their Application to Single-Sign-On**<details close> Modern life makes having a digital identity no longer optional, whether one needs to manage a bank account or subscribe to a newspaper. As the number of online services increases, it is fundamental to safeguard user privacy and equip service providers (SP) with mechanisms enforcing Sybil resistance, i.e., preventing a single entity from showing as many. Current approaches, such as anonymous credentials and self-sovereign identities, typically rely on identity providers or identity registries trusted not to track users' activities. However, this assumption of trust is no longer appropriate in a world where user data is considered a valuable asset. To address this challenge, we introduce a new cryptographic notion, Anonymous Self-Credentials (ASC), along with two implementations. This approach enables users to maintain their privacy within an anonymity set while allowing SPs to obtain Sybil resistance. Then, we present a User-issued Unlinkable Single Sign-On (U2SSO) implemented from ASC that solely relies on an identity registry to immutably store identities. U2SSO solution allows users to generate unlinkable child credentials for each SP using only one set of master credentials. We demonstrate the practicality and efficiency of our U2SSO solution by providing a complete proof of concept. </details>|
| 16:30-17:00  || Andrea Cerulli (DFINITY) |
|              || **Integrating Threshold Signatures on the Internet Computer**<details close>Threshold signatures offer significant advantages in distributed systems, providing enhanced security and fault tolerance by requiring multiple parties to collaborate in signing a message. However, integrating threshold signatures into real-world systems comes with a unique set of challenges. In this talk we explore some of the practical challenges faced when integrating threshold signatures schemes on the Internet Computer blockchain and how these challenges affected key design decisions. </details> |
| 17:00-17:10  || Closing Remarks|
||||


##### Registration

Participation is free of cost but is necessary for planning and organization.
Please register at the following [Link](https://forms.office.com/e/gkUdqARkHV)

Registration deadline 27th March 2025.


<h1>Venue & Logistics</h1>
<h3>Lugano, Switzerland</h3>


<p>
<a href="http://www.luganoturismo.ch/en/discover/city">Lugano</a>, the largest town in the holiday region of Ticino, is not only Switzerland's third most important financial centre and a conference, banking and business centre, but also a town of parks and flowers, villas and sacred buildings. With Mediterranean flair, Lugano offers all the advantages of a world-class city, combined with the cachet of a small town.
</p>

<p>
Lugano lies in a bay on the northern side of <a href="http://www.luganoturismo.ch/en">Lake Lugano</a>, surrounded by numerous mountains offering splendid viewpoints. The traffic-free historic town centre, the numerous buildings in Italianate Lombardy style, the exclusive museums, the mountains, lake and a packed calendar of events all invite visitors to see the sights, soak up the atmosphere - and enjoy &quot;dolce far niente&quot;. Thanks to its <a href="https://meteo.search.ch/lugano">mild climate</a>, Lugano is a popular tourist destination from spring to fall.
</p>
<p>
The <a href="http://www.luganoturismo.ch/en/discover/city">town centre</a> with its Mediterranean-style squares and arcades, and numerous parks with sub-tropical plants such as the Parco Civico on the shores of the lake invite you to laze around, enjoying the atmosphere. By the lakeside promenade are the Belvedere Gardens, where the parkland boasts not only camellias and magnolias but also countless sub-tropical plants and modern works of art. <small>(Text and images courtesy of <a href="http://www.myswitzerland.com/en-ch/lugano.html">Swiss Tourism</a>)</small>
</p>

<p>
    Watch the video to get a feeling of Lugano and its atmosphere! <a href="http://www.youtube.com/embed/uhAl8oYII1o?rel=0">HERE</a>
</p>

<h3>Travel & Access</h3>
<div class="col-xs-6 main-body">
<p>Lugano is best reachable by train or by air. 
</p>
<ul>
<li><strong>By Air:</strong>
<!--<img align=right width="40%" src="./img/ch-by-plane.jpg" class="margined"/> -->
Zurich airport is approx. 200 km away from Lugano, but very conveniently connected with it by frequent trains. It takes around 2.5 hours to reach Lugano from Zurich airport. Zurich airport is serving all major worldwide destinations. The train ticket to Lugano can be purchased shortly before the trip (no need to pre-book).<br>
<br>
Lugano is reasonably well connected to Milano (about 60km distance). Milano has three airports: Malpensa (Terminal 1, Terminal 2), Linate, and Bergamo. The Malpensa Airport, which is the closest to Lugano, is connected to Lugano by train <a href="http://www.sbb.ch/en/home.html">http://www.sbb.ch/</a> 
The Milano Linate and Bergamo airports are not directly connected to Lugano - passengers first need to take a shuttle bus or a train to Milano City Center and then take a train to Lugano. It will take approx. 3-4 hours from Bergamo or Linate to reach Lugano.
</li><br>
<li><strong>By Train:</strong>
<!-- <img align=right width="40%" src="./img/ch-by-train.jpg" class="margined" />  -->
Lugano train station is well connected to all major cities in Europe, e.g., Rome (via Milan), Frankfurt, or Paris (both via Zurich). Using the train is not only the most convenient but also the most environmentally friendly option to reach Lugano. Trains coming from Zurich will travel through the new <a href="http://www.gottardo2016.ch/en">Gotthard Base Tunnel</a> - the <a href="https://en.wikipedia.org/wiki/List_of_longest_tunnels">world's longest and deepest travel tunnel</a>, completed in 2016 after 20 years of work. Sample travel times in hours and minutes: 1:15 from Milan, 2:08 from Zurich, 4:25 from Rome, 6:16 from Frankfurt, and 7:00 from Paris.<br><br>
Train tickets inside Switzerland have fixed prices, there is no difference between pre-booking and getting your tickets at the vending machines. Make sure you get your ticket before boarding the train: ticket sales in the train are subject to higher fees. Tickets and schedules are available at <a href="http://www.sbb.ch/en/home.html">http://www.sbb.ch/</a>. If you are planning to travel a lot inside Switzerland by train, it might be worth getting a travel pass (e.g., Swiss Travel Pass or the "Half-Fare Travel card") - see <a href="https://www.swiss-pass.ch/">https://www.swiss-pass.ch/</a>. 
</li><br>
<li><strong>By Car:</strong>
<!-- <img align=right width="40%" src="./img/ch-by-car.jpg" class="margined" /> -->
We strongly advise against traveling to Lugano by car. If you are coming from Zurich, the Gotthard road tunnel is often a major bottleneck, with traffic jams of several hours each weekend. From Milan, the border at Como-Chiasso will often result in long waiting lines. Plus: once in Lugano, finding parking is difficult and expensive. You do not need a car in Lugano: the symposium venue (i.e., the University) is a 10-minute walk from the city center and most hotels. An efficient and frequent bus service connects all parts of the city (especially all recommended hotels and the University). Trains are connecting Lugano with surrounding cities, villages and attractions. However, if you want a rental car, both the airport and the train station feature a number of rental agencies.
</li>
</ul>
<br>
<br>
</div>


<h3>Conference Venue</h3>
<p>
<!-- <img align=right src="./img/usi-entrance.jpg" /> -->
<!--<img align=right width="30%" src="./img/usi-campus-green.jpg" class="margined" /> -->
The Spring Crypto Day 2025 will take place in the Aula Polivalente, East Campus of the <a href="http://www.usi.ch">&quot;Universit&#224; della Svizzera italiana&quot;</a> - or USI for short. The East Campus of USI is located in Lugano (Switzerland), in Via la Santa 1, Viganello neighborhood. USI is Switzerland’s most international university, and one of the 12 certified public universities in Switzerland coordinated by <a href="https://www.swissuniversities.ch/en">swissuniversities</a>. </p>
<p>
Established in 1996, USI has grown steadily and includes today five Faculties: Architecture, Economics, Communication Sciences, <a href="http://www.inf.usi.ch/">Informatics</a> and Biomedical Sciences. USI currently counts also three affiliated entities, the Institute for Research in Biomedicine (IRB, Bellinzona), the Institute for Oncology Research (IOR, Bellinzona) and the Dalle Molle Institute for Artificial Intelligence (IDSIA, Manno).</p>
<p>
The <a href="http://www.inf.usi.ch">Faculty of Informatics</a> stands out as a centre of competence in advanced informatics. Since its inception in 2004, it has become one of Switzerland’s major poles for informatics teaching and research, ranking third after the two Federal Institutes of Technology, ETH Zurich and EPFL in Lausanne. It features a faculty of ~30 professors, 40+ postdocs and more than 100 PhD students.</p>

<p>
<div class="google-maps">
<iframe src="https://www.google.com/maps/embed?pb=!1m18!1m12!1m3!1d2771.0135421983528!2d8.95603381532269!3d46.01092200481717!2m3!1f0!2f0!3f0!3m2!1i1024!2i768!4f13.1!3m3!1m2!1s0x47842d8a7d9d44e1%3A0x51147d79a8566d60!2sUniversit%C3%A0+della+Svizzera+italiana!5e0!3m2!1sit!2sch!4v1491211269079" width="600" height="450" frameborder="0" style="border:0" allowfullscreen></iframe></p>
</div>
</p>



<p></p>


##### Mailing list
To subscribe to the mailing list, please visit [list.inf.unibe.ch](https://list.inf.unibe.ch/postorius/lists/swisscryptoday.list.inf.unibe.ch/) or send an empty email to: `swisscryptoday-join@list.inf.unibe.ch`.
