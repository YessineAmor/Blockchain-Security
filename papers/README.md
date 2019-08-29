# Papers List

* ### [Ethereum papers](ethereum/)

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


