# Systems Resources

A curated collection of foundational papers and resources on distributed systems, scalability, architecture patterns, and design principles from leading technology companies and academic institutions.

---

## Table of Contents

- [Google](#google)
- [Amazon](#amazon)
- [Meta (Facebook)](#meta-facebook)
- [LinkedIn](#linkedin)
- [Apache](#apache)
- [Other Notable Systems](#other-notable-systems)

---

## Google

Foundational papers that shaped modern cloud infrastructure and distributed systems.

### Storage & File Systems
- **[Google File System (GFS)](https://static.googleusercontent.com/media/research.google.com/en//archive/gfs-sosp2003.pdf)** - Distributed file system architecture
- **[Colossus](https://cloud.google.com/blog/products/storage-data-transfer/a-peek-behind-colossus-googles-file-system)** - Next-generation Google file system
- **[Bigtable](https://static.googleusercontent.com/media/research.google.com/en//archive/bigtable-osdi06.pdf)** - Distributed storage system for structured data

### Databases & Data Processing
- **[Spanner](https://static.googleusercontent.com/media/research.google.com/en//archive/spanner-osdi2012.pdf)** - Globally distributed database with external consistency
  - **[CAP Theorem Considerations](https://cloud.google.com/blog/products/databases/inside-cloud-spanner-and-the-cap-theorem)** - Understanding Spanner's consistency model
- **[Megastore](https://www.cidrdb.org/cidr2011/Papers/CIDR11_Paper32.pdf)** - Scalable, highly available storage for interactive services
- **[F1](https://static.googleusercontent.com/media/research.google.com/en//pubs/archive/41344.pdf)** - Distributed SQL database built on Spanner
- **[Firestore](https://storage.googleapis.com/gweb-research2023-media/pubtools/7076.pdf)** - Document database with real-time synchronization
- **[MapReduce](https://static.googleusercontent.com/media/research.google.com/en//archive/mapreduce-osdi04.pdf)** - Simplified data processing on large clusters

### Data Warehousing & Analytics
- **[Mesa](https://static.googleusercontent.com/media/research.google.com/en//pubs/archive/42851.pdf)** - Geo-replicated, near real-time data warehouse
- **[Napa](https://www.vldb.org/pvldb/vol14/p2986-sankaranarayanan.pdf)** - Powering scalable data warehousing with robust partitioning

### Infrastructure & Orchestration
- **[Borg](https://dl.acm.org/doi/pdf/10.1145/2741948.2741964)** - Large-scale cluster management at Google
- **[Chubby](https://static.googleusercontent.com/media/research.google.com/en//archive/chubby-osdi06.pdf)** - Lock service for loosely-coupled distributed systems

### Monitoring, Tracing & Authorization
- **[Dapper](https://static.googleusercontent.com/media/research.google.com/en//archive/papers/dapper-2010-1.pdf)** - Large-scale distributed systems tracing infrastructure
- **[Monarch](https://storage.googleapis.com/gweb-research2023-media/pubtools/6348.pdf)** - Global in-memory time series database
- **[Zanzibar](https://storage.googleapis.com/gweb-research2023-media/pubtools/5068.pdf)** - Global authorization system

### Machine Learning & Graph Processing
- **[TensorFlow](https://www.usenix.org/system/files/conference/osdi16/osdi16-abadi.pdf)** - Large-scale machine learning on heterogeneous systems
- **[Pregel](https://15799.courses.cs.cmu.edu/fall2013/static/papers/p135-malewicz.pdf)** - System for large-scale graph processing

### Content Delivery
- **[HALP](https://www.usenix.org/system/files/nsdi23-song-zhenyu.pdf)** - YouTube's content delivery network design
- **[Improving CDN Path Latencies](https://static.googleusercontent.com/media/research.google.com/en//archive/imc191/imc191.pdf)** - Performance optimization study

---

## Amazon

Papers on highly scalable, available cloud infrastructure and services.

- **[Dynamo](https://www.allthingsdistributed.com/files/amazon-dynamo-sosp2007.pdf)** - Highly available key-value store
- **[Amazon Aurora](https://assets.amazon.science/dc/2b/4ef2b89649f9a393d37d3e042f4e/amazon-aurora-design-considerations-for-high-throughput-cloud-native-relational-databases.pdf)** - Cloud-native relational database design
- **[Physalia](https://assets.amazon.science/c4/11/de2606884b63bf4d95190a3c2390/millions-of-tiny-databases.pdf)** - Managing millions of tiny databases
- **[Collaborative Filtering](https://www.cs.umd.edu/~samir/498/Amazon-Recommendations.pdf)** - Item-to-item recommendation algorithms

---

## Meta (Facebook)

Systems designed for massive social graph scale and real-time data processing.

### Storage & Databases
- **[TAO](https://www.usenix.org/system/files/conference/atc13/atc13-bronson.pdf)** - Facebook's distributed data store for the social graph
- **[Cassandra](https://www.cs.cornell.edu/projects/ladis2009/papers/lakshman-ladis2009.pdf)** - Decentralized structured storage system
- **[Gorilla](https://www.vldb.org/pvldb/vol8/p1816-teller.pdf)** - Fast, scalable, in-memory time series database
- **[Shard Manager](https://scontent.fccj6-1.fna.fbcdn.net/v/t39.8562-6/246905779_1558379681185166_3606269237190124509_n.pdf)** - Generic shard management framework

### Caching & Consensus
- **[Memcache](https://www.usenix.org/system/files/conference/nsdi13/nsdi13-final170_update.pdf)** - Scaling Memcache at Facebook
- **[FlexiRaft](https://www.cidrdb.org/cidr2023/papers/p83-yadav.pdf)** - Flexible Paxos quorum for cloud storage

### Data Processing & Analytics
- **[Hive](https://scontent.fccj6-2.fna.fbcdn.net/v/t39.8562-6/240821631_557956282118593_1903152843934808575_n.pdf)** - Data warehouse infrastructure built on Hadoop
- **[Prophet](https://peerj.com/preprints/3190v2.pdf)** - Forecasting at scale

### Infrastructure & Networking
- **[Twine](https://scontent.fccj6-1.fna.fbcdn.net/v/t39.8562-6/240836403_389005185950985_6091829722024266146_n.pdf)** - Unified cluster management system for large-scale services
- **[ServiceRouter](https://www.usenix.org/system/files/osdi23-saokar.pdf)** - Hyperscale and servicemesh architecture
- **[Thrift](https://thrift.apache.org/static/files/thrift-20070401.pdf)** - Scalable cross-language services development
- **[Millisampler](https://dl.acm.org/doi/pdf/10.1145/3517745.3561430)** - Network sampling at scale

### Monitoring & Debugging
- **[MineSweeper](https://arxiv.org/pdf/2010.09974)** - Root cause analysis for large-scale systems

---

## LinkedIn

Systems for professional networking, data processing, and graph traversal.

- **[Kafka](https://notes.stephenholiday.com/Kafka.pdf)** - Distributed streaming platform
- **[Finding n-hop Connections](https://www.usenix.org/system/files/conference/hotcloud13/hotcloud13-wang.pdf)** - Graph search at LinkedIn scale
- **[Magnet](https://www.vldb.org/pvldb/vol13/p3382-shen.pdf)** - Push-based shuffle service for large-scale data processing
- **[Detecting Fake Profiles](https://farid.berkeley.edu/downloads/publications/cvpr23b.pdf)** - Fighting fraud with machine learning

---

## Apache

Open-source distributed systems projects that power the industry.

- **[Hadoop (HDFS)](https://pages.cs.wisc.edu/~akella/CS838/F15/838-CloudPapers/hdfs.pdf)** - Distributed file system
- **[Apache Flink](https://asterios.katsifodimos.com/assets/publications/flink-deb.pdf)** - Stream and batch processing engine

---

## Other Notable Systems

Foundational papers on caching, scalability economics, and distributed databases.

- **[FoundationDB](https://www.foundationdb.org/files/fdb-paper.pdf)** - Distributed database with layered architecture
- **[Monolith](https://arxiv.org/pdf/2209.07663)** - Real-time recommendation system with collisionless embedding tables
- **[SIEVE Cache Eviction](https://junchengyang.com/publication/nsdi24-SIEVE.pdf)** - Simpler and more efficient than LRU
- **[Twitter Caching Strategies](https://www.usenix.org/conference/osdi20/presentation/yang)** - Large-scale distributed caching
- **[Netflix Multi-CDN](https://www.cs.princeton.edu/courses/archive/fall16/cos561/papers/NetFlix12.pdf)** - Improving video delivery performance
- **[Scalability! But at what COST?](https://www.usenix.org/system/files/conference/hotos15/hotos15-paper-mcsherry.pdf)** - Critical look at distributed systems overhead

---

## License

This is a curated list of publicly available research papers and resources. All papers remain under their original licenses.
