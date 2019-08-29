
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


