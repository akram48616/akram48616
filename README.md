# Hi, I'm Shaik Akram

**Java Backend Developer | Spring Boot | Kafka | Redis | Microservices**
 
MCA graduate (CGPA 9.0/10) who builds REST APIs and distributed backend services, then tests, benchmarks and containerizes them. I like problems where things fail halfway (crashed workers, duplicate messages, stale caches) and the system has to recover correctly.

- 💼 **Looking for:** Full-time Java Backend Developer / Java Developer roles (fresher) in Hyderabad, Bangalore, Mysore and Pune
- 🎓 **Education:** MCA, VEMU Institute of Technology
- 🔭 **Currently building:** [FlowForge](https://github.com/akram48616/flowforge), a distributed workflow orchestration platform
- 🌱 **Learning:** AWS, Microservices, System Design
- 🧩 **Practice:** [LeetCode](https://leetcode.com/u/akram_codes/), 190 problems solved
- 🌐 **Portfolio:** [akram-portfolio-ivory.vercel.app](https://akram-portfolio-ivory.vercel.app/)
- 📄 **Know about my experiences:** [Shaik_Akram_Java_Backend_Developer.pdf](https://github.com/akram48616/akram48616/blob/main/Shaik_Akram_Java_Backend_Developer.pdf)
- 📫 **Contact:** [akramakrama538@gmail.com](mailto:akramakrama538@gmail.com) · [LinkedIn](https://www.linkedin.com/in/shaik-akram-516272300/)

---

## 🚀 Featured Projects

### 🔹 [FlowForge](https://github.com/akram48616/flowforge): Distributed Workflow Orchestration

A microservices platform for defining and running multi-step workflows with dependency resolution, retries and failure recovery.
 
- **Cycle detection:** DFS-based check rejects circular workflow definitions at creation time
- **No duplicate execution:** Redis distributed lock (`SET NX` + Lua token-verified unlock) stops concurrent workers from running the same task
- **Fault tolerance:** exponential-backoff retries, dead-letter queue routing, and a scheduler that re-queues tasks stuck in `DISPATCHED`
- **Failure-tested:** killed workers and interrupted Kafka mid-execution in Docker, then verified recovery with no duplicate completion
- **Scaling and tests:** Kafka consumer groups for horizontal scaling, 30 unit tests and 2 Testcontainers integration tests
- **Docs:** [Architecture](https://github.com/akram48616/flowforge#architecture) · [Run locally](https://github.com/akram48616/flowforge#running-it) · [Verified failure modes](https://github.com/akram48616/flowforge#verified-failure-modes)
- **Tech:** Java 17 · Spring Boot · Kafka · Redis · MySQL · Eureka · Spring Cloud Gateway · Resilience4j · Docker · Testcontainers
### 🔹 [Library Management API](https://github.com/akram48616/library-api)

Containerized REST API for library operations with secure, role-based access.

 
- **Security:** JWT access and refresh tokens with rotation, logout blacklisting, `@PreAuthorize` role checks
- **Performance:** Redis caching improved the book-listing endpoint from ~30 to ~160 req/s and p95 latency from 2.9 s to under 0.4 s (k6, 50 virtual users, 60 s, local Docker)
- **Quality:** 30+ tests with JUnit 5, Mockito, MockMvc and DataJpaTest; Docker Compose setup
- **Docs:** [Setup and benchmark](https://github.com/akram48616/library-api#performance-redis-caching)
- **Tech:** Java 17 · Spring Boot · Spring Security · MySQL · Redis · Docker · Swagger/OpenAPI

### 🔹 [E-Commerce Backend](https://github.com/akram48616/EcommerceBackend)

Backend for products, carts, orders, payments and analytics.
 
- **Payments:** Razorpay order creation, payment verification, transaction tracking and webhook handling
- **Auth:** JWT with refresh-token rotation, logout blacklisting, BCrypt password hashing
- **Caching and reports:** Redis caching with eviction on updates; sales analytics, top-product and low-stock reports; async email notifications
- **Docs:** [API documentation](https://github.com/akram48616/EcommerceBackend#-api-documentation) (Swagger/OpenAPI)
- **Tech:** Java 17 · Spring Boot 3.5 · Spring Security · MySQL · Redis · Razorpay
---
## 🛠️ Tech I Work With

 
| Area | Technologies |
|---|---|
| **Language** | Java 17, SQL |
| **Backend** | Spring Boot, Spring MVC, Spring Security, Spring Data JPA, Hibernate, REST APIs, JWT, RBAC |
| **Microservices** | Spring Cloud, Eureka, Spring Cloud Gateway, Resilience4j |
| **Messaging** | Apache Kafka (consumer groups, dead-letter queues, retry and recovery) |
| **Data and caching** | MySQL, Redis |
| **Testing** | JUnit 5, Mockito, MockMvc, Testcontainers, k6 |
| **Tools and DevOps** | Docker, Docker Compose, Git, Maven, Postman, Linux, Swagger/OpenAPI |
 
---

<p align="left">
  <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/java/java-original.svg" width="40" height="40" alt="Java"/>
  <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/spring/spring-original.svg" width="40" height="40" alt="Spring"/>
  <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/apachekafka/apachekafka-original.svg" width="40" height="40" alt="Kafka"/>
  <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/redis/redis-original.svg" width="40" height="40" alt="Redis"/>
  <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/mysql/mysql-original.svg" width="40" height="40" alt="MySQL"/>
  <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/docker/docker-original.svg" width="40" height="40" alt="Docker"/>
  <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/git/git-original.svg" width="40" height="40" alt="Git"/>
  <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/linux/linux-original.svg" width="40" height="40" alt="Linux"/>
</p>

---
## 📊 Most Used Languages
<p align="left">
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=akram48616&layout=compact&theme=tokyonight&hide_border=true&langs_count=5&hide=html,css" alt="Most used languages"/>
</p>
---

## 🔗 Connect

[LinkedIn](https://www.linkedin.com/in/shaik-akram-516272300/) · [LeetCode](https://leetcode.com/akram_codes/) · [GeeksforGeeks](https://www.geeksforgeeks.org/profile/akramakr7tx6/) · [Portfolio](https://akram-portfolio-ivory.vercel.app/)
