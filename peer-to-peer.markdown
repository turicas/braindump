# Peer-to-peer

- What are [peer-to-peer networks](https://en.wikipedia.org/wiki/Peer-to-peer)
- [Peer-to-peer foundation](http://p2pfoundation.net/)


## Proeminent Networks

- [Napster](https://en.wikipedia.org/wiki/Napster) (26.4M users in 2001)
- [Gnutella](https://en.wikipedia.org/wiki/Gnutella) (3M in 2006)
- [FastTrack](https://en.wikipedia.org/wiki/FastTrack) (2.4M concurrent users
  in 2003)
- [Bitcoin](https://bitcoin.org/bitcoin.pdf) (protocol's whitepaper)
- [BitTorrent](http://www.bittorrent.org/beps/bep_0003.html) protocol
  specification (~52k transactions per day, May 2014)
- [BitMessage](https://bitmessage.org/) (~20k users in Jan 2014)
- Twister: a peer-to-peer microblogging network (7.6k known peers in May 2014)
	- [White paper](http://arxiv.org/pdf/1312.7152v1.pdf)
	- [Website](http://twister.net.co/)
- [Coral CDN](http://www.coralcdn.org/)
- [Freenet](https://freenetproject.org/), distributed anonymous information
  storage


## Theory

- [Steven Gordon's lecture on peer-to-peer
  networks](https://www.youtube.com/watch?v=gn95YTkPoZI)
- [Bootstrapping of P2P Networks](http://grothoff.org/christian/bootstrap.pdf)


### Distributed Hash Tables

"Original" DHT protocols:

- [CAN](http://en.wikipedia.org/wiki/Content_addressable_network)
- [Chord](http://en.wikipedia.org/wiki/Chord_project)
- [Pastry](http://en.wikipedia.org/wiki/Pastry_%28DHT%29)
- [Tapestry](http://en.wikipedia.org/wiki/Tapestry_%28DHT%29)

Other:

- [Koorde](http://en.wikipedia.org/wiki/Koorde)
- [Kademlia](http://pdos.csail.mit.edu/~petar/papers/maymounkov-kademlia-lncs.pdf)
- [Mainline DHT](http://en.wikipedia.org/wiki/Mainline_DHT) (BitTorrent's DHT,
  Kademlia-based)


### Other

- [Electric routing](http://arxiv.org/abs/0909.2859)
- [Swarm Intelligence](http://en.wikipedia.org/wiki/Swarm_intelligence)


## Useful Implementations

### General

- [entangled](http://entangled.sourceforge.net), Python with twisted
- [Chimera](http://current.cs.ucsb.edu/projects/chimera/index.html)
- [YaCy peer-to-peer search network](http://yacy.de/)
- [SNAP](http://snap.objectweb.org/)
- [P-Grid](http://en.wikipedia.org/wiki/P-Grid)
- [GlusterFS](http://www.gluster.org/)
- [HDFS: Hadoop Distributed FileSystem](http://www.aosabook.org/en/hdfs.html)
- [FreeHaven](http://www.freehaven.net/overview.html), distributed data storage
- [GoCircuit](https://github.com/gocircuit/circuit)


### DHT

- [PyDHT](https://github.com/isaaczafuta/pydht/blob/master/pydht/pydht.py)
- [Kademlia implementation in Python](https://github.com/bmuller/kademlia)
  - Uses [RPC over UDP](https://github.com/bmuller/rpcudp)


### Hash Table Libraries (not distributed)

- [BDB](https://en.wikipedia.org/wiki/Berkeley_DB)
	- [The Architecture of Open Source Applications: Berkeley
	DB](http://www.aosabook.org/en/bdb.html)
- [LevelDB](https://code.google.com/p/leveldb/)
- [bitcask](http://downloads.basho.com/papers/bitcask-intro.pdf) (white paper)
- [Python 3 dbm module](https://docs.python.org/3/library/dbm.html)


### Distributed Key-Value Stores

- [Amazon
  Dynamo](http://www.allthingsdistributed.com/files/amazon-dynamo-sosp2007.pdf)
  (white paper, theory)
- [Riak](http://basho.com/riak/) (free/libre software implemented in Erlang)


## Simulation

- [OverSim](http://en.wikipedia.org/wiki/OverSim)
- [SimGrid](http://en.wikipedia.org/wiki/SimGrid)
- [PlanetLab](https://www.planet-lab.org/)


## Attacks

- [Sybil attack](https://en.wikipedia.org/wiki/Sybil_attack)


## NAT Traversal

Types of Network Address Translation implementations:

- [Full-cone NAT](http://en.wikipedia.org/wiki/Full_cone_NAT#Full-cone_NAT)
- [Restricted-cone NAT](http://en.wikipedia.org/wiki/Restricted_cone_NAT#Restricted-cone_NAT)
- [Port-restricted-cone NAT](http://en.wikipedia.org/wiki/Port_restricted_cone_NAT#Port-restricted_cone_NAT)
- [Symmetric NAT](http://en.wikipedia.org/wiki/Symmetric_NAT#Symmetric_NAT)

What is [NAT Traversal](http://en.wikipedia.org/wiki/NAT_traversal).


### Papers

- [State of P2P Communication across NATs](http://tools.ietf.org/html/rfc5128)
- [A NAT Traversal Mechanism for P2P
  Networks](http://www.uni-kassel.de/eecs/fileadmin/datas/fb16/Fachgebiete/UC/papers/wacker-nat-traversal.pdf)
- [NAT Traversal Techniques and P2P
  Applications](http://www.tml.tkk.fi/Publications/C/18/hu.pdf)


### NAT Traversal Techniques

- [STUN](http://en.wikipedia.org/wiki/STUN)
- [ICE](http://tools.ietf.org/html/rfc5245)
- [TURN](http://en.wikipedia.org/wiki/Traversal_Using_Relay_NAT)
- [UPnP](http://en.wikipedia.org/wiki/Universal_Plug_and_Play)


## Infrastructure Protocols (not peer-to-peer)

- [Serval](http://www.serval-arch.org/faq/)
- [uTP](http://www.bittorrent.org/beps/bep_0029.html) (BitTorrent's own
  protocol for better congestion control than TCP)
- [IP Multicast](https://en.wikipedia.org/wiki/IP_multicast)
