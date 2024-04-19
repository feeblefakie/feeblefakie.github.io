---
title: "Scalar DL: Scalable and Practical Byzantine Fault Detection for Transactional Database Systems"
collection: publications
permalink: /publication/2022-pvldb
date: 2022-03-01
venue: 'PVLDB (VLDB) - Proceedings of the VLDB Endowment'
paperurl: 'https://dl.acm.org/doi/10.14778/3523210.3523212'
citation: '<u>H. Yamada</u> and J. Nemoto. 2022. Scalar DL: Scalable and Practical Byzantine Fault Detection for Transactional Database Systems. PVLDB 15, 7 (2022), 1324-1336.'
---
This paper presents Scalar DL, a Byzantine fault detection (BFD) middleware for transactional database systems. Scalar DL manages two separately administered database replicas in a database system and can detect Byzantine faults in the database system as long as either replica is honest (not faulty). Unlike previous BFD works, Scalar DL executes non-conflicting transactions in parallel while preserving a correctness guarantee. Moreover, Scalar DL is database-agnostic middleware so that it achieves the detection capability in a database system without either modifying the databases or using database-specific mechanisms. Experimental results with YCSB and TPC-C show that Scalar DL outperforms a state-of-the-art BFD system by 3.5 to 10.6 times in throughput and works effectively on multiple database implementations. We also show that Scalar DL achieves near-linear (91%) scalability when the number of nodes composing each replica increases.

[Download paper here](https://dl.acm.org/doi/10.14778/3523210.3523212)

Recommended citation: H. Yamada and J. Nemoto. 2022. Scalar DL: Scalable and Practical Byzantine Fault Detection for Transactional Database Systems. PVLDB 15, 7 (2022), 1324-1336.
---

