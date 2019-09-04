# Papers List

* ### [Ethereum papers](ethereum/)
* ### [Hyperledger papers](hyperledger/)

* ### Towards Blockchain'enabled Searchable Encryption by Qiang Tang

  * Abstract: Distributed Leger Technologies (DLTs), most notably Blockchain technologies,
bring decentralised platforms that eliminate a single trusted third party and
avoid the notorious single point of failure vulnerability. Since Nakamoto's
Bitcoin cryptocurrency system, an enormous number of decentralised applications
have been proposed on top of these technologies, aiming at more transparency
and trustworthiness than their traditional counterparts. These applications
spread over a lot of areas, e.g. financial services, healthcare,
transportation, supply chain management, and cloud computing. While Blockchain
brings transparency and decentralised trust intuitively due to the consensus of
a (very large) group of nodes (or, miners), it introduces very subtle
implications for other desirable properties such as privacy. In this work, we
demonstrate these subtle implications for Blockchain-based searchable
encryption solutions, which are one specific use case of cloud computing
services. These solutions rely on Blockchain to achieve both the standard
privacy property and the new fairness property, which requires that search
operations are carried out faithfully and are rewarded accordingly. We show
that directly replacing the server in an existing searchable encryption
solution with a Blockchain will cause undesirable operational cost, privacy
loss, and security vulnerabilities. The analysis results indicate that a
dedicated server is still needed to achieve the desired privacy guarantee. To
this end, we propose two frameworks which can be instantiated based on most
existing searchable encryption schemes. Through analysing these two frameworks,
we affirmatively show that a carefully engineered Blockchain-based solution can
achieve the desired fairness property while preserving the privacy guarantee of
the original searchable encryption scheme simultaneously.

  * Publication date: 2019-08-26T09:43:58Z

  * Arxiv: http://arxiv.org/abs/1908.09564v1


* ### Blockchain based access control systems: State of the art and challenges by Sara Rouhani, Ralph Deters

  * Abstract: Access to the system resources. The current access control systems face many
problems, such as the presence of the third-party, inefficiency, and lack of
privacy. These problems can be addressed by blockchain, the technology that
received major attention in recent years and has many potentials. In this
study, we overview the problems of the current access control systems, and
then, we explain how blockchain can help to solve them. We also present an
overview of access control studies and proposed platforms in different domains.
This paper presents the state of the art and the challenges of blockchain-based
access control systems.

  * Publication date: 2019-08-22T17:21:43Z

  * Arxiv: http://arxiv.org/abs/1908.08503v1


* ### Detecting Fraudulent Accounts on Blockchain: A Supervised Approach by Michal Ostapowicz, Kamil Żbikowski

  * Abstract: Applications of blockchain technologies got a lot of attention in recent
years. They exceed beyond exchanging value and being a substitute for fiat
money and traditional banking system. Nevertheless, being able to exchange
value on a blockchain is at the core of the entire system and has to be
reliable. Blockchains have built-in mechanisms that guarantee whole system's
consistency and reliability. However, malicious actors can still try to steal
money by applying well known techniques like malware software or fake emails.
In this paper we apply supervised learning techniques to detect fraudulent
accounts on Ethereum blockchain. We compare capabilities of Random Forests,
Support Vector Machines and XGBoost classifiers to identify such accounts
basing on a dataset of more than 300 thousands accounts. Results show that we
are able to achieve recall and precision values allowing for the designed
system to be applicable as an anti-fraud rule for digital wallets or currency
exchanges. We also present sensitivity analysis to show how presented models
depend on particular feature and how lack of some of them will affect the
overall system performance.

  * Publication date: 2019-08-21T14:15:42Z

  * Arxiv: http://arxiv.org/abs/1908.07886v1


* ### Blockguard: Adaptive Blockchain Security by Shishir Rai, Kendric Hood, Mikhail Nesterenko, Gokarna Sharma

  * Abstract: We consider the problem of varying the security of blockchain transactions
according to their importance. This adaptive security is achieved by using
variable size consensus committees. To improve performance, such committees
function concurrently. We present two algorithms that allow adaptive security
by forming concurrent variable size consensus committees on demand. One is
based on a single joint blockchain, the other is based on separate sharded
blockchains. For in-committee consensus, our algorithms may use various
available byzantine-robust fault tolerant algorithms (BFT). We implement
synchronous BFT, asynchronous BFT and proof-of-work consensus. We thoroughly
evaluate the performance of our adaptive security algorithms.

  * Publication date: 2019-07-30T21:32:43Z

  * Arxiv: http://arxiv.org/abs/1907.13232v1


* ### Fair Byzantine Agreements for Blockchains by Tzu'Wei Chao, Hao Chung, Po'Chun Kuo

  * Abstract: Byzantine general problem is the core problem of the consensus algorithm, and
many protocols are proposed recently to improve the decentralization level, the
performance and the security of the blockchain. There are two challenging
issues when the blockchain is operating in practice. First, the outcomes of the
consensus algorithm are usually related to the incentive model, so whether each
participant's value has an equal probability of being chosen becomes essential.
However, the issues of fairness are not captured in the traditional security
definition of Byzantine agreement. Second, the blockchain should be resistant
to network failures, such as cloud services shut down or malicious attack,
while remains the high performance most of the time.
  This paper has two main contributions. First, we propose a novel notion
called fair validity for Byzantine agreement. Intuitively, fair validity
lower-bounds the expected numbers that honest nodes' values being decided if
the protocol is executed many times. However, we also show that any Byzantine
agreement could not achieve fair validity in an asynchronous network, so we
focus on synchronous protocols. This leads to our second contribution: we
propose a fair, responsive and partition-resilient Byzantine agreement protocol
tolerating up to 1/3 corruptions. Fairness means that our protocol achieves
fair validity. Responsiveness means that the termination time only depends on
the actual network delay instead of depending on any pre-determined time bound.
Partition-resilience means that the safety still holds even if the network is
partitioned, and the termination will hold if the partition is resolved.

  * Publication date: 2019-07-08T07:43:24Z

  * Arxiv: http://arxiv.org/abs/1907.03437v1


* ### Integrating Privacy Enhancing Techniques into Blockchains Using  Sidechains by Reza M. Parizi, Sajad Homayoun, Abbas Yazdinejad, Ali Dehghantanha, Kim'Kwang Raymond Choo

  * Abstract: Blockchains are turning into decentralized computing platforms and are
getting worldwide recognition for their unique advantages. There is an emerging
trend beyond payments that blockchains could enable a new breed of
decentralized applications, and serve as the foundation for Internet's security
infrastructure. The immutable nature of the blockchain makes it a winner on
security and transparency; it is nearly inconceivable for ledgers to be altered
in a way not instantly clear to every single user involved. However, most
blockchains fall short in privacy aspects, particularly in data protection.
Garlic Routing and Onion Routing are two of major Privacy Enhancing Techniques
(PETs) which are popular for anonymization and security. Garlic Routing is a
methodology using by I2P Anonymous Network to hide the identity of sender and
receiver of data packets by bundling multiple messages into a layered
encryption structure. The Onion Routing attempts to provide lowlatency
Internet-based connections that resist traffic analysis, deanonymization
attack, eavesdropping, and other attacks both by outsiders (e.g. Internet
routers) and insiders (Onion Routing servers themselves). As there are a few
controversies over the rate of resistance of these two techniques to privacy
attacks, we propose a PET-Enabled Sidechain (PETES) as a new privacy enhancing
technique by integrating Garlic Routing and Onion Routing into a Garlic Onion
Routing (GOR) framework suitable to the structure of blockchains. The
preliminary proposed GOR aims to improve the privacy of transactions in
blockchains via PETES structure.

  * Publication date: 2019-06-12T05:48:04Z

  * Arxiv: http://arxiv.org/abs/1906.04953v1


* ### A Blockchain'based Framework for Detecting Malicious Mobile Applications  in App Stores by Sajad Homayoun, Ali Dehghantanha, Reza M. Parizi, Kim'Kwang Raymond Choo

  * Abstract: The dramatic growth in smartphone malware shows that malicious program
developers are shifting from traditional PC systems to smartphone devices.
Therefore, security researchers are also moving towards proposing novel
antimalware methods to provide adequate protection. This paper proposes a
Blockchain-Based Malware Detection Framework (B2MDF) for detecting malicious
mobile applications in mobile applications marketplaces (app stores). The
framework consists of two internal and external private blockchains forming a
dual private blockchain as well as a consortium blockchain for the final
decision. The internal private blockchain stores feature blocks extracted by
both static and dynamic feature extractors, while the external blockchain
stores detection results as blocks for current versions of applications. B2MDF
also shares feature blocks with third parties, and this helps antimalware
vendors to provide more accurate solutions.

  * Publication date: 2019-06-12T05:38:30Z

  * Arxiv: http://arxiv.org/abs/1906.04951v1


* ### Secure Software'Defined Networking Based on Blockchain by Weng Jiasi, Weng Jian, Liu Jia'Nan, Zhang Yue

  * Abstract: Software-Defined Networking (SDN) separates the network control plane and
data plane, which provides a network-wide view with centralized control (in the
control plane) and programmable network configuration for data plane injected
by SDN applications (in the application plane). With these features, a number
of drawbacks of the traditional network architectures such as static
configuration, non-scalability and low efficiency can be effectively avoided.
However, SDN also brings with it some new security challenges, such as
single-point failure of the control plane, malicious flows from applications,
exposed network-wide resources and a vulnerable channel between the control
plane and the data plane. In this paper, we design a monolithic security
mechanism for SDN based on Blockchain. Our mechanism decentralizes the control
plane to overcome single-point failure while maintaining a network-wide view.
The mechanism also guarantees the authenticity, traceability, and
accountability of application flows, and hence secures the programmable
configuration. Moreover, the mechanism provides a fine-grained access control
of network-wide resources and a secure controller-switch channel to further
protect resources and communication in SDN.

  * Publication date: 2019-06-11T01:32:05Z

  * Arxiv: http://arxiv.org/abs/1906.04342v1


* ### Access Control for Electronic Health Records with Hybrid Blockchain'Edge  Architecture by Hao Guo, Wanxin Li, Mark Nejad, Chien'Chung Shen

  * Abstract: The global Electronic Health Record (EHR) market is growing dramatically and
expected to reach .7 billions by 2022. To safe-guard security and privacy of
EHR, access control is an essential mechanism for managing EHR data. This paper
proposes a hybrid architecture to facilitate access control of EHR data by
using both blockchain and edge node. Within the architecture, a
blockchain-based controller manages identity and access control policies and
serves as a tamper-proof log of access events. In addition, off-chain edge
nodes store the EHR data and apply policies specified in Abbreviated Language
For Authorization (ALFA) to enforce attribute-based access control on EHR data
in collaboration with the blockchain-based access control logs. We evaluate the
proposed hybrid architecture by utilizing Hyperledger Composer Fabric
blockchain to measure the performance of executing smart contracts and ACL
policies in terms of transaction processing time and response time against
unauthorized data retrieval.

  * Publication date: 2019-06-04T04:01:08Z

  * Arxiv: http://arxiv.org/abs/1906.01188v1


* ### BlockLoc: Secure Localization in the Internet'of'Things using Blockchain by Omar Cheikhrouhou, Anis Koubaa

  * Abstract: Several IoT applications are tightly dependent on the locations of the
devices. However, localization algorithms can be easily compromised by
injecting false locations. In this paper, we propose a Blockchain-based secure
localization algorithm for the Internet of Things (IoT). The algorithm uses a
public ledger (Blockchain) that contains nodes position and the list of their
neighbor nodes. This ledger is shared among the IoT devices. Once an IoT device
is localized its new position and the list of neighbor nodes are added to the
Blockchain. This shared localization data will be used later by other IoT
devices for their localization process. To avoid the attack where a malicious
node sends a fake position, the correctness of the claimed position are
verified before adding it to the Blockchain. Moreover, data exchanged between
nodes (IoT devices) are signed to guarantee their authenticity and integrity.
The integration of these security mechanisms into the localization process
permits to exclude false data and therefore reduces the localization error. The
simulation results show that adding the proposed security mechanism improves
the localization accuracy of the algorithm when running in the presence of
malicious nodes.

  * Publication date: 2019-04-30T10:23:35Z

  * Arxiv: http://arxiv.org/abs/1904.13138v1


* ### Agent'Based Simulations of Blockchain protocols illustrated via Kadena's  Chainweb by Tarun Chitra, Monica Quaintance, Stuart Haber, Will Martino

  * Abstract: While many distributed consensus protocols provide robust liveness and
consistency guarantees under the presence of malicious actors, quantitative
estimates of how economic incentives affect security are few and far between.
In this paper, we describe a system for simulating how adversarial agents, both
economically rational and Byzantine, interact with a blockchain protocol. This
system provides statistical estimates for the economic difficulty of an attack
and how the presence of certain actors influences protocol-level statistics,
such as the expected time to regain liveness. This simulation system is
influenced by the design of algorithmic trading and reinforcement learning
systems that use explicit modeling of an agent's reward mechanism to evaluate
and optimize a fully autonomous agent. We implement and apply this simulation
framework to Kadena's Chainweb, a parallelized Proof-of-Work system, that
contains complexity in how miner incentive compliance affects security and
censorship resistance. We provide the first formal description of Chainweb that
is in the literature and use this formal description to motivate our simulation
design. Our simulation results include a phase transition in block height
growth rate as a function of shard connectivity and empirical evidence that
censorship in Chainweb is too costly for rational miners to engage in. We
conclude with an outlook on how simulation can guide and optimize protocol
development in a variety of contexts, including Proof-of-Stake parameter
optimization and peer-to-peer networking design.

  * Publication date: 2019-04-29T19:48:20Z

  * Arxiv: http://arxiv.org/abs/1904.12924v1


* ### Blockchain Enabled Privacy Preserving Data Audit by Prabal Banerjee, Nishant Nikam, Sushmita Ruj

  * Abstract: Data owners upload large files to cloud storage servers, but malicious
servers may potentially tamper data. To check integrity of remote data, Proof
of Retrievability (PoR) schemes were introduced. Existing PoR protocols assume
that data owners and third-party auditors are honest and audit only the
potentially malicious cloud server to check integrity of stored data. In this
paper we consider a system where any party may attempt to cheat others and
consider collusion cases. We design a protocol that is secure under such
adversarial assumptions and use blockchain smart contracts to act as mediator
in case of dispute and payment settlement. We use state channels to reduce
blockchain interactions in order to build a practical audit solution. We
implement and evaluate a prototype using Ethereum as the blockchain platform
and show that our scheme has comparable performance.

  * Publication date: 2019-04-28T18:30:00Z

  * Arxiv: http://arxiv.org/abs/1904.12362v1


* ### Bitcoin and Blockchain: Security and Privacy by Ehab Zaghloul, Tongtong Li, Matt Mutka, Jian Ren

  * Abstract: A cryptocurrency is a decentralized digital currency that is designed for
secure and private asset transfer and storage. As a currency, it should be
difficult to counterfeit and double-spend. In this paper, we review and analyze
the major security and privacy issues of Bitcoin. In particular, we focus on
its underlying foundation, blockchain technology. First, we present a
comprehensive background of Bitcoin and the preliminary on security. Second,
the major security threats and countermeasures of Bitcoin are investigated. We
analyze the risk of double-spending attacks, evaluate the probability of
success in performing the attacks and derive the profitability for the attacker
to perform such attacks. Third, we analyze the underlying Bitcoin peer-to-peer
network security risks and Bitcoin storage security. We compare three types of
Bitcoin wallets in terms of security, type of services and their trade-offs.
Finally, we discuss the security and privacy features of alternative
cryptocurrencies and present an overview of emerging technologies today. Our
results can help Bitcoin users to determine a trade-off between the risk of
double-spending attempts and the transaction time delay or confidence before
accepting transactions. These results can also assist miners to develop
suitable strategies to get involved in the mining process and maximize their
profits.

  * Publication date: 2019-04-25T16:16:06Z

  * Arxiv: http://arxiv.org/abs/1904.11435v1


* ### A Security Reference Architecture for Blockchains by Ivan Homoliak, Sarad Venugopalan, Qingze Hum, Pawel Szalachowski

  * Abstract: Due to their interesting features, blockchains have become popular in recent
years. They are full-stack systems where security is a critical factor for
their success. The main focus of this work is to systematize knowledge about
security and privacy issues of blockchains. To this end, we propose a security
reference architecture based on models that demonstrate the stacked hierarchy
of various threats (similar to the ISO/OSI hierarchy) as well as threat-risk
assessment using ISO/IEC 15408. In contrast to the previous surveys, we focus
on the categorization of security incidents based on their origins and using
the proposed architecture we present existing prevention and mitigation
techniques. The scope of our work mainly covers aspects related to the
decentralized nature of blockchains, while we mention common operational
security issues and countermeasures only tangentially.

  * Publication date: 2019-04-15T08:05:35Z

  * Arxiv: http://arxiv.org/abs/1904.06898v1


* ### Secure Consistency Verification for Untrusted Cloud Storage by Public  Blockchains by Kai Li, Yuzhe Tang, Beom Heyn Kim, Jianliang Xu

  * Abstract: This work presents ContractChecker, a Blockchain-based security protocol for
verifying the storage consistency between the mutually distrusting cloud
provider and clients. Unlike existing protocols, the ContractChecker uniquely
delegates log auditing to the Blockchain, and has the advantages in reducing
client cost and lowering requirements on client availability, lending itself to
modern scenarios with mobile and web clients.
  The ContractChecker collects the logs from both clients and the cloud server,
and verifies the consistency by cross-checking the logs. By this means, it does
not only detects the attacks from malicious clients and server forging their
logs, but also is able to mitigate those attacks and recover the system from
them. In addition, we design new attacks against ContractChecker exploiting
various limits in real Blockchain systems (e.g., write unavailability,
Blockchain forks, contract race conditions). We analyze and harden the security
of ContractChecker protocols against the proposed new attacks.
  For evaluating the cost, we build a functional prototype of the
ContractChecker on Ethereum/Solidity. By experiments on private and public
Ethereum testnets, we extensively evaluate the cost of the ContractChecker in
comparison with that of existing client-based log auditing works. The result
shows the ContractChecker can scale to hundreds of clients and save client
costs by more than one order of magnitude.

  * Publication date: 2019-04-14T04:42:54Z

  * Arxiv: http://arxiv.org/abs/1904.06626v3


* ### Exploring the Attack Surface of Blockchain: A Systematic Overview by Muhammad Saad, Jeffrey Spaulding, Laurent Njilla, Charles Kamhoua, Sachin Shetty, DaeHun Nyang, Aziz Mohaisen

  * Abstract: In this paper, we systematically explore the attack surface of the Blockchain
technology, with an emphasis on public Blockchains. Towards this goal, we
attribute attack viability in the attack surface to 1) the Blockchain
cryptographic constructs, 2) the distributed architecture of the systems using
Blockchain, and 3) the Blockchain application context. To each of those
contributing factors, we outline several attacks, including selfish mining, the
51% attack, Domain Name System (DNS) attacks, distributed denial-of-service
(DDoS) attacks, consensus delay (due to selfish behavior or distributed
denial-of-service attacks), Blockchain forks, orphaned and stale blocks, block
ingestion, wallet thefts, smart contract attacks, and privacy attacks. We also
explore the causal relationships between these attacks to demonstrate how
various attack vectors are connected to one another. A secondary contribution
of this work is outlining effective defense measures taken by the Blockchain
technology or proposed by researchers to mitigate the effects of these attacks
and patch associated vulnerabilities

  * Publication date: 2019-04-06T16:34:34Z

  * Arxiv: http://arxiv.org/abs/1904.03487v1


* ### IoT based Smart Access Controlled Secure Smart City Architecture Using Blockchain by Rourab Paul, Nimisha Ghosh, Suman Sau, Amlan Chakrabarti, Prasant Mahapatra

  * Abstract: Standard security protocols like SSL, TLS, IPSec etc. have high memory and
processor consumption which makes all these security protocols unsuitable for
resource constrained platforms such as Internet of Things (IoT). Blockchain
(BC) finds its efficient application in IoT platform to preserve the five basic
cryptographic primitives, such as confidentiality, authenticity, integrity,
availability and non-repudiation. Conventional adoption of BC in IoT platform
causes high energy consumption, delay and computational overhead which are not
appropriate for various resource constrained IoT devices. This work proposes a
machine learning (ML) based smart access control framework in a public and a
private BC for a smart city application which makes it more efficient as
compared to the existing IoT applications. The proposed IoT based smart city
architecture adopts BC technology for preserving all the cryptographic security
and privacy issues. Moreover, BC has very minimal overhead on IoT platform as
well. This work investigates the existing threat models and critical access
control issues which handle multiple permissions of various nodes and detects
relevant inconsistencies to notify the corresponding nodes. Comparison in terms
of all security issues with existing literature shows that the proposed
architecture is competitively efficient in terms of security access control.

  * Publication date: 2019-08-30T05:37:05Z

  * Arxiv: http://arxiv.org/abs/1908.11538v2


* ### Agent'based Simulation of Blockchains by Edoardo Rosa, Gabriele D'Angelo, Stefano Ferretti

  * Abstract: In this paper, we describe LUNES-Blockchain, an agent-based simulator of
blockchains that is able to exploit Parallel and Distributed Simulation (PADS)
techniques to offer a high level of scalability. To assess the preliminary
implementation of our simulator, we provide a simplified modelling of the
Bitcoin protocol and we study the effect of a security attack on the consensus
protocol in which a set of malicious nodes implements a filtering denial of
service (i.e. Sybil Attack). The results confirm the viability of the
agent-based modelling of blockchains implemented by means of PADS.

  * Publication date: 2019-08-29T14:15:13Z

  * Arxiv: http://arxiv.org/abs/1908.11811v1


* ### Secure Computation Offloading in Blockchain based IoT Networks with Deep Reinforcement Learning by Dinh C. Nguyen, Pubudu N. Pathirana, Ming Ding, Aruna Seneviratne

  * Abstract: In current Internet of Things (IoT) networks, mobile edge-cloud computation
offloading (MECCO) has been regarded as a promising means to support
delay-sensitive IoT applications. However, offloading mobile tasks to cloud is
vulnerable to security risks due to malicious mobile devices (MDs). How to
implement offloading to solve computation problems of MDs while guaranteeing
high security in mobile cloud is challenging. In this paper, we investigate
simultaneously the security and offloading problems in a multi-user MECCO
system on mobile cloud blockchain. First, to improve offloading security, we
propose a trustworthy access control using blockchain, which protects clouds
against illegal offloading behaviours. Then, to tackle the intensive
computation issues of authorized MDs, we formulate a computation offloading
problem by jointly optimizing the offloading decisions and the allocation of
computing resource and radio bandwidth. This optimization problem aims to
minimize the long-term system costs of latency and energy consumption among all
MDs. To solve the proposed offloading problem, we develop a novel deep
reinforcement learning (DRL) algorithm by using advanced deep Q-network. We
evaluate our framework towards access control and offloading performances by
both real experiments and numerical simulations, showing significant advantages
over existing schemes.

  * Publication date: 2019-08-15T07:44:51Z

  * Arxiv: http://arxiv.org/abs/1908.07466v1


* ### Cryptanalysis of two recently proposed ultralightweight authentication protocol for IoT by Masoumeh Safkhani, Nasour Bagheri

  * Abstract: By expanding the connection of objects to the Internet and their entry to
human life, the issue of security and privacy has become important. In order to
enhance security and privacy on the Internet, many security protocols have been
developed. Unfortunately, the security analyzes that have been carried out on
these protocols show that they are vulnerable to one or few attacks, which
eliminates the use of these protocols. Therefore, the need for a security
protocol on the Internet of Things (IoT) has not yet been resolved.
  Recently, Khor and Sidorov cryptanalyzed the Wang et al. protocol and
presented an improved version of it. In this paper, at first, we show that this
protocol also does not have sufficient security and so it is not recommended to
be used in any application. More precisely, we present a full secret disclosure
attack against this protocol, which extracted the whole secrets of the protocol
by two communication with the target tag.
  In addition, Sidorv et al. recently proposed an ultralightweight mutual
authentication RFID protocol for blockchain enabled supply chains, supported by
formal and informal security proofs. However, we present a full secret
disclosure attack against this protocol as well.

  * Publication date: 2019-07-25T22:17:36Z

  * Arxiv: http://arxiv.org/abs/1907.11322v1


* ### Secure and Transparent Audit Logs with BlockAudit by Ashar Ahmad, Muhammad Saad, Aziz Mohaisen

  * Abstract: Audit logs serve as a critical component in enterprise business systems and
are used for auditing, storing, and tracking changes made to the data. However,
audit logs are vulnerable to a series of attacks enabling adversaries to tamper
data and corresponding audit logs without getting detected. Among them, two
well-known attacks are the physical access attack, which exploits root
privileges, and the remote vulnerability attack, which compromises known
vulnerabilities in database systems. In this paper, we present BlockAudit: a
scalable and tamper-proof system that leverages the design properties of audit
logs and security guarantees of blockchain to enable secure and trustworthy
audit logs. Towards that, we construct the design schema of BlockAudit and
outline its functional and operational procedures. We implement our design on a
custom-built Practical Byzantine Fault Tolerance (PBFT) blockchain system and
evaluate the performance in terms of latency, network size, payload size, and
transaction rate. Our results show that conventional audit logs can seamlessly
transition into BlockAudit to achieve higher security and defend against the
known attacks on audit logs.

  * Publication date: 2019-07-21T00:23:29Z

  * Arxiv: http://arxiv.org/abs/1907.10484v1


* ### Greedy but Cautious: Conditions for Miner Convergence to Resource Allocation Equilibrium by George Bissias, Brian N. Levine, David Thibodeau

  * Abstract: All public blockchains are secured by a proof of opportunity cost among block
producers. For example, the security offered by proof-of-work (PoW) systems,
like Bitcoin, is due to spent computation; it is work precisely because it
cannot be performed for free. In general, more resources provably lost in
producing blocks yields more security for the blockchain. When two blockchains
share the same mechanism for providing opportunity cost, as is the case when
they share the same PoW algorithm, the two chains compete for resources from
block producers. Indeed, if there exists a liquid market between resource
types, then theoretically all blockchains will compete for resources. In this
paper, we show that there exists a resource allocation equilibrium between any
two blockchains, which is essentially driven by the fiat value of reward that
each chain offers in return for providing security. We go on to prove that this
equilibrium is singular and always achieved provided that block producers
behave in a greedy, but cautious fashion. The opposite is true when they are
overly greedy: resource allocation oscillates in extremes between the two
chains. We show that these results hold both in practice and in a block
generation simulation. Finally, we demonstrate several applications of this
theory including a trustless price-ratio oracle, increased security for
blockchains whose coins have lower fiat value, and a quantification of cost to
allocating resources away from the equilibrium.

  * Publication date: 2019-07-19T21:02:53Z

  * Arxiv: http://arxiv.org/abs/1907.09883v2


* ### Effcient logging and querying for Blockchain'based cross'site genomic dataset access audit by Shuaicheng Ma, Yang Cao, Li Xiong

  * Abstract: Background: Genomic data have been collected by different institutions and
companies and need to be shared for broader use. In a cross-site genomic data
sharing system, a secure and transparent access control audit module plays an
essential role in ensuring the accountability. The 2018 iDASH competition first
track provides us with an opportunity to design efficient logging and querying
system for cross-site genomic dataset access audit. We designed a
blockchain-based log system which can provide a light-weight and widely
compatible module for existing blockchain platforms. The submitted solution won
the third place of the competition. In this paper, we report the technical
details in our system. Methods: We present two methods: baseline method and
enhanced method. We started with the baseline method and then adjusted our
implementation based on the competition evaluation criteria and characteristics
of the log system. To overcome obstacles of indexing on the immutable
Blockchain system, we designed a hierarchical timestamp structure which
supports efficient range queries on the timestamp field. Results: We
implemented our methods in Python3, tested the scalability, and compared the
performance using the test data supplied by competition organizer. We
successfully boosted the log retrieval speed for complex AND queries that
contain multiple predicates. For the range query, we boosted the speed for at
least one order of magnitude. The storage usage is reduced by 25%. Conclusion:
We demonstrate that Blockchain can be used to build a time and space efficient
log and query genomic dataset audit trail. Therefore, it provides a promising
solution for sharing genomic data with accountability requirement across
multiple sites.

  * Publication date: 2019-07-17T02:11:53Z

  * Arxiv: http://arxiv.org/abs/1907.07303v2


* ### Catfish Effect Between Internal and External Attackers:Being Semi'honest is Helpful by Hanqing Liu, Na Ruan, Joseph K. Liu

  * Abstract: The consensus protocol named proof of work (PoW) is widely applied by
cryptocurrencies like Bitcoin. Although security of a PoW cryptocurrency is
always the top priority, it is threatened by mining attacks like selfish
mining. Researchers have proposed many mining attack models with one attacker,
and optimized the attacker's strategy. During these mining attacks, an attacker
pursues a higher relative revenue (RR) by wasting a large amount of
computational power of the honest miners at the cost of a small amount of
computational power of himself. In this paper, we propose a mining attack model
with two phases: the original system and the multi-attacker system. It is the
first model to provide both theoretical and quantitative analysis of mining
attacks with two attackers. We explain how the original system turns into the
multi-attacker system by introducing two attackers: the internal attacker and
the external attacker. If both attackers take the attacking strategy selfish
mining, the RR of the internal attacker in multi-attacker system will drop by
up to 31.9% compared with his RR in original system. The external attacker will
overestimate his RR by up to 44.6% in multiattacker system. Unexpected
competitions, auctions between attackers and overestimation of attackers'
influence factor are three main causes of both attackers' dropping RR. We
propose a mining strategy named Partial Initiative Release (PIR) which is a
semi-honest mining strategy in multi-attacker system. In some specific
situations, PIR allows the attacker to get more block reward by launching an
attack in multi-attacker system.

  * Publication date: 2019-06-19T11:25:22Z

  * Arxiv: http://arxiv.org/abs/1907.03720v1


* ### A multi'layered blockchain framework for smart mobility data'markets by David Lopez, Bilal Farooq

  * Abstract: Blockchain has the potential to render the transaction of information more
secure and transparent. Nowadays, transportation data are shared across
multiple entities using heterogeneous mediums, from paper collected data to
smartphone. Most of this data are stored in central servers that are
susceptible to hacks. In some cases shady actors who may have access to such
sources, share the mobility data with unwanted third parties. A multi-layered
Blockchain framework for Smart Mobility Data-market (BSMD) is presented for
addressing the associated privacy, security, management, and scalability
challenges. Each participant shares their encrypted data to the blockchain
network and can transact information with other participants as long as both
parties agree to the transaction rules issued by the owner of the data. Data
ownership, transparency, auditability and access control are the core
principles of the proposed blockchain for smart mobility data-market. In a case
study of real-time mobility data sharing, we demonstrate the performance of
BSMD on a 370 nodes blockchain running on heterogeneous and
geographically-separated devices communicating on a physical network. We also
demonstrate how BSMD ensures the cybersecurity and privacy of individual by
safeguarding against spoofing and message interception attacks and providing
information access management control.

  * Publication date: 2019-06-14T23:36:11Z

  * Arxiv: http://arxiv.org/abs/1906.06435v1


* ### Direct Acyclic Graph based Blockchain for Internet of Things: Performance and Security Analysis by Yixin Li, Bin Cao, Mugen Peng, Long Zhang, Lei Zhang, Daquan Feng, Jihong Yu

  * Abstract: Direct Acyclic Graph (DAG) based blockchain and the corresponding consensus
mechanism has been identified as a promising technology for Internet of Things
(IoT). Compared with Proof-of-Work (PoW) and Proof-of-Stake (PoS) that have
been widely used in the existing blockchains, the consensus mechanism designed
based on DAG architecture (simply called as DAG consensus) can overcome some
shortcomings such as high resource consumption, high transaction fee, low
transaction throughput and long confirmation delay. However, the theoretic
analysis on the DAG consensus is an untapped venue to be explored. To this end,
based on one of the most typical DAG consensuses, Tangle, we investigate the
impact of network load on the blockchain performance and security. Considering
unsteady network load, we first propose a Markov chain model to capture the
behavior of DAG consensus process under dynamic load conditions. The key
performance metrics, i.e., cumulative weight and confirmation delay are
analysed based on the proposed model. Then, we leverage a stochastic model to
analyse the probability of a successful double-spending attack in different
network load regimes. The results can provide insightful understanding of DAG
consensus process, e.g., how the network load affects the confirmation delay
and the probability of a successful attack. Meanwhile, we also demonstrate the
trade-off between security level and confirmation delay, which can act as a
guidance for practical deployment of DAG based blockchain systems.

  * Publication date: 2019-05-27T01:30:16Z

  * Arxiv: http://arxiv.org/abs/1905.10925v1


* ### Smart Contract Development in Practice: Trends, Issues, and Discussions on Stack Overflow by Afiya Ayman, Amna Aziz, Amin Alipour, Aron Laszka

  * Abstract: Blockchain based platforms are emerging as a transformative technology that
can provide reliability, integrity, and auditability without trusted entities.
One of the key features of these platforms is the trustworthy decentralized
execution of general-purpose computation in the form of smart contracts, which
are envisioned to have a wide range of applications from finance to the
Internet of Things. As a result, a rapidly growing and active community of
smart contract developers has emerged in recent years. A number of research
efforts have investigated the technological challenges that smart contract
developers face. However, very little is known about the community itself,
about the developers, and about the issues that they discuss and care about. To
address this gap, we study the online community of smart contract developers on
Stack Overflow. We provide insight into the topics that they discuss, their
technological and demographic background, and their awareness of security
issues and tools. Our results show that the community of smart contract
developers is very active and growing rapidly, in comparison with the general
user population. However, a large fraction of smart contract related questions
remain unanswered, which can pose a real threat to the viability of a
sustainable community and may indicate gaps in community knowledge. Further, we
observe very limited discussion of security related topics, which is concerning
since smart contracts in practice are plagued by security issues.

  * Publication date: 2019-05-15T19:46:37Z

  * Arxiv: http://arxiv.org/abs/1905.08833v1


* ### Domain Specific Code Smells in Smart Contracts by Jiachi Chen, Xin Xia, David Lo, John Grundy, Daniel Xiapu Luo, Ting Chen

  * Abstract: Smart contracts are programs running on a blockchain. They are immutable to
patch for bugs once deployed -- it is critical to ensure they are bug-free and
well-designed before deploying. Code smells are symptoms in source code that
possibly indicate deeper problems. The detection of code smells is a method to
avoid potential bugs and improve the design of existing code. However,
traditional code smell patterns are designed for centralized OO programs, e.g.,
Java or C++; while smart contracts are decentralized and contain numerous
distinctive features, such as the gas system. To fill this gap, we collected
smart-contract-related posts from Stack Exchange, as well as real-world smart
contracts. We manually analyzed these posts and defined 20 kinds of mph{code
smells for smart contracts. We categorized these into security, architecture,
and usability problems. To validate if practitioners consider these contract
smells as harmful, we created an online survey and received 96 responses from
24 different countries. Feedback showed these code smells are harmful and
removing them would improve quality and robustness of smart contracts. We
manually identified our defined code smells in 587 contract accounts and
publicly released our dataset. Finally, we summarized 5 impacts caused by
contract code smells. These help developers better understand the symptoms of
the smells and removal priority.

  * Publication date: 2019-05-04T09:58:49Z

  * Arxiv: http://arxiv.org/abs/1905.01467v1


* ### Discharged Payment Channels: Quantifying the Lightning Network's Resilience to Topology'Based Attacks by Elias Rohrer, Julian Malliaris, Florian Tschorsch

  * Abstract: The Lightning Network is the most widely used payment channel network (PCN)
to date, making it an attractive attack surface for adversaries. In this paper,
we analyze the Lightning Network's PCN topology and investigate its resilience
towards random failures and targeted attacks. In particular, we introduce the
notions of channel exhaustion and node isolation attacks and show that the
Lightning Network is susceptible to these attacks. In a preliminary analysis,
we confirm that the Lightning Network can be classified as a small-world and
scale-free network. Based on these findings, we develop a series of strategies
for targeted attacks and introduce metrics that allow us to quantify the
adversary's advantage. Our results indicate that an attacker who is able to
remove a certain number of nodes should follow a centrality-based strategy,
while a resource-limited attacker who aims for high efficiency should employ a
highest ranked minimum cut strategy.

  * Publication date: 2019-04-23T11:29:50Z

  * Arxiv: http://arxiv.org/abs/1904.10253v1


* ### Detecting brute'force attacks on cryptocurrency wallets by E. O. Kiktenko, M. A. Kudinov, A. K. Fedorov

  * Abstract: Blockchain is a distributed ledger, which is protected against malicious
modifications by means of cryptographic tools, e.g. digital signatures and hash
functions. One of the most prominent applications of blockchains is
cryptocurrencies, such as Bitcoin. In this work, we consider a particular
attack on wallets for collecting assets in a cryptocurrency network based on
brute-force search attacks. Using Bitcoin as an example, we demonstrate that if
the attack is implemented successfully, a legitimate user is able to prove that
fact of this attack with a high probability. We also consider two options for
modification of existing cryptocurrency protocols for dealing with this type of
attacks. First, we discuss a modification that requires introducing changes in
the Bitcoin protocol and allows diminishing the motivation to attack wallets.
Second, an alternative option is the construction of special smart-contracts,
which reward the users for providing evidence of the brute-force attack. The
execution of this smart-contract can work as an automatic alarm that the
employed cryptographic mechanisms, and (particularly) hash functions, have an
evident vulnerability.

  * Publication date: 2019-04-15T10:11:49Z

  * Arxiv: http://arxiv.org/abs/1904.06943v1


* ### An Efficient Blockchain'based Hierarchical Authentication Mechanism for Energy Trading in V2G Environment by Sahil Garg, Kuljeet Kaur, Georges Kaddoum, François Gagnon, Joel J. P. C. Rodrigues

  * Abstract: Vehicle-to-grid (V2G) networks have emerged as a new technology in modern
electric power transmission networks. It allows bi-directional flow of
communication and electricity between electric vehicles (EVs) and the Smart
Grid (SG), in order to provide more sophisticated energy trading. However, due
to the involvement of a huge amount of trading data and the presence of
untrusted entities in the visiting networks, the underlying V2G infrastructure
suffers from various security and privacy challenges. Although, several
solutions have been proposed in the literature to address these problems,
issues like lack of mutual authentication and anonymity, incapability to
protect against several attack vectors, generation of huge overhead, and
dependency on centralized infrastructures make security and privacy issues even
more challenging. To address the above mentioned problems, in this paper, we
propose a blockchain oriented hierarchical authentication mechanism for
rewarding EVs. The overall process is broadly classified into the following
phases: 1) System Initialization, 2) Registration, 3) Hierarchical Mutual
Authentication, and 4) Consensus; wherein blockchain's distributed ledger has
been employed for transaction execution in distributed V2G environments while
Elliptic curve cryptography (ECC) has been used for hierarchical
authentication. The designed hierarchical authentication mechanism has been
employed to preserve the anonymity of EVs and support mutual authentication
between EVs, charging stations (CSs) and the central aggregator (CAG).
Additionally, it also supports minimal communicational and computational
overheads on resource constrained EVs. Further, formal security verification of
the proposed scheme on widely accepted Automated Validation of Internet
Security Protocols and Applications (AVISPA) tool validates its safeness
against different security attacks.

  * Publication date: 2019-04-02T02:01:13Z

  * Arxiv: http://arxiv.org/abs/1904.01171v1


* ### Security and Privacy on Blockchain by Rui Zhang, Rui Xue, Ling Liu

  * Abstract: Blockchain offers an innovative approach to storing information, executing
transactions, performing functions, and establishing trust in an open
environment. Many consider blockchain as a technology breakthrough for
cryptography and cybersecurity, with use cases ranging from globally deployed
cryptocurrency systems like Bitcoin, to smart contracts, smart grids over the
Internet of Things, and so forth. Although blockchain has received growing
interests in both academia and industry in the recent years, the security and
privacy of blockchains continue to be at the center of the debate when
deploying blockchain in different applications. This paper presents a
comprehensive overview of the security and privacy of blockchain. To facilitate
the discussion, we first introduce the notion of blockchains and its utility in
the context of Bitcoin like online transactions. Then we describe the basic
security properties that are supported as the essential requirements and
building blocks for Bitcoin like cryptocurrency systems, followed by presenting
the additional security and privacy properties that are desired in many
blockchain applications. Finally, we review the security and privacy techniques
for achieving these security properties in blockchain-based systems, including
representative consensus algorithms, hash chained storage, mixing protocols,
anonymous signatures, non-interactive zero-knowledge proof, and so forth. We
conjecture that this survey can help readers to gain an in-depth understanding
of the security and privacy of blockchain with respect to concept, attributes,
techniques and systems.

  * Publication date: 2019-03-18T17:49:51Z

  * Arxiv: http://arxiv.org/abs/1903.07602v2


* ### A Novel Blockchain'based Trust Model for Cloud Identity Management by Keltoum Bendiab, Nicholas Kolokotronis, Stavros Shiaeles, Samia Boucherkha

  * Abstract: Secure and reliable management of identities has become one of the greatest
challenges facing cloud computing today, mainly due to the huge number of new
cloud-based applications generated by this model, which means more user
accounts, passwords, and personal information to provision, monitor, and
secure. Currently, identity federation is the most useful solution to overcome
the aforementioned issues and simplify the user experience by allowing
efficient authentication mechanisms and use of identity information from data
distributed across multiple domains. However, this approach creates
considerable complexity in managing trust relationships for both the cloud
service providers and their clients. Poor management of trust in federated
identity management systems brings with it many security, privacy and
interoperability issues, which contributes to the reluctance of organizations
to move their critical identity data to the cloud. In this paper, we aim to
address these issues by introducing a novel trust and identity management model
based on the Blockchain for cloud identity management with security and privacy
improvements.

  * Publication date: 2019-03-12T07:49:38Z

  * Arxiv: http://arxiv.org/abs/1903.04767v1


* ### A Taxonomy for Understanding the Security Technical Debts in Blockchain Based Systems by Sabreen Ahmadjee, Rami Bahsoon

  * Abstract: Blockchain is a disruptive technology intended at implementing secure
decentralized distributed systems, in which transactional data can be shared,
stored and verified by participants of a system using cryptographic and
consensus mechanisms, elevating the need for a central
authentication/verification authority. Contrary to the belief, blockchain-based
systems are not inherently secure by design; it is crucial for security
software engineers to be aware of the various blockchain specific architectural
design decisions and choices and their consequences on the dependability of the
software system. We argue that sub-optimal and ill-informed design decisions
and choices of blockchain components and their configurations including smart
contracts, key management, cryptographic and consensus mechanisms, on-chain vs.
off chain storage choices can introduce security technical debt into the
system. The technical debt metaphor can serve as a powerful tool for early,
preventive and transparent evaluation of the security design of
blockchain-based systems by making the potential security technical debt
visible to security software engineers. We review the core architectural
components of blockchain-based systems and we show how the ill-choice or
sub-optimal design decisions and configuration of these components can manifest
into security technical debt. We contribute to a taxonomy that classifies the
blockchain specific design decisions and choices and we describe their
connection to potential debts. The taxonomy can help architects of this
category of systems avoid potential security risks by visualising the security
technical debts and raising its visibility. We use examples from two case
studies to discuss the taxonomy and its application.

  * Publication date: 2019-03-08T08:36:45Z

  * Arxiv: http://arxiv.org/abs/1903.03323v1


* ### Profitable Double'Spending Attacks by Jehyuk Jang, Heung'No Lee

  * Abstract: Our aim in this paper is to investigate the profitability of double-spending
(DS) attacks that manipulate a priori mined transaction in a blockchain. Up to
date, it was understood that the requirement for successful DS attacks is to
occupy a higher proportion of computing power than a target network's
proportion; i.e., to occupy more than 51% proportion of computing power. On the
contrary, we show that DS attacks using less than 50% proportion of computing
power can also be vulnerable. Namely, DS attacks using any proportion of
computing power can occur as long as the chance to making a good profit is
there; i.e., revenue of an attack is greater than the cost of launching it. We
have novel probability theory based derivations for calculating time finite
attack probability. This can be used to size up the resource needed to
calculate the revenue and the cost. The results enable us to derive sufficient
and necessary conditions on the value of a target transaction which make DS
attacks for any proportion of computing power profitable. They can also be used
to assess the risk of one's transaction by checking whether or not the
transaction value satisfies the conditions for profitable DS attacks. Two
examples are provided in which we evaluate the attack resources and the
conditions for profitable DS attacks given 35% proportion of computing power
against Syscoin and BitcoinCash networks, and quantitatively shown how
vulnerable they are.

  * Publication date: 2019-03-05T07:44:41Z

  * Arxiv: http://arxiv.org/abs/1903.01711v2


* ### Cyber'Physical Simulation Platform for Security Assessment of Transactive Energy Systems by Yue Zhang, Scott Eisele, Abhishek Dubey, Aron Laszka, Anurag K. Srivastava

  * Abstract: Transactive energy systems (TES) are emerging as a transformative solution
for the problems that distribution system operators face due to an increase in
the use of distributed energy resources and rapid growth in scalability of
managing active distribution system (ADS). On the one hand, these changes pose
a decentralized power system control problem, requiring strategic control to
maintain reliability and resiliency for the community and for the utility. On
the other hand, they require robust financial markets while allowing
participation from diverse prosumers. To support the computing and flexibility
requirements of TES while preserving privacy and security, distributed software
platforms are required. In this paper, we enable the study and analysis of
security concerns by developing Transactive Energy Security Simulation Testbed
(TESST), a TES testbed for simulating various cyber attacks. In this work, the
testbed is used for TES simulation with centralized clearing market,
highlighting weaknesses in a centralized system. Additionally, we present a
blockchain enabled decentralized market solution supported by distributed
computing for TES, which on one hand can alleviate some of the problems that we
identify, but on the other hand, may introduce newer issues. Future study of
these differing paradigms is necessary and will continue as we develop our
security simulation testbed.

  * Publication date: 2019-03-04T20:12:42Z

  * Arxiv: http://arxiv.org/abs/1903.01520v1


* ### BlendMAS: A BLockchain'ENabled Decentralized Microservices Architecture for Smart Public Safety by Ronghua Xu, Seyed Yahya Nikouei, Yu Chen, Erik Blasch, Alex Aved

  * Abstract: Thanks to rapid technological advances in the Internet of Things (IoT), a
smart public safety (SPS) system has become feasible by integrating
heterogeneous computing devices to collaboratively provide public protection
services. While a service oriented architecture (SOA) has been adopted by IoT
and cyber-physical systems (CPS), it is difficult for a monolithic architecture
to provide scalable and extensible services for a distributed IoT based SPS
system. Furthermore, traditional security solutions rely on a centralized
authority, which can be a performance bottleneck or single point failure.
Inspired by microservices architecture and blockchain technology, this paper
proposes a BLockchain-ENabled Decentralized Microservices Architecture for
Smart public safety (BlendMAS). Within a permissioned blockchain network, a
microservices based security mechanism is introduced to secure data access
control in an SPS system. The functionality of security services are decoupled
into separate containerized microservices that are built using a smart
contract, and deployed on edge and fog computing nodes. An extensive
experimental study verified that the proposed BlendMAS is able to offer a
decentralized, scalable and secured data sharing and access control to
distributed IoT based SPS system.

  * Publication date: 2019-02-27T14:52:56Z

  * Arxiv: http://arxiv.org/abs/1902.10567v1


* ### Safe Artificial General Intelligence via Distributed Ledger Technology by Kristen W. Carlson

  * Abstract: Background. Expert observers and artificial intelligence (AI) progression
metrics indicate AI will exceed human intelligence within a few decades.
Whether general AI that exceeds human capabilities (AGI) will be the single
greatest boon in history or a disaster is unknown. No proofs exist that AGI
will benefit humans or that AGI will not harm or eliminate humans.
  Objective. I propose a set of logically distinct conceptual components that
are necessary and sufficient to 1) ensure that most known AGI scenarios will
not harm humanity and 2) robustly align AGI values and goals with human values.
  Methods. By systematically addressing each pathway category to malevolent AI
we can induce the methods/axioms required to redress the category.
  Results and Discussion. Distributed ledger technology (DLT, blockchain) is
integral to this proposal, e.g. to reduce the probability of hacking, provide
an audit trail to detect and correct errors or identify components causing
vulnerability or failure and replace them or shut them down remotely and/or
automatically, and to separate and balance key AGI components via decentralized
apps (dApps). Smart contracts based on DLT are necessary to address evolution
of AI that will be too fast for human monitoring and intervention.
  The proposed axioms. 1) Access to technology by market license. 2)
Transparent ethics embodied in DLT. 3) Morality encrypted via DLT. 4) Behavior
control structure with values (ethics) at roots. 5) Individual bar-code
identification of all critical components. 6) Configuration Item (from business
continuity/disaster recovery planning). 7) Identity verification secured via
DLT. 8) Smart automated contracts based on DLT. 9) Decentralized applications -
AI software code modules encrypted via DLT. 10) Audit trail of component usage
stored via DLT. 11) Social ostracism (denial of societal resources) augmented
by DLT petitions.

  * Publication date: 2019-02-11T00:10:47Z

  * Arxiv: http://arxiv.org/abs/1902.03689v2


* ### Blockchain Trilemma Solver Algorand has Dilemma over Undecidable Messages by Mauro Conti, Ankit Gangwal, Michele Todero

  * Abstract: Recently, an ingenious protocol called Algorand has been proposed to overcome
these limitations. Algorand uses an innovative process - called cryptographic
sortition - to securely and unpredictably elect a set of voters from the
network periodically. These voters are responsible for reaching consensus
through a Byzantine Agreement (BA) protocol on one block per time, guaranteeing
an overwhelming probability of linearity of the blockchain.
  In this paper, we present a security analysis of Algorand. To the best of our
knowledge, it is the first security analysis as well as the first formal study
on Algorand. We designed an attack scenario in which a group of malicious users
tries to break the protocol, or at least limiting it to a reduced partition of
network users, by exploiting a possible security flaw in the messages
validation process of the BA. Since the source code or an official simulator
for Algorand was not available at the time of our study, we created a simulator
(which is available on request) to implement the protocol and assess the
feasibility of our attack scenario. Our attack requires the attacker to have a
trivial capability of establishing multiple connections with targeted nodes and
costs practically nothing to the attacker. Our results show that it is possible
to slow down the message validation process on honest nodes, which eventually
forces them to choose default values on the consensus; leaving the targeted
nodes behind in the chain as compared to the non-attacked nodes. Even though
our results are subject to the real implementation assumption, the core concept
of our attack remains valid.

  * Publication date: 2019-01-28T22:28:07Z

  * Arxiv: http://arxiv.org/abs/1901.10019v1


* ### Smart contracts for the Internet of Things: opportunities and challenges by Nikos Fotiou, George C. Polyzos

  * Abstract: With the Internet of Things (IoT), Things are expected to live in different
domains and contexts during their lifetime. Information generated by and
associated with Things should be manageable by multiple, diverse stakeholders
accordingly. Moreover, the scope of the information related to Things can range
from private and confidential to public and auditable. Identification,
security, and interoperability in this vivid environment are expected to be
challenging. In this paper we discuss how smart contracts and blockchain
technologies create the potential for a viable solution. To this end, we
present smart contract-based solutions that improve security and information
management, we identify new opportunities and challenges, and we provide
security recommendations and guidelines.

  * Publication date: 2019-01-23T10:48:16Z

  * Arxiv: http://arxiv.org/abs/1901.10582v1


* ### RepChain: A Reputation based Secure, Fast and High Incentive Blockchain System via Sharding by Chenyu Huang, Zeyu Wang, Huangxun Chen, Qiwei Hu, Qian Zhang, Wei Wang, Xia Guan

  * Abstract: In today's blockchain system, designing a secure and high throughput on par
with centralized payment system is a difficulty task. Sharding is one of the
most worth expecting technologies to improve the system throughput when
maintain high security level. However, the previous works have two main
limitations: Firstly, the throughput of their random-based sharding system is
not high enough due to not leveraging the heterogeneity among validators.
Secondly, the incentive mechanism can be a huge overhead on their system
without an appropriate scheme. We propose RepChain, a reputation-based secure,
high incentive and fast blockchain system via sharding. RepChain utilizes
reputation to explicitly characterize the heterogeneity among the validators
and lay the foundation for the incentive mechanism. We novelly propose the
double-chain architecture that including transaction chain and reputation
chain. For transaction chain, a Raft-based Byzantine fault tolerant synchronous
consensus with high resiliency and high throughput has been presented. For
reputation chain, the collective signing has been utilized to achieve consensus
on the reputation score and support the high throughput transaction chain with
moderate generation speed. Moreover, we propose a reputation based sharding and
leader selection scheme. To analyze the security of RepChain, we propose a
recursive formula to calculate the epoch security within only O(km^2) time.
Further more, we implement and evaluate RepChain on Amazon Web Service
platform. The results show our solution can enhance both throughout and
security level of the existing sharding-based blockchain system.

  * Publication date: 2019-01-17T11:49:31Z

  * Arxiv: http://arxiv.org/abs/1901.05741v1


* ### Incentive'based integration of useful work into blockchains by David Amar, Lior Zilpa

  * Abstract: Blockchains have recently gained popularity thanks to their ability to record
digital truth. They are designed to keep persistence, security, and avoid
attacks which is useful for many applications. However, they are still
problematic in their energy consumption, governance, and scalability Current
solutions either require vast computing power via Proof-of-Work (PoW) or cannot
directly utilize computing power as a resource in virtual mining. Here, we
propose incentive-based protocols that use competitions to integrate computing
power into blockchains. We introduce Proof-of-Accumulated-Work (PoAW): miners
compete in costumer-submitted jobs, accumulate recorded work whenever they are
successful, and, over time, are remunerated. The underlying competition
replaces the standard hash puzzle-based competitions of PoW. A competition is
managed by a dynamically-created small masternode network (dTMN) of invested
miners. dTMNs allow for scalability as we do not need the entire network to
manage the competition. Using careful design on incentives, our system
preserves security, avoids attacks, and offers new markets to miners. When
there are no costumers the system converges into a standard protocol. Our
proposed solution improves the way by which the blockchain infrastructure works
and makes use of its computing power. We also discuss how the protocol can be
used by fields that require solving difficult optimization problems, such as
Artificial Intelligence and Pattern Recognition in Big Data.

  * Publication date: 2019-01-10T20:34:48Z

  * Arxiv: http://arxiv.org/abs/1901.03375v1


* ### On the Activity Privacy of Blockchain for IoT by Ali Dorri, Clemence Roulin, Raja Jurdak, Salil Kanhere

  * Abstract: Security is one of the fundamental challenges in the Internet of Things (IoT)
due to the heterogeneity and resource constraints of the IoT devices. Device
classification methods are employed to enhance the security of IoT by detecting
unregistered devices or traffic patterns. In recent years, blockchain has
received tremendous attention as a distributed trustless platform to enhance
the security of IoT. Conventional device identification methods are not
directly applicable in blockchain-based IoT as network layer packets are not
stored in the blockchain. Moreover, the transactions are broadcast and thus
have no destination IP address and contain a public key as the user identity,
and are stored permanently in blockchain which can be read by any entity in the
network. We show that device identification in blockchain introduces privacy
risks as the malicious nodes can identify users' activity pattern by analyzing
the temporal pattern of their transactions in the blockchain. We study the
likelihood of classifying IoT devices by analyzing their information stored in
the blockchain, which to the best of our knowledge, is the first work of its
kind. We use a smart home as a representative IoT scenario. First, a blockchain
is populated according to a real-world smart home traffic dataset. We then
apply machine learning algorithms on the data stored in the blockchain to
analyze the success rate of device classification, modeling both an informed
and a blind attacker. Our results demonstrate success rates over 90\% in
classifying devices. We propose three timestamp obfuscation methods, namely
combining multiple packets into a single transaction, merging ledgers of
multiple devices, and randomly delaying transactions, to reduce the success
rate in classifying devices. The proposed timestamp obfuscation methods can
reduce the classification success rates to as low as 20%.

  * Publication date: 2018-12-21T06:46:20Z

  * Arxiv: http://arxiv.org/abs/1812.08970v2


* ### Blockchain Enabled Trustless API Marketplace by Vijay Arya, Sayandeep Sen, Palani Kodeswaran

  * Abstract: There has been an unprecedented surge in the number of service providers
offering a wide range of machine learning prediction APIs for tasks such as
image classification, language translation, etc. thereby monetizing the
underlying data and trained models. Typically, a data owner (API provider)
develops a model, often over proprietary data, and leverages the infrastructure
services of a cloud vendor for hosting and serving API requests. Clearly, this
model assumes complete trust between the API Provider and cloud vendor. On the
other hand, a malicious/buggy cloud vendor may copy the APIs and offer an
identical service, under-report model usage metrics, or unfairly discriminate
between different API providers by offering them a nominal share of the
revenue. In this work, we present the design of a blockchain based
decentralized trustless API marketplace that enables all the stakeholders in
the API ecosystem to audit the behavior of the parties without having to trust
a single centralized entity. In particular, our system divides an AI model into
multiple pieces and deploys them among multiple cloud vendors who then
collaboratively execute the APIs. Our design ensures that cloud vendors cannot
collude with each other to steal the combined model, while individual cloud
vendors and clients cannot repudiate their input or model executions.

  * Publication date: 2018-12-05T18:45:29Z

  * Arxiv: http://arxiv.org/abs/1812.02154v1


* ### Research on the Security of Blockchain Data: A Survey by Liehuang Zhu, Baokun Zheng, Meng Shen, Shui Yu, Feng Gao, Hongyu Li, Kexin Shi, Keke Gai

  * Abstract: With the more and more extensive application of blockchain, blockchain
security has been widely concerned by the society and deeply studied by
scholars. Moreover, the security of blockchain data directly affects the
security of various applications of blockchain. In this survey, we perform a
comprehensive classification and summary of the security of blockchain data.
First, we present classification of blockchain data attacks. Subsequently, we
present the attacks and defenses of blockchain data in terms of privacy,
availability, integrity and controllability. Data privacy attacks present data
leakage or data obtained by attackers through analysis. Data availability
attacks present abnormal or incorrect access to blockchain data. Data integrity
attacks present blockchain data being tampered. Data controllability attacks
present blockchain data accidentally manipulated by smart contract
vulnerability. Finally, we present several important open research directions
to identify follow-up studies in this area.

  * Publication date: 2018-12-05T14:09:25Z

  * Arxiv: http://arxiv.org/abs/1812.02009v2


* ### Blockchain based secure data handover scheme in non'orthogonal multiple access by Anik Islam, Mohammed Belal Uddin, Md. Fazlul Kader, Soo Young Shin

  * Abstract: Non-orthogonal multiple access (NOMA) with successive interference
cancellation receiver is considered as one of the most potent multiple access
techniques to be adopted in future wireless communication networks. Data
security in the NOMA transmission scheme is on much attention drawing issue.
Blockchain is a distributed peer-to-peer network enables a way of protecting
information from unauthorized access, tempering etc. By utilizing encryption
techniques of blockchain, a secured data communication scheme using blockchain
in NOMA is proposed in this paper. A two-phase encryption technique with key
generation using different parameter is proposed. In the first-phase data is
encrypted by imposing users' public key and in the second phase, a private key
of the base station (BS) is engaged for encryption. Finally, the superiority of
the proposed scheme over existing scheme is proven through a comparative study
based on the different features.

  * Publication date: 2018-12-04T01:15:27Z

  * Arxiv: http://arxiv.org/abs/1812.01156v1


* ### Sapiens Chain: A Blockchain'based Cybersecurity Framework by Yu Han, Zhongru Wang, Qiang Ruan, Binxing Fang

  * Abstract: Recently, cybersecurity becomes more and more important due to the rapid
development of Internet. However, existing methods are in reality highly
sensitive to attacks and are far more vulnerable than expected, as they are
lack of trustable measures. In this paper, to address the aforementioned
problems, we propose a blockchain-based cybersecurity framework, termed as
Sapiens Chain, which can protect the privacy of the anonymous users and ensure
that the transactions are immutable by providing decentralized and trustable
services. Integrating semantic analysis, symbolic execution, and routing
learning methods into intelligent auditing, this framework can achieve good
accuracy for detecting hidden vulnerabilities. In addition, a revenue incentive
mechanism, which aims to donate participants, is built. The practical results
demonstrate the effectiveness of the proposed framework.

  * Publication date: 2018-11-27T08:27:49Z

  * Arxiv: http://arxiv.org/abs/1811.10868v1


* ### Research on CRO's Dilemma In Sapiens Chain: A Game Theory Method by Jinyu Shi, Zhongru Wang, Qiang Ruan, Yue Wu, Binxing Fang

  * Abstract: In recent years, blockchain-based techniques have been widely used in
cybersecurity, owing to the decentralization, anonymity, credibility and not be
tampered properties of the blockchain. As one of the decentralized framework,
Sapiens Chain was proposed to protect cybersecurity by scheduling the
computational resources dynamically, which were owned by Computational
Resources Owners (CROs). However, when CROs in the same pool attack each other,
all CROs will earn less. In this paper, we tackle the problem of prisoner's
dilemma from the perspective of CROs. We first define a game that a CRO
infiltrates another pool and perform an attack. In such game, the honest CRO
can control the payoffs and increase its revenue. By simulating this game, we
propose to apply Zero Determinant (ZD) strategy on strategy decision, which can
be categorized into cooperation and defecting. Our experimental results
demonstrate the effectiveness of the proposed strategy decision method.

  * Publication date: 2018-11-27T07:59:12Z

  * Arxiv: http://arxiv.org/abs/1811.10857v1


* ### Countering Selfish Mining in Blockchains by Muhammad Saad, Laurent Njilla, Charles Kamhoua, Aziz Mohaisen

  * Abstract: Selfish mining is a well known vulnerability in blockchains exploited by
miners to steal block rewards. In this paper, we explore a new form of selfish
mining attack that guarantees high rewards with low cost. We show the
feasibility of this attack facilitated by recent developments in blockchain
technology opening new attack avenues. By outlining the limitations of existing
countermeasures, we highlight a need for new defense strategies to counter this
attack, and leverage key system parameters in blockchain applications to
propose an algorithm that enforces fair mining. We use the expected transaction
confirmation height and block publishing height to detect selfish mining
behavior and develop a network-wide defense mechanism to disincentivize selfish
miners. Our design involves a simple modifications to transactions' data
structure in order to obtain a truth state used to catch the selfish miners
and prevent honest miners from losing block rewards.

  * Publication date: 2018-11-25T04:42:22Z

  * Arxiv: http://arxiv.org/abs/1811.09943v2


* ### All roads lead to Rome: Many ways to double spend your cryptocurrency by Zhiniang Peng, Yuki Chen

  * Abstract: In 2008, Satoshi Nakamoto proposed an electronic cash system (bitcoin) that
is completely realized by peer-to-peer technology. The core value of this
scheme is that it proposes a solution based on Proof-of Work, so that the cash
system can run in a peer-to-peer environment and be able to prevent
double-spend attacks. Bitcoin has been developed for ten years, and since then
countless digital currencies have been created. But the discussion of
double-spend attacks seems to still concentrate on 51% Attacks. In fact, our
research has found that there are many other way to achieve double-spend
attacks. In this paper, by introducing a number of double-spend attack
vulnerabilities that we have found in EOS, NEO and other large blockchain
platforms, we summarized various reasons for causing double-spend attacks, and
propose an efficient mitigation measure against them.

  * Publication date: 2018-11-16T11:02:56Z

  * Arxiv: http://arxiv.org/abs/1811.06751v1


* ### Blockchain'based Firmware Update Scheme Tailored for Autonomous Vehicles by Mohamed Baza, Mahmoud Nabil, Noureddine Lasla, Kemal Fidan, Mohamed Mahmoud, Mohamed Abdallah

  * Abstract: Recently, Autonomous Vehicles (AVs) have gained extensive attention from both
academia and industry. AVs are a complex system composed of many subsystems,
making them a typical target for attackers. Therefore, the firmware of the
different subsystems needs to be updated to the latest version by the
manufacturer to fix bugs and introduce new features, e.g., using security
patches. In this paper, we propose a distributed firmware update scheme for the
AVs' subsystems, leveraging blockchain and smart contract technology. A
consortium blockchain made of different AVs manufacturers is used to ensure the
authenticity and integrity of firmware updates. Instead of depending on
centralized third parties to distribute the new updates, we enable AVs, namely
distributors, to participate in the distribution process and we take advantage
of their mobility to guarantee high availability and fast delivery of the
updates. To incentivize AVs to distribute the updates, a reward system is
established that maintains a credit reputation for each distributor account in
the blockchain. A zero-knowledge proof protocol is used to exchange the update
in return for a proof of distribution in a trust-less environment. Moreover, we
use attribute-based encryption (ABE) scheme to ensure that only authorized AVs
will be able to download and use a new update. Our analysis indicates that the
additional cryptography primitives and exchanged transactions do not affect the
operation of the AVs network. Also, our security analysis demonstrates that our
scheme is efficient and secure against different attacks.

  * Publication date: 2018-11-14T16:58:25Z

  * Arxiv: http://arxiv.org/abs/1811.05905v1


* ### Rationality'proof consensus: extended abstract by Jean'Philippe Martin, Eunjin, Jung

  * Abstract: Blockchain systems benefit from lessons in prior art such as fault tolerance,
distributed systems, peer-to-peer systems, and game theory. In this paper we
argue that blockchain algorithms should tolerate both rational
(self-interested) users and Byzantine (malicious) ones, rather than assuming
all non-Byzantine users are altruistic and follow the protocols blindly. Such
algorithms are called BAR-tolerant [1]. To design a BAR-tolerant system, one
can follow these three steps: clearly define the utility function for the
rational users, prove the algorithm is such that there is no benefit from
unilaterally deviating (that is, it's a Byzantine Nash Equilibrium), then prove
the algorithm correct assuming the rational actors follow the protocol. We
present an example attack by rational users: the gatekeeping attack, where
members of a system selfishly decide to prevent newcomers from joining. This
attack may affect any stake-based system where the existing members prevent
newcomers from making a stake, and essentially form a cartel. We then sketch a
BAR-tolerant consensus protocol for blockchain that can defend against this
attack. It relies on a strict order to decide who gets to propose a new block
(so there's no need to race to solve a crypto puzzle) and it relies on hardware
ID tokens to make sure every computer is only represented at most once as a
block proposer to mitigate Sybil attacks. It also defends against the
gatekeeper attack. The BAR-tolerant approach is naturally also applicable to
other blockchain algorithms.

  * Publication date: 2018-11-02T05:21:34Z

  * Arxiv: http://arxiv.org/abs/1811.00742v1


* ### Quantum Advantage and Y2K Bug: Comparison by Lei Zhang, Andriy Miranskyy, Walid Rjaibi

  * Abstract: Quantum Computers (QCs), once they mature, will be able to solve someproblems faster than Classic Computers. This phenomenon is called quantumadvantage (or a stronger term quantum supremacy).  Quantum advantage will help us to speed up computations in many areas, fromartificial intelligence to medicine. However, QC power can also be leveraged tobreak modern cryptographic algorithms, which pervade modern software: use casesrange from encryption of Internet traffic, to encryption of disks, to signingblockchain ledgers.  While the exact date when QCs will evolve to reach quantum advantage isunknown, the consensus is that this future is near. Thus, in order to maintaincrypto agility of the software, one needs to start preparing for the era ofquantum advantage proactively.  In this paper, we recap the effect of quantum advantage on the existing andnew software systems, as well as the data that we currently store. We alsohighlight similarities and differences between the security challenges broughtby QCs and the challenges that software engineers faced twenty years ago whilefixing widespread Y2K bug. Technically, the Y2K bug and the quantum advantageproblems are different: the former was caused by timing-related problems, whilethe latter is caused by a cryptographic algorithm being non-quantum-resistant.However, conceptually, the problems are similar: we know what the root causeis, the fix (strategically) is straightforward, yet the implementation of thefix is challenging.  To address the quantum advantage challenge, we create a seven-step roadmap,deemed 7E. It is inspired by the lessons-learnt from the Y2K era amalgamatedwith modern knowledge. The roadmap gives developers a structured way to startpreparing for the quantum advantage era, helping them to start planning for thecreation of new as well as the evolution of the existent software.

  * Publication date: 2019-07-24T14:00:07Z

  * Arxiv: http://arxiv.org/abs/1907.10454v1


* ### Secure and Efficiently Searchable IoT Communication Data Management Model: Using Blockchain as a new tool by Ziqing Guo, Hua Zhang, Xin Zhang, Zhengping Jin, Qiaoyan Wen

  * Abstract: With the rapid development of the Internet of things (IoT), more and more IoTdevices are connected and communicate frequently. In this background, thetraditional centralized security architecture of IoT will be limited in termsof data storage space, data reliability, scalability, operating costs andliability judgment. In this paper, we propose an new key information storageframework based on a small distributed database generated by blockchaintechnology and cloud storage. Specifically, all encrypted key communicationdata will be upload to public could server for enough storage, but theabstracts of these data (called communication logs) will be recorded in IoTledger (i.e., an distributed database) that maintained by all IoT devicesaccording to the blockchain generation approach, which could solve the problemof data reliability, scalability and liability judgment. Besides, in order toefficiently search communication logs and not reveal any sensitive informationof communication data, we design the secure search scheme for our IoT ledger,which exploits the Asymmetric Scalar-product Preserving Encryption (ASPE)approach to guarantee the data security, and exploits the 2-layers index whichis tailor-made for blockchain database to improve the search efficiency.Security analysis and experiments on synthetic dataset show that our schemesare secure and efficient.

  * Publication date: 2018-12-20T14:37:55Z

  * Arxiv: http://arxiv.org/abs/1812.08603v1


