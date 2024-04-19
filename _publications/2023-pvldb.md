---
title: "ScalarDB: Universal Transaction Manager for Polystores"
collection: publications
permalink: /publication/2023-pvldb
date: 2023-08-01
venue: 'PVLDB (VLDB) - Proceedings of the VLDB Endowment'
paperurl: 'https://dl.acm.org/doi/10.14778/3611540.3611563'
citation: '<u>H. Yamada</u>, T. Suzuki, Y. Ito, and J. Nemoto. 2023. ScalarDB: Universal Transaction Manager for Polystores. PVLDB 16, 12, 3768–3780.'
---
This paper presents ScalarDB, a universal transaction manager that achieves distributed transactions across multiple disparate databases. ScalarDB provides a database-agnostic transaction manager on top of its database abstraction; thus, it achieves transactions spanning various databases without depending on the transactional capability of underlying databases. ScalarDB is based on several research works and extended to provide a strong correctness guarantee (i.e., strict serializability), further performance optimizations, and several critical mechanisms for productization. In this paper, we describe the design and implementation of ScalarDB. We also present evaluation results showing that ScalarDB achieves database-spanning transactions with reasonable performance and near-linear scalability without sacrificing correctness. Finally, we share some case studies and lessons learned while building and running ScalarDB.

[Download paper here](https://dl.acm.org/doi/10.14778/3611540.3611563)

Recommended citation: H. Yamada, T. Suzuki, Y. Ito, and J. Nemoto. 2023. ScalarDB: Universal Transaction Manager for Polystores. PVLDB 16, 12, 3768–3780.
---

