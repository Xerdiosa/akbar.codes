---
title: "About"
date: 2026-04-22T23:00:00+08:00
draft: false
---

My name is Muhammad Aulia Akbar, senior software engineer at Shopee.
I focus on back-end engineering, mainly in Go.

## Experience

### **[Shopee](https://shopee.com)** - *Software Engineer (Promoted to Senior Engineer in 2025)*

August 2022 - Present\
Backend engineer in the Order Payment domain, primary owner (PIC) of refund system services, responsible for reliability, feature delivery, and operations across multiple regions.

- Designed a workaround for incompatible payment state machines, enabling safe payment method switching and unblocking feature delivery
- Built RCV File Manager service from scratch (cloud storage, encryption, HTML->PDF pipeline), automating Brazil customs form (RCV) collection and eliminating manual email-based operations
- Led rollout of middleware authentication across 12 services / 10 regions (Kafka, Redis, Elasticsearch, etcd) with near-zero downtime
- Designed high-throughput data pipeline for Elasticsearch migration, achieving ~60k-80k writes/sec and supporting large-scale indexing workloads
- Improved system performance and stability:
  - Reduced CPU bottlenecks (~100% -> ~80%) via load balancing improvements
  - Reduced deployment failure rate from ~25% to near 0%
- Designed scalable refund data archiving solution across ~20,000 DB shards with prioritization and deduplication strategy
- Drove technical debt reduction (e.g., refund notification deprecation, clearing linter warnings) and improved system maintainability
- Collaborated with cross-functional teams across regions to deliver complex distributed system changes
- Tech stack: Go, Kafka, Redis, Elasticsearch, Kubernetes, MySQL, Protobuf

### **[GudangAda](https://gudangada.com)** - *Software Engineer Intern*

Jul 2021 - Jul 2022\

- Developed a Kubernetes Operator (Go) to automate service deployment workflows
- Reduced deployment complexity and improved developer experience for internal Kubernetes services
- Implemented API logic for managing infrastructure resources programmatically

### **[Bareksa](https://bareksa.com)** - *Software Engineer Intern*

June 2020 - June 2021\

- Built and maintained REST APIs using Go and Node.js for fintech applications
- Implemented caching mechanisms (Redis) to improve system performance
- Added backend event tracking for analytics and monitoring

### **[SIRCLO](https://sirclo.com)** - *Software Engineer Intern*

June 2019 - August 2019\

- Developed backend features in Go for e-commerce systems
- Implemented REST APIs and handled partner API integration & error mapping
- Debugged and resolved production issues
