# System Design Roadmap — Fresher Level

You do **not** need senior-engineer system design depth for most fresher interviews. Focus on learning how to break a problem into sensible components and discuss trade-offs.

## 1. Foundations
- Functional vs non-functional requirements
- Scalability basics
- Availability and reliability
- Latency vs throughput
- Vertical vs horizontal scaling

Reference: [System Design Cheatsheet](../System-Design/System-Design-Cheatsheet.md)

## 2. Core Building Blocks
- Client / server
- Load balancer
- Application server
- Database
- Cache
- Queue
- Object/file storage
- CDN basics

Reference: [System Design Notes](../System-Design/System-Design-Notes.pdf)

## 3. Databases and Scaling
- SQL vs NoSQL trade-offs
- Replication basics
- Partitioning / sharding intuition
- Read replicas
- Caching strategies

## 4. API Design
- REST basics
- Resource-oriented endpoints
- Authentication / authorization basics
- Pagination
- Rate limiting concept

## 5. Design Practice
Start with simple systems:
- URL shortener
- Pastebin
- File upload service
- Simple chat system
- Basic notification service

Use [System Design Interview Questions](../System-Design/System-Design-Interview-Questions.pdf) after learning the building blocks.

## Interview Method
1. Clarify requirements.
2. Estimate scale only as needed.
3. Propose a simple architecture.
4. Explain data flow.
5. Identify bottlenecks.
6. Add scaling components only when justified.
7. Discuss trade-offs.

The goal is structured thinking, not memorizing architecture diagrams.
