* ### Towards Secure and Decentralized Sharing of IoT Data by Hien Thi Thu Truong, Miguel Almeida, Ghassan Karame, Claudio Soriente

  * Abstract: The Internet of Things (IoT) bears unprecedented security and scalability
challenges due to the magnitude of data produced and exchanged by IoT devices
and platforms. Some of those challenges are currently being addressed by
coupling IoT applications with blockchains. However, current blockchain-backed
IoT systems simply use the blockchain to store access control policies, thereby
underutilizing the power of blockchain technology. In this paper, we propose a
new framework named Sash that couples IoT platforms with blockchain that
provides a number of advantages compared to state of the art. In Sash, the
blockchain is used to store access control policies and take access control
decisions. Therefore, both changes to policies and access requests are
correctly enforced and publicly auditable. Further, we devise a data
marketplace'' by leveraging the ability of blockchains to handle financial
transaction and providing by design'' remuneration to data producers.
Finally, we exploit a special flavor of identity-based encryption to cater for
cryptography-enforced access control while minimizing the overhead to
distribute decryption keys. We prototype Sash by using the FIWARE open source
IoT platform and the Hyperledger Fabric framework as the blockchain back-end.
We also evaluate the performance of our prototype and show that it incurs
tolerable overhead in realistic deployment settings.

  * Publication date: 2019-08-23T19:50:40Z

  * Arxiv: http://arxiv.org/abs/1908.09015v1


* ### Verity: Blockchains to Detect Insider Attacks in DBMS by Shubham S. Srivastava, Medha Atre, Shubham Sharma, Rahul Gupta, Sandeep K. Shukla

  * Abstract: Integrity and security of the data in database systems are typically
maintained with access control policies and firewalls. However, insider attacks
-- where someone with an intimate knowledge of the system and administrative
privileges tampers with the data -- pose a unique challenge. Measures like
append only logging prove to be insufficient because an attacker with
administrative privileges can alter logs and login records to eliminate the
trace of attack, thus making insider attacks hard to detect.
  In this paper, we propose Verity -- first of a kind system to the best of our
knowledge. Verity serves as a dataless framework by which any blockchain
network can be used to store fixed-length metadata about tuples from any SQL
database, without complete migration of the database. Verity uses a formalism
for parsing SQL queries and query results to check the respective tuples'
integrity using blockchains to detect insider attacks. We have implemented our
technique using Hyperledger Fabric, Composer REST API, and SQLite database.
Using TPC-H data and SQL queries of varying complexity and types, our
experiments demonstrate that any overhead of integrity checking remains
constant per tuple in a query's results, and scales linearly.

  * Publication date: 2019-01-02T01:02:56Z

  * Arxiv: http://arxiv.org/abs/1901.00228v1


* ### Towards Blockchain'Driven, Secure and Transparent Audit Logs by Ashar Ahmad, Muhammad Saad, Mostafa Bassiouni, Aziz Mohaisen

  * Abstract: Audit logs serve as a critical component in the enterprise business systems
that are used for auditing, storing, and tracking changes made to the data.
However, audit logs are vulnerable to a series of attacks, which enable
adversaries to tamper data and corresponding audit logs. In this paper, we
present BlockAudit: a scalable and tamper-proof system that leverages the
design properties of audit logs and security guarantees of blockchains to
enable secure and trustworthy audit logs. Towards that, we construct the design
schema of BlockAudit, and outline its operational procedures. We implement our
design on Hyperledger and evaluate its performance in terms of latency, network
size, and payload size. Our results show that conventional audit logs can
seamlessly transition into BlockAudit to achieve higher security, integrity,
and fault tolerance.

  * Publication date: 2018-11-25T04:55:31Z

  * Arxiv: http://arxiv.org/abs/1811.09944v1


* ### Trustworthy Configuration Management for Networked Devices using  Distributed Ledgers by Holger Kinkelin, Valentin Hauner, Heiko Niedermayer, Georg Carle

  * Abstract: Numerous IoT applications, like building automation or process control of
industrial sites, exist today. These applications inherently have a strong
connection to the physical world. Hence, IT security threats cannot only cause
problems like data leaks but also safety issues which might harm people.
Attacks on IT systems are not only performed by outside attackers but also
insiders like administrators. For this reason, we present ongoing work on a
configuration management system (CMS) that provides control over
administrators, restrains their rights, and enforces separation of concerns. We
reach this goal by conducting a configuration management process that requires
multi-party authorization for critical configurations to achieve Byzantine
fault tolerance against attacks and faults by administrators. Only after a
configuration has been authorized by multiple experts, it is applied to the
targeted devices. For the whole configuration management process, our CMS
guarantees accountability and traceability. Lastly, our system is
tamper-resistant as we leverage Hyperledger Fabric, which provides a
distributed execution environment for our CMS and a blockchain-based
distributed ledger that we use to store the configurations. A beneficial side
effect of this approach is that our CMS is also suitable to manage
configurations for infrastructure shared across different organizations that do
not need to trust each other.

  * Publication date: 2018-04-13T06:43:29Z

  * Arxiv: http://arxiv.org/abs/1804.04798v2


