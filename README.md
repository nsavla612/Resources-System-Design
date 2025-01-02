# SYSTEM DESIGN INTERVIEW FORMAT

* Format
  * Functional
  * Non-Functional
  * Capacity Estimation
  * API
  * Entities
  * High level design
  * Component Design - Database
* Time Management
* Expected in mid-level and staff level.
* My Recommendations
  *  Understand the interviewer's perspective 

# CORE CONCEPTS

* Horinzontal Scaling vs Vertical Scaling
* HTTP / TCP
* API Design
* What is a distributed system ?
* Databases
  * Single Leader
  * Multi Leader
  * Leaderless
* Caching
* Data Serialization
* Synchronous vs Asynchronous
* Transactions
* ACID properties
* CAP theorem
* Load Balancing
* DNs Routing
* Fault Tolerance
* Orchestration vs Choreography
* Rollout and Deployment Statergies
* Sidecar proxy
* Data plane vs control plane
* Command Query Responsibility egregation (CQRS)
* Monitoring
* What is a microservice vs monolith ?
* http vs polling vs long polling vs websockets vs SSE ?
* What happens in a TCP Handshake ?
* Outbok Pattern
* Saga Pattern
* Scatter / Gather
* Inverted Indexes
* Consistent hashing
* Authentication Mechanisms.
* Fan-in vs Fan-out


# CORE COMPONENTS

* General Databases
  *  How to partition ? 
* Relational Databases
  * How to write SQL queries
  * How is acid implemented ?
  * What are isolation levels ?
  * What are concurrency protocols ?
  * Row oritend storage ?
  * what is a page and disk ?
  * What are various indexes ?
  * How are indexes implemented ? 
* NoSQL Key Value Databases
  * Column oriented storage - parquet 
* NoSQL Time Series Database
* NoSQL Graph Database
* S3 File Storage Database
* Single Leader failover
   * Leader elections 
* Single Leader Replication
    *  Paxos
    *  Chain Replication
    *  Repliucation Lag
    *  How to resolve conflicts ?
* LeaderLess Replication
  * Gossip Protocol
  * Quorums
  * Read Repairs
  * Hinted Handoff        
* Redis Cache
* AWS API Gateway
* ElasticSearch Search Servers
* Kafka MEssage Queue
* Real Time Updates
* CDN
* DNS and Geo-DNS
* Infrastruvutre as a code
* Cloudwatch Monitoring and Logging
* Zookeeper coordingation
* Lambda Serverless functions
* Change Data Captures
* Docker Containerization
* Kubernetes ORchestrations Services


# CASE STUDIES - EACH ONE HAS A SEPARATE MD FILE.

* Real Time Leaderboard
* Tiny URL


# QUESTIONS THAT CAN BE ASKED IN AN INTERVIEW

* What is backend vs frontend ?
* What is stateful vs stateles ?
* Baremetal vs cloud ?
* Why are we sharding based on region instead of hash / user ?



# OTHER VIDEOS OR BLOGS
