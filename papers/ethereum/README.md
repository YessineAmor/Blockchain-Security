
# Papers List
* ### Eclipsing Ethereum Peers with False Friends by Sebastian Henningsen, Daniel Teunis, Martin Florian, Björn Scheuermann

  * Abstract: Ethereum is a decentralized Blockchain system that supports the execution of
Turing-complete smart contracts. Although the security of the Ethereum
ecosystem has been studied in the past, the network layer has been mostly
neglected. We show that Go Ethereum (Geth), the most widely used Ethereum
implementation, is vulnerable to eclipse attacks, effectively circumventing
recently introduced (Geth v1.8.0) security enhancements. We responsibly
disclosed the vulnerability to core Ethereum developers; the corresponding
countermeasures to our attack where incorporated into the v1.9.0 release of
Geth. Our false friends attack exploits the Kademlia-inspired peer discovery
logic used by Geth and enables a low-resource eclipsing of long-running, remote
victim nodes. An adversary only needs two hosts in distinct /24 subnets to
launch the eclipse, which can then be leveraged to filter the victim's view of
the Blockchain. We discuss fundamental properties of Geth's node discovery
logic that enable the false friends attack, as well as proposed and implemented
countermeasures.

  * Publication date: 2019-08-27T11:36:14Z

  * Arxiv: http://arxiv.org/abs/1908.10141v1


* ### Security Analysis Methods on Ethereum Smart Contract Vulnerabilities: A  Survey by Purathani Praitheeshan, Lei Pan, Jiangshan Yu, Joseph Liu, Robin Doss

  * Abstract: Smart contracts are software programs featuring both traditional applications
and distributed data storage on blockchains. Ethereum is a prominent blockchain
platform with the support of smart contracts. The smart contracts act as
autonomous agents in critical decentralized applications and hold a significant
amount of cryptocurrency to perform trusted transactions and agreements.
Millions of dollars as part of the assets held by the smart contracts were
stolen or frozen through the notorious attacks just between 2016 and 2018, such
as the DAO attack, Parity Multi-Sig Wallet attack, and the integer
underflow/overflow attacks. These attacks were caused by a combination of
technical flaws in designing and implementing software codes. However, many
more vulnerabilities of less severity are to be discovered because of the
scripting natures of the Solidity language and the non-updateable feature of
blockchains. Hence, we surveyed 16 security vulnerabilities in smart contract
programs, and some vulnerabilities do not have a proper solution. This survey
aims to identify the key vulnerabilities in smart contracts on Ethereum in the
perspectives of their internal mechanisms and software security
vulnerabilities. By correlating 16 Ethereum vulnerabilities and 19 software
security issues, we predict that many attacks are yet to be exploited. And we
have explored many software tools to detect the security vulnerabilities of
smart contracts in terms of static analysis, dynamic analysis, and formal
verification. This survey presents the security problems in smart contracts
together with the available analysis tools and the detection methods. We also
investigated the limitations of the tools or analysis methods with respect to
the identified security vulnerabilities of the smart contracts.

  * Publication date: 2019-08-22T21:43:02Z

  * Arxiv: http://arxiv.org/abs/1908.08605v1


* ### A Survey on Ethereum Systems Security: Vulnerabilities, Attacks and  Defenses by Huashan Chen, Marcus Pendleton, Laurent Njilla, Shouhuai Xu

  * Abstract: The blockchain technology is believed by many to be a game changer in many
application domains, especially financial applications. While the first
generation of blockchain technology (i.e., Blockchain 1.0) is almost
exclusively used for cryptocurrency purposes, the second generation (i.e.,
Blockchain 2.0), as represented by Ethereum, is an open and decentralized
platform enabling a new paradigm of computing --- Decentralized Applications
(DApps) running on top of blockchains. The rich applications and semantics of
DApps inevitably introduce many security vulnerabilities, which have no
counterparts in pure cryptocurrency systems like Bitcoin. Since Ethereum is a
new, yet complex, system, it is imperative to have a systematic and
comprehensive understanding on its security from a holistic perspective, which
is unavailable. To the best of our knowledge, the present survey, which can
also be used as a tutorial, fills this void. In particular, we systematize
three aspects of Ethereum systems security: vulnerabilities, attacks, and
defenses. We draw insights into, among other things, vulnerability root causes,
attack consequences, and defense capabilities, which shed light on future
research directions.

  * Publication date: 2019-08-13T06:15:41Z

  * Arxiv: http://arxiv.org/abs/1908.04507v1


* ### Selfish Mining in Ethereum by Cyril Grunspan, Ricardo Pérez'Marco

  * Abstract: We study selfish mining in Ethereum. The problem is combinatorially more
complex than in Bitcoin because of major differences in the reward system and a
different difficulty adjustment formula. Equivalent strategies in Bitcoin do
have different profitabilities in Ethereum. The attacker can either broadcast
his fork one block by one, or keep them secret as long as possible and publish
them all at once at the end of an attack cycle. The first strategy is damaging
for substantial hashrates, and we show that the second strategy is even worse.
This confirms what we already proved for Bitcoin: Selfish mining is most of all
an attack on the difficulty adjustment formula. We show that the current reward
for signaling uncle blocks is a weak incentive for the attacker to signal
blocks. We compute the profitabilities of different strategies and find out
that for a large parameter space values, strategies that do not signal blocks
are the best ones. We compute closed-form formulas for the apparent hashrates
for these strategies and compare them. We use a direct combinatorics analysis
with Dyck words to find these closed-form formulas.

  * Publication date: 2019-04-30T15:47:20Z

  * Arxiv: http://arxiv.org/abs/1904.13330v1


* ### Towards a First Step to Understand the Cryptocurrency Stealing Attack on  Ethereum by Zhen Cheng, Xinrui Hou, Runhuai Li, Yajin Zhou, Xiapu Luo, Jinku Li, Kui Ren

  * Abstract: We performed the first systematic study of a new attack on Ethereum that
steals cryptocurrencies. The attack is due to the unprotected JSON-RPC
endpoints existed in Ethereum nodes that could be exploited by attackers to
transfer the Ether and ERC20 tokens to attackers-controlled accounts. This
study aims to shed light on the attack, including malicious behaviors and
profits of attackers. Specifically, we first designed and implemented a
honeypot that could capture real attacks in the wild. We then deployed the
honeypot and reported results of the collected data in a period of six months.
In total, our system captured more than 308 million requests from 1,072
distinct IP addresses. We further grouped attackers into 36 groups with 59
distinct Ethereum accounts. Among them, attackers of 34 groups were stealing
the Ether, while other 2 groups were targeting ERC20 tokens. The further
behavior analysis showed that attackers were following a three-steps pattern to
steal the Ether. Moreover, we observed an interesting type of transaction
called zero gas transaction, which has been leveraged by attackers to steal
ERC20 tokens. At last, we estimated the overall profits of attackers. To engage
the whole community, the dataset of captured attacks is released on
https://github.com/zjuicsr/eth-honey.

  * Publication date: 2019-04-03T12:48:29Z

  * Arxiv: http://arxiv.org/abs/1904.01981v2


* ### The Art of The Scam: Demystifying Honeypots in Ethereum Smart Contracts by Christof Ferreira Torres, Mathis Steichen, Radu State

  * Abstract: Modern blockchains, such as Ethereum, enable the execution of so-called smart
contracts - programs that are executed across a decentralised network of nodes.
As smart contracts become more popular and carry more value, they become more
of an interesting target for attackers. In the past few years, several smart
contracts have been exploited by attackers. However, a new trend towards a more
proactive approach seems to be on the rise, where attackers do not search for
vulnerable contracts anymore. Instead, they try to lure their victims into
traps by deploying seemingly vulnerable contracts that contain hidden traps.
This new type of contracts is commonly referred to as honeypots. In this paper,
we present the first systematic analysis of honeypot smart contracts, by
investigating their prevalence, behaviour and impact on the Ethereum
blockchain. We develop a taxonomy of honeypot techniques and use this to build
HoneyBadger - a tool that employs symbolic execution and well defined
heuristics to expose honeypots. We perform a large-scale analysis on more than
2 million smart contracts and show that our tool not only achieves high
precision, but is also highly efficient. We identify 690 honeypot smart
contracts as well as 240 victims in the wild, with an accumulated profit of
more than ,000 for the honeypot creators. Our manual validation shows that
87% of the reported contracts are indeed honeypots.

  * Publication date: 2019-02-19T09:56:31Z

  * Arxiv: http://arxiv.org/abs/1902.06976v2


* ### Hunting the Ethereum Smart Contract: Color'inspired Inspection of  Potential Attacks by TonTon Hsien'De Huang

  * Abstract: Blockchain and Cryptocurrencies are gaining unprecedented popularity and
understanding. Meanwhile, Ethereum is gaining a significant popularity in the
blockchain community, mainly due to the fact that it is designed in a way that
enables developers to write smart contract and decentralized applications
(Dapps). This new paradigm of applications opens the door to many possibilities
and opportunities. However, the security of Ethereum smart contracts has not
received much attention; several Ethereum smart contracts malfunctioning have
recently been reported. Unlike many previous works that have applied static and
dynamic analyses to find bugs in smart contracts, we do not attempt to define
and extract any features; instead we focus on reducing the expert's labor
costs. We first present a new in-depth analysis of potential attacks
methodology and then translate the bytecode of solidity into RGB color code.
After that, we transform them to a fixed-sized encoded image. Finally, the
encoded image is fed to convolutional neural network (CNN) for automatic
feature extraction and learning, detecting compiler bugs of Ethereum smart
contract.

  * Publication date: 2018-07-05T07:06:36Z

  * Arxiv: http://arxiv.org/abs/1807.01868v1


* ### Double'Spending Risk Quantification in Private, Consortium and Public  Ethereum Blockchains by Parinya Ekparinya, Vincent Gramoli, Guillaume Jourjon

  * Abstract: Recently, several works conjectured the vulnerabilities of mainstream
blockchains under several network attacks. All these attacks translate into
showing that the assumptions of these blockchains can be violated in theory or
under simulation at best. Unfortunately, previous results typically omit both
the nature of the network under which the blockchain code runs and whether
blockchains are private, consortium or public. In this paper, we study the
public Ethereum blockchain as well as a consortium and private blockchains and
quantify the feasibility of man-in-the-middle and double spending attacks
against them. To this end, we list important properties of the Ethereum public
blockchain topology, we deploy VMs with constrained CPU quantum to mimic the
top-10 mining pools of Ethereum and we develop full-fledged attacks, that first
partition the network through BGP hijacking or ARP spoofing before issuing a
Balance Attack to steal coins. Our results demonstrate that attacking Ethereum
is remarkably devastating in a consortium or private context as the adversary
can multiply her digital assets by 200, 000x in 10 hours through BGP hijacking
whereas it would be almost impossible in a public context.

  * Publication date: 2018-05-14T03:53:25Z

  * Arxiv: http://arxiv.org/abs/1805.05004v1


* ### A Semantic Framework for the Security Analysis of Ethereum smart  contracts by Ilya Grishchenko, Matteo Maffei, Clara Schneidewind

  * Abstract: Smart contracts are programs running on cryptocurrency (e.g., Ethereum)
blockchains, whose popularity stem from the possibility to perform financial
transactions, such as payments and auctions, in a distributed environment
without need for any trusted third party. Given their financial nature, bugs or
vulnerabilities in these programs may lead to catastrophic consequences, as
witnessed by recent attacks. Unfortunately, programming smart contracts is a
delicate task that requires strong expertise: Ethereum smart contracts are
written in Solidity, a dedicated language resembling JavaScript, and shipped
over the blockchain in the EVM bytecode format. In order to rigorously verify
the security of smart contracts, it is of paramount importance to formalize
their semantics as well as the security properties of interest, in particular
at the level of the bytecode being executed.
  In this paper, we present the first complete small-step semantics of EVM
bytecode, which we formalize in the F* proof assistant, obtaining executable
code that we successfully validate against the official Ethereum test suite.
Furthermore, we formally define for the first time a number of central security
properties for smart contracts, such as call integrity, atomicity, and
independence from miner controlled parameters. This formalization relies on a
combination of hyper- and safety properties. Along this work, we identified
various mistakes and imprecisions in existing semantics and verification tools
for Ethereum smart contracts, thereby demonstrating once more the importance of
rigorous semantic foundations for the design of security verification
techniques.

  * Publication date: 2018-02-23T17:56:37Z

  * Arxiv: http://arxiv.org/abs/1802.08660v2


* ### An Adaptive Gas Cost Mechanism for Ethereum to Defend Against  Under'Priced DoS Attacks by Ting Chen, Xiaoqi Li, Ying Wang, Jiachi Chen, Zihao Li, Xiapu Luo, Man Ho Au, Xiaosong Zhang

  * Abstract: The gas mechanism in Ethereum charges the execution of every operation to
ensure that smart contracts running in EVM (Ethereum Virtual Machine) will be
eventually terminated. Failing to properly set the gas costs of EVM operations
allows attackers to launch DoS attacks on Ethereum. Although Ethereum recently
adjusted the gas costs of EVM operations to defend against known DoS attacks,
it remains unknown whether the new setting is proper and how to configure it to
defend against unknown DoS attacks. In this paper, we make the first step to
address this challenging issue by first proposing an emulation-based framework
to automatically measure the resource consumptions of EVM operations. The
results reveal that Ethereum's new setting is still not proper. Moreover, we
obtain an insight that there may always exist exploitable under-priced
operations if the cost is fixed. Hence, we propose a novel gas cost mechanism,
which dynamically adjusts the costs of EVM operations according to the number
of executions, to thwart DoS attacks. This method punishes the operations that
are executed much more frequently than before and lead to high gas costs. To
make our solution flexible and secure and avoid frequent update of Ethereum
client, we design a special smart contract that collaborates with the updated
EVM for dynamic parameter adjustment. Experimental results demonstrate that our
method can effectively thwart both known and unknown DoS attacks with flexible
parameter settings. Moreover, our method only introduces negligible additional
gas consumption for benign users.

  * Publication date: 2017-12-18T14:57:11Z

  * Arxiv: http://arxiv.org/abs/1712.06438v1


* ### Designing Secure Ethereum Smart Contracts: A Finite State Machine Based  Approach by Anastasia Mavridou, Aron Laszka

  * Abstract: The adoption of blockchain-based distributed computation platforms is growing
fast. Some of these platforms, such as Ethereum, provide support for
implementing smart contracts, which are envisioned to have novel applications
in a broad range of areas, including finance and Internet-of-Things. However, a
significant number of smart contracts deployed in practice suffer from security
vulnerabilities, which enable malicious users to steal assets from a contract
or to cause damage. Vulnerabilities present a serious issue since contracts may
handle financial assets of considerable value, and contract bugs are
non-fixable by design. To help developers create more secure smart contracts,
we introduce FSolidM, a framework rooted in rigorous semantics for designing
con- tracts as Finite State Machines (FSM). We present a tool for creating FSM
on an easy-to-use graphical interface and for automatically generating Ethereum
contracts. Further, we introduce a set of design patterns, which we implement
as plugins that developers can easily add to their contracts to enhance
security and functionality.

  * Publication date: 2017-11-26T03:05:42Z

  * Arxiv: http://arxiv.org/abs/1711.09327v1


* ### SmartEmbed: A Tool for Clone and Bug Detection in Smart Contracts through Structural Code Embedding by Zhipeng Gao, Vinoj Jayasundara, Lingxiao Jiang, Xin Xia, David Lo, John Grundy

  * Abstract: Ethereum has become a widely used platform to enable secure, Blockchain-based
financial and business transactions. However, a major concern in Ethereum is
the security of its smart contracts. Many identified bugs and vulnerabilities
in smart contracts not only present challenges to maintenance of blockchain,
but also lead to serious financial loses. There is a significant need to better
assist developers in checking smart contracts and ensuring their reliability.In
this paper, we propose a web service tool, named SmartEmbed, which can help
Solidity developers to find repetitive contract code and clone-related bugs in
smart contracts. Our tool is based on code embeddings and similarity checking
techniques. By comparing the similarities among the code embedding vectors for
existing solidity code in the Ethereum blockchain and known bugs, we are able
to efficiently identify code clones and clone-related bugs for any solidity
code given by users, which can help to improve the users' confidence in the
reliability of their code. In addition to the uses by individual developers,
SmartEmbed can also be applied to studies of smart contracts in a large scale.
When applied to more than 22K solidity contracts collected from the Ethereum
blockchain, we found that the clone ratio of solidity code is close to 90\%,
much higher than traditional software, and 194 clone-related bugs can be
identified efficiently and accurately based on our small bug database with a
precision of 96\%. SmartEmbed can be accessed at
\url{http://www.smartembed.net}. A demo video of SmartEmbed is at
\url{https://youtu.be/o9ylyOpYFq8}

  * Publication date: 2019-08-22T22:55:13Z

  * Arxiv: http://arxiv.org/abs/1908.08615v1


* ### A Secure Consensus Protocol for Sidechains by Fangyu Gai, Cesar Grajales, Jianyu Niu, Chen Feng

  * Abstract: Sidechain technology has been envisioned as a promising solution to
accelerate today's public blockchains in terms of scalability and
interoperability. By relying on the mainchain for security, different
sidechains can formulate their own rules to reach consensus. Although the
literature has considered the possibility of using consensus protocols in the
sidechain, so far a tailor-made consensus protocol for sidechains with high
performance and formal security proof has not been attempted. To fill this gap,
we introduce Vulcan, a low overhead, highly efficient, security provable
sidechain protocol. Vulcan makes use of smart contracts to ensure that only one
block proposed in the sidechain will be enforced on the mainchain in each
round, achieving consensus in an efficient manner. We give formal
specifications of Vulcan which ensures safety and liveness with $ validators
(total number of \geq 2f+1$) without online requirement of clients. For
security analysis, we give formal security definitions and proofs under
Universally Composable Security (UCS) model. As a proof of concept, we
implement Vulcan and evaluate it in Ethereum testnet.

  * Publication date: 2019-06-15T07:48:31Z

  * Arxiv: http://arxiv.org/abs/1906.06490v1


* ### Targeted Greybox Fuzzing with Static Lookahead Analysis by Valentin Wüstholz, Maria Christakis

  * Abstract: Automatic test generation typically aims to generate inputs that explore new
paths in the program under test in order to find bugs. Existing work has,
therefore, focused on guiding the exploration toward program parts that are
more likely to contain bugs by using an offline static analysis.
  In this paper, we introduce a novel technique for targeted greybox fuzzing
using an online static analysis that guides the fuzzer toward a set of target
locations, for instance, located in recently modified parts of the program.
This is achieved by first semantically analyzing each program path that is
explored by an input in the fuzzer's test suite. The results of this analysis
are then used to control the fuzzer's specialized power schedule, which
determines how often to fuzz inputs from the test suite. We implemented our
technique by extending a state-of-the-art, industrial fuzzer for Ethereum smart
contracts and evaluate its effectiveness on 27 real-world benchmarks. Using an
online analysis is particularly suitable for the domain of smart contracts
since it does not require any code instrumentation---instrumentation to
contracts changes their semantics. Our experiments show that targeted fuzzing
significantly outperforms standard greybox fuzzing for reaching 83% of the
challenging target locations (up to 14x of median speed-up).

  * Publication date: 2019-05-17T07:38:19Z

  * Arxiv: http://arxiv.org/abs/1905.07147v1


* ### TRIDEnT: Building Decentralized Incentives for Collaborative Security by Nikolaos Alexopoulos, Emmanouil Vasilomanolakis, Stephane Le Roux, Steven Rowe, Max Mühlhäuser

  * Abstract: Sophisticated mass attacks, especially when exploiting zero-day
vulnerabilities, have the potential to cause destructive damage to
organizations and critical infrastructure. To timely detect and contain such
attacks, collaboration among the defenders is critical. By correlating
real-time detection information (alerts) from multiple sources (collaborative
intrusion detection), defenders can detect attacks and take the appropriate
defensive measures in time. However, although the technical tools to facilitate
collaboration exist, real-world adoption of such collaborative security
mechanisms is still underwhelming. This is largely due to a lack of trust and
participation incentives for companies and organizations. This paper proposes
TRIDEnT, a novel collaborative platform that aims to enable and incentivize
parties to exchange network alert data, thus increasing their overall detection
capabilities. TRIDEnT allows parties that may be in a competitive relationship,
to selectively advertise, sell and acquire security alerts in the form of
(near) real-time peer-to-peer streams. To validate the basic principles behind
TRIDEnT, we present an intuitive game-theoretic model of alert sharing, that is
of independent interest, and show that collaboration is bound to take place
infinitely often. Furthermore, to demonstrate the feasibility of our approach,
we instantiate our design in a decentralized manner using Ethereum smart
contracts and provide a fully functional prototype.

  * Publication date: 2019-05-09T12:28:20Z

  * Arxiv: http://arxiv.org/abs/1905.03571v1


* ### Bug Searching in Smart Contract by Xiaotao Feng, Qin Wang, Xiaogang Zhu, Sheng Wen

  * Abstract: With the frantic development of smart contracts on the Ethereum platform, its
market value has also climbed. In 2016, people were shocked by the loss of
nearly  million in cryptocurrencies from the DAO reentrancy attack. Due to
the tremendous amount of money flowing in smart contracts, its security has
attracted much attention of researchers. In this paper, we investigated several
common smart contract vulnerabilities and analyzed their possible scenarios and
how they may be exploited. Furthermore, we survey the smart contract
vulnerability detection tools for the Ethereum platform in recent years. We
found that these tools have similar prototypes in software vulnerability
detection technology. Moreover, for the features of public distribution systems
such as Ethereum, we present the new challenges that these software
vulnerability detection technologies face.

  * Publication date: 2019-05-02T15:12:18Z

  * Arxiv: http://arxiv.org/abs/1905.00799v1


* ### Multi'Authority Attribute'Based Access Control with Smart Contract by Hao Guo, Ehsan Meamari, Chien'Chung Shen

  * Abstract: Attribute-based access control makes access control decisions based on the
assigned attributes of subjects and the access policies to protect objects by
mediating operations from the subjects. Authority, which validates attributes
of subjects, is one key component to facilitate attribute-based access control.
In an increasingly decentralized society, multiple attributes possessed by
subjects may need to be validated by multiple different authorities. This paper
proposes a multi-authority attribute-based access control scheme by using
Ethereum's smart contracts. In the proposed scheme, Ethereum smart contracts
are created to define the interactions between data owner, data user, and
multiple attribute authorities. A data user presents its attributes to
different attribute authorities, and after successful validation of attributes,
obtains attribute tokens from respective attribute authorities. After
collecting enough attribute tokens, a smart contract will be executed to issue
secret key to the data user to access the requested object. The smart contracts
for multi-authority attribute-based access control have been prototyped in
Solidity, and their performance has been evaluated on the Rinkeby Ethereum
Testnet.

  * Publication date: 2019-03-17T01:04:14Z

  * Arxiv: http://arxiv.org/abs/1903.07009v3


* ### The Attack of the Clones against Proof'of'Authority by Parinya Ekparinya, Vincent Gramoli, Guillaume Jourjon

  * Abstract: In this paper, we explore vulnerabilities and countermeasures of the recently
proposed blockchain consensus based on proof-of-authority. The proof-of-work
blockchains, like Bitcoin and Ethereum, have been shown both theoretically and
empirically vulnerable to double spending attacks. This is why Byzantine fault
tolerant consensus algorithms have gained popularity in the blockchain context
for their ability to tolerate a limited number t of attackers among n
participants. We formalize the recently proposed proof-of-authority consensus
algorithms that are Byzantine fault tolerant by describing the Aura and Clique
protocols present in the two mainstream implementations of Ethereum. We then
introduce the Cloning Attack and show how to apply it to double spend in each
of these protocols with a single malicious node. Our results show that the
Cloning Attack against Aura is always successful while the same attack against
Clique is about twice as fast and succeeds in most cases.

  * Publication date: 2019-02-26T21:58:38Z

  * Arxiv: http://arxiv.org/abs/1902.10244v2


* ### Precise Attack Synthesis for Smart Contracts by Yu Feng, Emina Torlak, Rastislav Bodik

  * Abstract: Smart contracts are programs running on top of blockchain platforms. They
interact with each other through well-defined interfaces to perform financial
transactions in a distributed system with no trusted third parties. But these
interfaces also provide a favorable setting for attackers, who can exploit
security vulnerabilities in smart contracts to achieve financial gain.
  This paper presents SmartScopy, a system for automatic synthesis of
adversarial contracts that identify and exploit vulnerabilities in a victim
smart contract. Our tool explores the space of mph{attack programs} based on
the Application Binary Interface (ABI) specification of a victim smart contract
in the Ethereum ecosystem. To make the synthesis tractable, we introduce
mph{summary-based symbolic evaluation}, which significantly reduces the
number of instructions that our synthesizer needs to evaluate symbolically,
without compromising the precision of the vulnerability query. Building on the
summary-based symbolic evaluation, SmartScopy further introduces a novel
approach for partitioning the synthesis search space for parallel exploration,
as well as a lightweight deduction technique that can prune infeasible
candidates earlier. We encoded common vulnerabilities of smart contracts in our
query language, and evaluated SmartScopy on the entire data set from etherscan
with $>K smart contracts. Our experiments demonstrate the benefits of
summary-based symbolic evaluation and show that SmartScopy outperforms two
state-of-the-art smart contracts analyzers, Oyente and Contractfuzz, in terms
of running time, precision, and soundness. Furthermore, running on recent
popular smart contracts, SmartScopy uncovers 20 vulnerable smart contracts that
contain the recent BatchOverflow vulnerability and cannot be precisely detected
by existing tools.

  * Publication date: 2019-02-16T08:37:32Z

  * Arxiv: http://arxiv.org/abs/1902.06067v1


* ### Decentralized Release of Self'emerging Data using Smart Contracts by Chao Li, Balaji Palanisamy

  * Abstract: In the age of Big Data, releasing protected sensitive data at a future point
in time is critical for various applications. Such self-emerging data release
requires the data to be protected until a prescribed data release time and be
automatically released to the recipient at the release time, even if the data
sender goes offline. While straight-forward centralized approaches provide a
basic solution to the problem, unfortunately they are limited to a single point
of trust and involve a single point of control. This paper presents
decentralized techniques for supporting self-emerging data using smart
contracts in Ethereum blockchain networks. We design a credible and enforceable
smart contract for supporting self-emerging data release. The smart contract
employs a set of Ethereum peers to jointly follow the proposed timed-release
service protocol allowing the participating peers to earn the remuneration paid
by the service users.We model the problem as an extensive-form game with
imperfect information to protect against possible adversarial attacks including
some peers destroying the private data (drop attack) or secretly releasing the
private data before the release time (release-ahead attack). We demonstrate the
efficacy and attack-resilience of the proposed techniques through rigorous
analysis and experimental evaluation. Our implementation and experimental
evaluation on the Ethereum official test network demonstrate the low monetary
cost and the low time overhead associated with the proposed approach and
validate its guaranteed security properties.

  * Publication date: 2019-02-14T22:11:27Z

  * Arxiv: http://arxiv.org/abs/1902.05623v1


* ### Decentralized Privacy'preserving Timed Execution in Blockchain'based Smart Contract Platforms by Chao Li, Balaji Palanisamy

  * Abstract: In the age of Big Data, enabling task scheduling while protecting users'
privacy is critical for various decentralized applications in blockchain-based
smart contract platforms. Such a privacy-preserving task scheduler requires the
task input data to be secretly maintained until a prescribed task execution
time and be automatically recorded into the blockchain to enabling the
execution of the task at the execution time, even if the user goes offline.
While straight-forward centralized approaches provide a basic solution to the
problem, unfortunately they are limited to a single point of trust and involve
a single point of control. This paper presents decentralized techniques for
supporting privacy-preserving task scheduling using smart contracts in Ethereum
blockchain networks. We design a privacy-preserving task scheduling protocol
that is managed by a manager smart contract. The protocol requires a user to
schedule a task by deploying a proxy smart contract maintaining the
non-sensitive information of the task while creating decentralized secret trust
and selecting trustees from the network to maintain the sensitive information
of the task. With security techniques including secret sharing and layered
encryption as well as security deposit paid by trustees as economic deterrence,
the protocol can protect the sensitive information against possible attacks
including some trustees destroying the sensitive information (drop attack) or
secretly releasing the sensitive information before the execution time
(release-ahead attack). We demonstrate the attack-resilience of the proposed
protocol through rigorous analysis.Our implementation and experimental
evaluation on the Ethereum official test network demonstrate the low monetary
cost and the low time overhead associated with the proposed approach.

  * Publication date: 2019-02-14T21:44:22Z

  * Arxiv: http://arxiv.org/abs/1902.05613v1


* ### Sereum: Protecting Existing Smart Contracts Against Re'Entrancy Attacks by Michael Rodler, Wenting Li, Ghassan O. Karame, Lucas Davi

  * Abstract: Recently, a number of existing blockchain systems have witnessed major bugs
and vulnerabilities within smart contracts. Although the literature features a
number of proposals for securing smart contracts, these proposals mostly focus
on proving the correctness or absence of a certain type of vulnerability within
a contract, but cannot protect deployed (legacy) contracts from being
exploited. In this paper, we address this problem in the context of re-entrancy
exploits and propose a novel smart contract security technology, dubbed Sereum
(Secure Ethereum), which protects existing, deployed contracts against
re-entrancy attacks in a backwards compatible way based on run-time monitoring
and validation. Sereum does neither require any modification nor any semantic
knowledge of existing contracts. By means of implementation and evaluation
using the Ethereum blockchain, we show that Sereum covers the actual execution
flow of a smart contract to accurately detect and prevent attacks with a false
positive rate as small as 0.06% and with negligible run-time overhead. As a
by-product, we develop three advanced re-entrancy attacks to demonstrate the
limitations of existing offline vulnerability analysis tools.

  * Publication date: 2018-12-14T13:54:34Z

  * Arxiv: http://arxiv.org/abs/1812.05934v1


* ### SOC: hunting the underground inside story of the ethereum Social'network Opinion and Comment by TonTon Hsien'De Huang, Po'Wei Hong, Ying'Tse Lee, Yi'Lun Wang, Chi'Leong Lok, Hung'Yu Kao

  * Abstract: The cryptocurrency is attracting more and more attention because of the
blockchain technology. Ethereum is gaining a significant popularity in
blockchain community, mainly due to the fact that it is designed in a way that
enables developers to write smart contracts and decentralized applications
(Dapps). There are many kinds of cryptocurrency information on the social
network. The risks and fraud problems behind it have pushed many countries
including the United States, South Korea, and China to make warnings and set up
corresponding regulations. However, the security of Ethereum smart contracts
has not gained much attention. Through the Deep Learning approach, we propose a
method of sentiment analysis for Ethereum's community comments. In this
research, we first collected the users' cryptocurrency comments from the social
network and then fed to our LSTM + CNN model for training. Then we made
prediction through sentiment analysis. With our research result, we have
demonstrated that both the precision and the recall of sentiment analysis can
achieve 0.80+. More importantly, we deploy our sentiment analysis1 on
RatingToken and Coin Master (mobile application of Cheetah Mobile Blockchain
Security Center23). We can effectively provide detail information to resolve
the risks of being fake and fraud problems.

  * Publication date: 2018-11-27T17:54:12Z

  * Arxiv: http://arxiv.org/abs/1811.11136v1


* ### EASYFLOW: Keep Ethereum Away From Overflow by Jianbo Gao, Han Liu, Chao Liu, Qingshan Li, Zhi Guan, Zhong Chen

  * Abstract: While Ethereum smart contracts enabled a wide range of blockchain
applications, they are extremely vulnerable to different forms of security
attacks. Due to the fact that transactions to smart contracts commonly involve
cryptocurrency transfer, any successful attacks can lead to money loss or even
financial disorder. In this paper, we focus on the overflow attacks in Ethereum
, mainly because they widely rooted in many smart contracts and comparatively
easy to exploit. We have developed EASYFLOW , an overflow detector at Ethereum
Virtual Machine level. The key insight behind EASYFLOW is a taint analysis
based tracking technique to analyze the propagation of involved taints.
Specifically, EASYFLOW can not only divide smart contracts into safe contracts,
manifested overflows, well-protected overflows and potential overflows, but
also automatically generate transactions to trigger potential overflows. In our
preliminary evaluation, EASYFLOW managed to find potentially vulnerable
Ethereum contracts with little runtime overhead.

  * Publication date: 2018-11-09T08:27:37Z

  * Arxiv: http://arxiv.org/abs/1811.03814v2


* ### Blockchain based Proxy Re'Encryption Scheme for Secure IoT Data Sharing by Ahsan Manzoor, Madhsanka Liyanage, An Braeken, Salil S. Kanhere, Mika Ylianttila

  * Abstract: Data is central to the Internet of Things (IoT) ecosystem. Most of the
current IoT systems are using centralized cloud-based data sharing systems,
which will be difficult to scale up to meet the demands of future IoT systems.
Involvement of such third-party service provider requires also trust from both
sensor owner and sensor data user. Moreover, the fees need to be paid for their
services. To tackle both the scalability and trust issues and to automatize the
payments, this paper presents a blockchain based proxy re-encryption scheme.
The system stores the IoT data in a distributed cloud after encryption. To
share the collected IoT data, the system establishes runtime dynamic smart
contracts between the sensor and data user without the involvement of a trusted
third party. It also uses a very efficient proxy re-encryption scheme which
allows that the data is only visible by the owner and the person present in the
smart contract. This novel combination of smart contracts with proxy
re-encryption provides an efficient, fast and secure platform for storing,
trading and managing of sensor data. The proposed system is implemented in an
Ethereum based testbed to analyze the performance and the security properties.

  * Publication date: 2018-11-06T10:46:42Z

  * Arxiv: http://arxiv.org/abs/1811.02276v2


* ### Exploiting The Laws of Order in Smart Contracts by Aashish Kolluri, Ivica Nikolic, Ilya Sergey, Aquinas Hobor, Prateek Saxena

  * Abstract: We investigate a family of bugs in blockchain-based smart contracts, which we
call event-ordering (or EO) bugs. These bugs are intimately related to the
dynamic ordering of contract events, i.e., calls of its functions on the
blockchain, and enable potential exploits of millions of USD worth of Ether.
Known examples of such bugs and prior techniques to detect them have been
restricted to a small number of event orderings, typicall 1 or 2. Our work
provides a new formulation of this general class of EO bugs as finding
concurrency properties arising in long permutations of such events. The
technical challenge in detecting our formulation of EO bugs is the inherent
combinatorial blowup in path and state space analysis, even for simple
contracts. We propose the first use of partial-order reduction techniques,
using happen-before relations extracted automatically for contracts, along with
several other optimizations built on a dynamic symbolic execution technique. We
build an automatic tool called ETHRACER that requires no hints from users and
runs directly on Ethereum bytecode. It flags 7-11% of over ten thousand
contracts analyzed in roughly 18.5 minutes per contract, providing compact
event traces that human analysts can run as witnesses. These witnesses are so
compact that confirmations require only a few minutes of human effort. Half of
the flagged contracts have subtle EO bugs, including in ERC-20 contracts that
carry hundreds of millions of dollars worth of Ether. Thus, ETHRACER is
effective at detecting a subtle yet dangerous class of bugs which existing
tools miss.

  * Publication date: 2018-10-27T06:41:38Z

  * Arxiv: http://arxiv.org/abs/1810.11605v1


* ### Vandal: A Scalable Security Analysis Framework for Smart Contracts by Lexi Brent, Anton Jurisevic, Michael Kong, Eric Liu, Francois Gauthier, Vincent Gramoli, Ralph Holz, Bernhard Scholz

  * Abstract: The rise of modern blockchains has facilitated the emergence of smart
contracts: autonomous programs that live and run on the blockchain. Smart
contracts have seen a rapid climb to prominence, with applications predicted in
law, business, commerce, and governance.
  Smart contracts are commonly written in a high-level language such as
Ethereum's Solidity, and translated to compact low-level bytecode for
deployment on the blockchain. Once deployed, the bytecode is autonomously
executed, usually by a %Turing-complete virtual machine. As with all programs,
smart contracts can be highly vulnerable to malicious attacks due to deficient
programming methodologies, languages, and toolchains, including buggy
compilers. At the same time, smart contracts are also high-value targets, often
commanding large amounts of cryptocurrency. Hence, developers and auditors need
security frameworks capable of analysing low-level bytecode to detect potential
security vulnerabilities.
  In this paper, we present Vandal: a security analysis framework for Ethereum
smart contracts. Vandal consists of an analysis pipeline that converts
low-level Ethereum Virtual Machine (EVM) bytecode to semantic logic relations.
Users of the framework can express security analyses in a declarative fashion:
a security analysis is expressed in a logic specification written in the
\souffle language. We conduct a large-scale empirical study for a set of common
smart contract security vulnerabilities, and show the effectiveness and
efficiency of Vandal. Vandal is both fast and robust, successfully analysing
over 95\% of all 141k unique contracts with an average runtime of 4.15 seconds;
outperforming the current state of the art tools---Oyente, EthIR, Mythril, and
Rattle---under equivalent conditions.

  * Publication date: 2018-09-11T15:39:35Z

  * Arxiv: http://arxiv.org/abs/1809.03981v1


* ### Empirical Vulnerability Analysis of Automated Smart Contracts Security Testing on Blockchains by Reza M. Parizi, Ali Dehghantanha, Kim'Kwang Raymond Choo, Amritraj Singh

  * Abstract: The emerging blockchain technology supports decentralized computing paradigm
shift and is a rapidly approaching phenomenon. While blockchain is thought
primarily as the basis of Bitcoin, its application has grown far beyond
cryptocurrencies due to the introduction of smart contracts. Smart contracts
are self-enforcing pieces of software, which reside and run over a hosting
blockchain. Using blockchain-based smart contracts for secure and transparent
management to govern interactions (authentication, connection, and transaction)
in Internet-enabled environments, mostly IoT, is a niche area of research and
practice. However, writing trustworthy and safe smart contracts can be
tremendously challenging because of the complicated semantics of underlying
domain-specific languages and its testability. There have been high-profile
incidents that indicate blockchain smart contracts could contain various
code-security vulnerabilities, instigating financial harms. When it involves
security of smart contracts, developers embracing the ability to write the
contracts should be capable of testing their code, for diagnosing security
vulnerabilities, before deploying them to the immutable environments on
blockchains. However, there are only a handful of security testing tools for
smart contracts. This implies that the existing research on automatic smart
contracts security testing is not adequate and remains in a very stage of
infancy. With a specific goal to more readily realize the application of
blockchain smart contracts in security and privacy, we should first understand
their vulnerabilities before widespread implementation. Accordingly, the goal
of this paper is to carry out a far-reaching experimental assessment of current
static smart contracts security testing tools, for the most widely used
blockchain, the Ethereum and its domain-specific programming language, Solidity
to provide the first...

  * Publication date: 2018-09-07T22:39:49Z

  * Arxiv: http://arxiv.org/abs/1809.02702v1


* ### Bicomp: A Bilayer Scalable Nakamoto Consensus Protocol by Zhenzhen Jiao, Rui Tian, Dezhong Shang, Hui Ding

  * Abstract: Blockchain has received great attention in recent years and motivated
innovations in different scenarios. However, many vital issues which affect its
performance are still open. For example, it is widely convinced that high level
of security and scalability and full decentralization are still impossible to
achieve simultaneously. In this paper, we propose Bicomp, a bilayer scalable
Nakamoto consensus protocol, which is an approach based on high security and
pure decentralized Nakamoto consensus, and with a significant improvement on
scalability. In Bicomp, two kinds of blocks are generated, i.e., microblocks
for concurrent transaction packaging in network, and macroblocks for leadership
competition and chain formation. A leader is elected at beginning of each round
by using a macroblock header from proof-of-work. An elected leader then
receives and packages multiple microblocks mined by different nodes into one
macroblock during its tenure, which results in a bilayer block structure. Such
design limits a leader's power and encourages as many nodes as possible to
participate in the process of packaging transactions, which promotes the
sharding nature of the system. Furthermore, several mechanisms are carefully
designed to reduce transaction overlapping and further limit a leader's power,
among which a novel transaction diversity based metric is proposed as the
second level criteria besides the longest-chain-first principle on selecting a
legitimate chain when fork happens. Security issues and potential attacks to
Bicomp are extensively discussed and experiments for evaluation are performed.
From the experimental results based on 50 nodes all over the world, Bicomp
achieves significant improvement on scalability than that of Bitcoin and
Ethereum, while the security and decentralization merits are still preserved.

  * Publication date: 2018-09-05T16:06:49Z

  * Arxiv: http://arxiv.org/abs/1809.01593v1


* ### ContractFuzzer: Fuzzing Smart Contracts for Vulnerability Detection by Bo Jiang, Ye Liu, W. K. Chan

  * Abstract: Decentralized cryptocurrencies feature the use of blockchain to transfer
values among peers on networks without central agency. Smart contracts are
programs running on top of the blockchain consensus protocol to enable people
make agreements while minimizing trusts. Millions of smart contracts have been
deployed in various decentralized applications. The security vulnerabilities
within those smart contracts pose significant threats to their applications.
Indeed, many critical security vulnerabilities within smart contracts on
Ethereum platform have caused huge financial losses to their users. In this
work, we present ContractFuzzer, a novel fuzzer to test Ethereum smart
contracts for security vulnerabilities. ContractFuzzer generates fuzzing inputs
based on the ABI specifications of smart contracts, defines test oracles to
detect security vulnerabilities, instruments the EVM to log smart contracts
runtime behaviors, and analyzes these logs to report security vulnerabilities.
Our fuzzing of 6991 smart contracts has flagged more than 459 vulnerabilities
with high precision. In particular, our fuzzing tool successfully detects the
vulnerability of the DAO contract that leads to USD 60 million loss and the
vulnerabilities of Parity Wallet that have led to the loss of  million and
the freezing of USD 150 million worth of Ether.

  * Publication date: 2018-07-11T02:32:54Z

  * Arxiv: http://arxiv.org/abs/1807.03932v2


* ### Design Patterns which Facilitate Message Digest Collision Attacks on Blockchains by Peter Robinson

  * Abstract: Message digest algorithms are one of the underlying building blocks of
blockchain platforms such as Ethereum. This paper analyses situations in which
the message digest collision resistance property can be exploited by attackers.
Two mitigations for possible attacks are described: longer message digest sizes
make attacks more difficult; and, including timeliness properties limits the
amount of time an attacker has to determine a hash collision.

  * Publication date: 2018-06-15T06:27:43Z

  * Arxiv: http://arxiv.org/abs/1806.05822v1


* ### A Memo on the Proof'of'Stake Mechanism by George Gui, Ali Hortacsu, Jose Tudon

  * Abstract: We analyze the economic incentives generated by the proof-of-stake mechanism
discussed in the Ethereum Casper upgrade proposal. Compared with proof-of-work,
proof-of-stake has a different cost structure for attackers. In Budish (2018),
three equations characterize the limits of Bitcoin, which has a proof-of-work
mechanism. We investigate their counterparts and evaluate the risk of
double-spending attack and sabotage attack. We argue that PoS is safer than PoW
agaisnt double-spending attack because of the tractability of attackers, which
implies a large stock cost for the attacker. Compared to a PoW system whose
mining equipments are repurposable, PoS is also safer against a sabotage
attack.

  * Publication date: 2018-06-14T00:17:02Z

  * Arxiv: http://arxiv.org/abs/1807.09626v1


* ### Securify: Practical Security Analysis of Smart Contracts by Petar Tsankov, Andrei Dan, Dana Drachsler Cohen, Arthur Gervais, Florian Buenzli, Martin Vechev

  * Abstract: Permissionless blockchains allow the execution of arbitrary programs (called
smart contracts), enabling mutually untrusted entities to interact without
relying on trusted third parties. Despite their potential, repeated security
concerns have shaken the trust in handling billions of USD by smart contracts.
  To address this problem, we present Securify, a security analyzer for
Ethereum smart contracts that is scalable, fully automated, and able to prove
contract behaviors as safe/unsafe with respect to a given property. Securify's
analysis consists of two steps. First, it symbolically analyzes the contract's
dependency graph to extract precise semantic information from the code. Then,
it checks compliance and violation patterns that capture sufficient conditions
for proving if a property holds or not. To enable extensibility, all patterns
are specified in a designated domain-specific language.
  Securify is publicly released, it has analyzed >18K contracts submitted by
its users, and is regularly used to conduct security audits by experts. We
present an extensive evaluation of Securify over real-world Ethereum smart
contracts and demonstrate that it can effectively prove the correctness of
smart contracts and discover critical violations.

  * Publication date: 2018-06-04T14:21:21Z

  * Arxiv: http://arxiv.org/abs/1806.01143v2


* ### Smart Contract'Based Access Control for the Internet of Things by Yuanyu Zhang, Shoji Kasahara, Yulong Shen, Xiaohong Jiang, Jianxiong Wan

  * Abstract: This paper investigates a critical access control issue in the Internet of
Things (IoT). In particular, we propose a smart contract-based framework, which
consists of multiple access control contracts (ACCs), one judge contract (JC)
and one register contract (RC), to achieve distributed and trustworthy access
control for IoT systems. Each ACC provides one access control method for a
subject-object pair, and implements both static access right validation based
on predefined policies and dynamic access right validation by checking the
behavior of the subject. The JC implements a misbehavior-judging method to
facilitate the dynamic validation of the ACCs by receiving misbehavior reports
from the ACCs, judging the misbehavior and returning the corresponding penalty.
The RC registers the information of the access control and misbehavior-judging
methods as well as their smart contracts, and also provides functions (e.g.,
register, update and delete) to manage these methods. To demonstrate the
application of the framework, we provide a case study in an IoT system with one
desktop computer, one laptop and two Raspberry Pi single-board computers, where
the ACCs, JC and RC are implemented based on the Ethereum smart contract
platform to achieve the access control.

  * Publication date: 2018-02-13T00:42:31Z

  * Arxiv: http://arxiv.org/abs/1802.04410v1


* ### Securing the Assets of Decentralized Applications using Financial Derivatives (DRAFT) by George Bissias, Brian Levine, Nikunj Kapadia

  * Abstract: Ethereum contracts can be designed to function as fully decentralized
applications called DAPPs. Many DAPPs have already been fielded, including an
online marketplace, a role playing game, a prediction market, and an Internet
service provider. Unfortunately, DAPPs can be hacked, and the assets they
control can be stolen. A recent attack on an Ethereum decentralized application
called The DAO demonstrated that smart contract bugs are more than an academic
concern. Ether worth tens of millions of US dollars was extracted by an
attacker from The DAO, sending the value of its tokens and the overall exchange
price of ether tumbling.
  We present a market-based technique for insuring the ether holdings of a DAPP
using futures contracts indexed by the trade price of ether for DAPP tokens.
Under fairly general circumstances, our technique is capable of recovering the
majority of ether lost from theft with high probability even when all of the
ether holdings are stolen; and the only cost to DAPP token holders is an
adjustable ether withdrawal fee. If the probability of a margin call in $
days is $ for a futures contract with 20 times leverage, then our approach
will allow for the recovery of half the stolen ether with probability $ and a
withdrawal fee of 5%. A higher withdrawal fee of 25% allows for more than 80%
of the ether to be recovered with probability $.

  * Publication date: 2017-01-14T16:35:03Z

  * Arxiv: http://arxiv.org/abs/1701.03945v1


* ### The Balance Attack Against Proof'Of'Work Blockchains: The R3 Testbed as an Example by Christopher Natoli, Vincent Gramoli

  * Abstract: In this paper, we identify a new form of attack, called the Balance attack,
against proof-of-work blockchain systems. The novelty of this attack consists
of delaying network communications between multiple subgroups of nodes with
balanced mining power. Our theoretical analysis captures the precise tradeoff
between the network delay and the mining power of the attacker needed to double
spend in Ethereum with high probability.
  We quantify our probabilistic analysis with statistics taken from the R3
consortium, and show that a single machine needs 20 minutes to attack the
consortium. Finally, we run an Ethereum private chain in a distributed system
with similar settings as R3 to demonstrate the feasibility of the approach, and
discuss the application of the Balance attack to Bitcoin. Our results clearly
confirm that main proof-of-work blockchain protocols can be badly suited for
consortium blockchains.

  * Publication date: 2016-12-30T09:08:10Z

  * Arxiv: http://arxiv.org/abs/1612.09426v1


