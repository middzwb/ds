# Distributed System

## consensus

* [ ] [Lamport Clock](time-clocks.pdf)

[Time Clocks and the Ordering of Events in a Distributed System 译文](http://duanple.com/?p=66)

>狭义相对论告诉我们时空中的事件并不存在一个始终如一的全序关系；不同的观察者对两个事件谁先发生可能具有不同的看法。当且仅当事件e2是由事件e1引起的时候，事件e1和e2之间才存在一个先后关系。

concurrent的事件在偏序中无法定义顺序；通过定义不同进程之间事件的顺序，将偏序扩展为全序

在外部系统介入后，逻辑时钟会产生“果先于因”的异常，因此引入物理时钟来满足“Strong Clock Condition”

[Lamport timestamp](https://en.wikipedia.org/wiki/Lamport_timestamp) -> [vector clock](https://en.wikipedia.org/wiki/Vector_clock)

* [ ] [关于Paxos的历史](http://duanple.com/?p=61)
* [ ] [paxos made simple](paxos-simple-copy.pdf)
* [ ] [Consensus Protocols: Paxos](https://www.the-paper-trail.org/post/2009-02-03-consensus-protocols-paxos/)
* [ ] [paxos made live](paxos-made-live.pdf)
* [ ] [paxos moderately complex](paxos-moderately-complex.pdf)
* [ ] [paxos lease](paxoslease.pdf)
* [ ] [the part-time parliament](the-part-time-parliament.pdf)
* [ ] [Viewstamped replication](vr.pdf)

[vr-revisit](vr-revisited.pdf)

* [ ] [raft](https://raft.github.io/)
* [ ] [zab](zab.pdf)

* [ ] [Consensus on Transaction Commit](consensus-on-transaction-commit.pdf)

* [ ] DHT

两篇关于分布式哈希表的介绍，[1](dht1.pdf), [2](dht2.pdf)

* [ ] [consistent hash](consistent-hashing-and-random-trees-distributed-caching-protocols-for-relieving-hot-spots-on-the-world-wide-web-technical-publication.pdf)

* [ ] [flake id](http://yellerapp.com/posts/2015-02-09-flake-ids.html)
* [ ] [’Cause I’m Strong Enough](cise.pdf)

## lock

* [ ] [chubby](chubby.pdf)

[The Chubby lock service for loosely-coupled distributed systems](https://www.youtube.com/watch?v=PqItueBaiRg&ab_channel=DataCouncil)

* [ ] [Distributed locks with Redis](https://redis.io/topics/distlock)

## storage

* [ ] [PacificA: Replication in Log-Based Distributed Storage Systems](pacifica.pdf)
* [ ] [log](https://engineering.linkedin.com/distributed-systems/log-what-every-software-engineer-should-know-about-real-time-datas-unifying)
* [ ] [data location](data-location.pdf)
* [ ] [Better I/O Through Byte-Addressable, Persistent Memory](bpfs.pdf)
* [ ] [petal](petal.pdf)

### filesystem

* [ ] [Sinfonia: a new paradigm for building scalable distributed systems](sinfonia.pdf)
* [ ] [GFS](gfs.pdf)
* [ ] [Colossus](https://levy.at/blog/22)
* [ ] [Finding a needle in Haystack: Facebook’s photo storage](facebook-haystack.pdf)
* [ ] [seaweedfs](https://github.com/chrislusf/seaweedfs)
* [ ] [Analysis of Six Distributed File Systems](a_survey_of_dfs.pdf)
* [ ] [f2fs](f2fs.pdf)
* [ ] [btrfs](btrfs.pdf)
* [ ] [frangipani](thekkath-frangipani.pdf)

### kv store/object store

* [ ] [LSM-tree](lsmtree.pdf)
* [ ] [big table](bigtable-osdi06.pdf)
* [ ] [craq](craq.pdf)
* [ ] [azure](azure.pdf)
* [ ] [spanner](spanner.pdf)
* [ ] [Dynamo: Amazon’s Highly Available Key-value Store](amazon-dynamo-sosp2007.pdf)
* [ ] [Cassandra - A Decentralized Structured Storage System](cassandra.pdf)
* [ ] [f4](f4.pdf)

### DB

* [ ] [f1](f1.pdf)

## open-system

* [ ] bitcoin
* [ ] blockstack

## design

* [ ] [Introduction to Distributed System Design](http://www.hpcs.cs.tsukuba.ac.jp/~tatebe/lecture/h23/dsys/dsd-tutorial.html)
* [ ] [Designs, Lessons and Advice from Building Large Distributed Systems](design-ds.pdf)
* [ ] [what we talk about when we talk about distributed systems](https://alvaro-videla.com/2015/12/learning-about-distributed-systems.html)
* [ ] [Design a Cache System](http://blog.gainlo.co/index.php/2016/05/17/design-a-cache-system/)

[tiny-lfu](cache-policy.pdf)

* [ ] [Distributed systems theory](https://www.the-paper-trail.org/post/2014-08-09-distributed-systems-theory-for-the-distributed-systems-engineer/)
* [ ] [The Tail at Scale](https://research.google/pubs/pub40801/)

## OS

* [ ] [Operating Systems Study Guide](http://faculty.salina.k-state.edu/tim/ossg/index.html)
* [ ] [Computer Science from the Bottom Up](http://www.bottomupcs.com/index.xhtml)
* [ ] [Operating Systems: Three Easy Pieces](http://pages.cs.wisc.edu/~remzi/OSTEP/)
* [ ] [Memory Systems Cache, DRAM, Disk](memory_systems_cache_dram_disk.pdf)
* [ ] [What are some high performance TCP hacks?](https://www.quora.com/What-are-some-high-performance-TCP-hacks)

## MISC

[Distributed systems for fun and profit](http://book.mixu.net/distsys/index.html)

[papers we love](https://github.com/papers-we-love/papers-we-love/tree/master/distributed_systems)

DDIA

[Distributed Systems and the End of the API](https://writings.quilt.org/2014/05/12/distributed-systems-and-the-end-of-the-api/)

[Replication, atomicity and order in distributed systems](http://afeinberg.github.io/2011/06/17/replication-atomicity-and-order-in-distributed-systems.html)

[papers](http://duanple.com/?p=170)

[lock-free](lockfree.pdf)

[A Distributed Systems Reading List](https://dancres.github.io/Pages/)

[ReadingList](http://pages.cs.wisc.edu/~swift/classes/cs739-fa14/wiki/pmwiki.php/Main/ReadingList)

[5-minute rule](5_min_rule_sigmod.pdf)
