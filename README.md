# Database and Blockchain Related Paper List
The repo lists recently papers of Blockchain, Outsourcing Database, Database Transaction Management, Database with modern AI and Hardware, and other related crypto tech papers.

[:accept:] means Recommendation 
[:accept: :accept:] means Strong Recommendation 


Inculding Conferences
- OSDI
- SIGMOD
- VLDB

## Blockchain
- Blurring the Lines between Blockchains and Database Systems: the Case of Hyperledger Fabric, SIGMOD 2019
- FlyClient: Super-Light Clients for Cryptocurrencies 2020 [[paper]](https://eprint.iacr.org/2019/226.pdf)
- Zether: Towards Privacy in a Smart Contract World [[paper]](https://crypto.stanford.edu/~buenz/papers/zether.pdf)

## Database 

### Indexing and data structure


### Database System
- CockroachDB: The Resilient Geo-Distributed SQL Database, SIGMOD 2020, [[paper]](https://dl.acm.org/doi/pdf/10.1145/3318464.3386134)
- FoundationDB: A Distributed Unbundled Transactional Key Value Store, Apple Inc, SIGMOD 2021, [[Paper]](https://www.foundationdb.org/files/fdb-paper.pdf)

### Concurrency
- [:accept: :accept:] Making Snapshot Isolation Serializable, [[paper]](http://www.cse.iitb.ac.in/infolab/Data/Courses/CS632/Papers/p492-fekete.pdf)
- [:accept:] Serializable Snapshot Isolation in PostgreSQL, VLDB 2012, [[paper]](https://drkp.net/papers/ssi-vldb12.pdf)
- TicToc: Time Traveling Optimistic Concurrency Control, SIGMOD 2016, [[paper]](https://people.csail.mit.edu/devadas/pubs/tictoc.pdf)
- Improving Optimistic Concurrency Control Through Transaction Batching and Operation Reordering, MS, VLDB 2018, [[paper]](http://www.vldb.org/pvldb/vol12/p169-ding.pdf)
- Handling Highly Contended OLTP Workloads Using Fast Dynamic Partitioning, Dan Suciu ,SIGMOD 2020, [[paper]](https://dl-acm-org.lib.ezproxy.ust.hk/doi/pdf/10.1145/3318464.3389764)
- Polyjuice: High-Performance Transactions via Learned Concurrency Control, OSDI 2021, [[paper]](https://arxiv.org/pdf/2105.10329.pdf)

### Database Recovery
- Constant Time Recovery in Azure SQL Database, MS Inc, VLDB 2019, [[Paper]](https://www.microsoft.com/en-us/research/uploads/prod/2019/06/p700-antonopoulos.pdf)

### Database Transaction Management
- Loose-Ordering Consistency for Persistent Memory
- TicToc: Time Traveling Optimistic Concurrency Control, Andy Pavlo, SIGMOD 2016, [MVCC] [[Paper]](https://people.csail.mit.edu/devadas/pubs/tictoc.pdf)
- Cicada: Dependably Fast Multi-Core In-Memory Transactions, SIGMOD 2017, [In-Memory] [[Paper]](https://15721.courses.cs.cmu.edu/spring2018/papers/06-mvcc2/lim-sigmod2017.pdf)
- An Empirical Evaluation of In-Memory Multi-Version Concurrency Control, Andy Pavlo,VLDB 2017, [MVCC]
- Large-scale Incremental Processing Using Distributed Transactions and Notifications, [[paper]](https://storage.googleapis.com/pub-tools-public-publication-data/pdf/36726.pdf)

### Database with Machine Learning
- Automatic Database Management System Tuning ThroughLarge-scale Machine Learning, Andy Pavlo , SIGMOD 2017, [AI FOR DB]
- iBTune: Individualized Buffer Tuning for Large-scale Cloud Databases, Li FeiFei, VLDB 2019
- Leaper: A Learned Prefetcher for Cache Invalidation in LSM-tree based Storage Engines, Li FeiFei, Zou Lei, VLDB 2020, [[paper]](http://www.vldb.org/pvldb/vol13/p1976-yang.pdf)
- An End-to-End Automatic Cloud Database Tuning System Using Deep Reinforcement Learning, Guoliang Li and Tencent , SIGMOD 2019
- Scheduling OLTP Transactions via Learned Abort Prediction, Andy Pavlo , SIGMOD 2019, [[paper]](https://db.cs.cmu.edu/papers/2019/a1-sheng.pdf)

### Database with Modern Hardware 
- A Study of the Fundamental Performance Characteristics of GPUs and CPUs for Database Analytics, **SIGMOD 2020**, Samuel Madden, Xiangyao Yu, [[paper]](http://pages.cs.wisc.edu/~yxy/pubs/crystal.pdf)

### Deterministic Database System
- An Evaluation of the Advantages and Disadvantages of Deterministic Database Systems, **VLDB 2014**, [[Paper]](https://dl-acm-org.lib.ezproxy.ust.hk/doi/pdf/10.14778/2732951.2732955)
- Aria: A Fast and Practical Deterministic OLTP Database, VLDB 2020, [[paper]](http://www.vldb.org/pvldb/vol13/p2047-lu.pdf)

### Query Optimazition
- An End-to-End Learning-based Cost Estimator, Li guoliang, VLDB 2019, [[paper]](https://15721.courses.cs.cmu.edu/spring2020/papers/22-costmodels/p307-sun.pdf)

# Blockchain and Database Top Reseachers

## Industry
- Li Feifei, VP, Alibaba Damo, [Cloud native database]

## Academic
- Andy Pavlo, Associate Professor，CMU, [Database system] [[Homepage]](http://www.cs.cmu.edu/~pavlo/)
  - Xiangyao Yu, Assistant Professor, UW, [Database system] [[Homepage]](http://pages.cs.wisc.edu/~yxy/)
- Lei chen, Chair Professor, HKUST, [Crowdsourcing, Blockchain, Knowledge base, Data management]
- Guoliang li, Professor, Tsinghua , [Crowdsourcing, Database]
- Samuel Madden, Professor, MIT, [Database system][[Homepage]](http://db.csail.mit.edu/madden/)
  - Daniel J. Abadi, Professor, umd, [Database system][[Homepage]](http://www.cs.umd.edu/~abadi/)
- Lorenzo Alvisi

# Other references
- Raft in Live [[link]](http://thesecretlivesofdata.com/raft/)
- ZKP [[link]](http://www.zeroknowledgeblog.com/)
