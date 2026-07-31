# Maruhsoft — Software Engineer · Cloud Infrastructure & Systems Security

Architecting high-availability distributed systems, automated CI/CD pipelines, and secure cloud environments—integrating scalable full-stack applications with AI/ML platforms.

---

## Technical Summary

- **Distributed Systems & Full-Stack** — Design and implementation of microservices and event-driven architectures using high-throughput backend services and reactive frontend platforms.
- **DevOps & Infrastructure Engineering** — Implementation of Infrastructure as Code (IaC), zero-downtime deployment pipelines, container orchestration, and multi-region failover systems.
- **Cybersecurity & Hardening** — DevSecOps practices, automated static/dynamic code analysis, zero-trust network access (ZTNA), identity and access management (IAM), and secrets management.
- **Artificial Intelligence & Machine Learning** — Integration of LLMs, model deployment via low-latency REST/gRPC endpoints, and data preprocessing pipelines.

---

## Technical Capabilities

| Category | Technologies & Tools |
| :--- | :--- |
| **Primary Languages** | TypeScript, JavaScript, Python, Go, SQL, Bash |
| **Frontend Frameworks** | React, Next.js, Redux Toolkit, Tailwind CSS, HTML5 / CSS3 |
| **Backend & Runtime** | Node.js, Express, FastAPI, Django, REST, GraphQL, gRPC |
| **Databases & Caching** | PostgreSQL, MySQL, Redis, MongoDB, Elasticsearch |
| **Cloud Infrastructure** | AWS, GCP |
| **DevOps & Orchestration** | Docker, Kubernetes, Terraform, Helm, GitHub Actions, GitLab CI |
| **Security & Observability** | OWASP, HashiCorp Vault, Datadog, Prometheus, Grafana |
| **AI / ML & Data** | PyTorch, TensorFlow, Pandas, NumPy, OpenAI API, LangChain |

---

## Architectural Focus Areas

### Cloud-Native Systems Design

**Objective:** Ensure maximum availability, low latency, and horizontal scalability across modern cloud topologies.

- Fault-tolerant microservice architectures with clear domain boundaries (DDD / bounded contexts).
- Stateless application tiers backed by scalable persistence and eventual consistency patterns.
- API Gateway for traffic shaping, rate limiting, circuit breaking, and centralized auth.
- Multi-region active-active topologies with automated failover and cross-region replication.

### DevSecOps & Continuous Delivery

**Objective:** Automate delivery pipelines while maintaining a rigorous security posture.

- Immutable infrastructure (Terraform), containerization, and GitOps workflows.
- CI/CD with SAST/DAST, dependency scanning, artifact signing, and SBOM generation.
- Progressive delivery: canary releases, blue-green deployments, and feature-flag rollouts.

### AI Platform Integration

**Objective:** Bridge enterprise software with intelligent algorithmic engines.

- Low-latency inference endpoints (FastAPI, gRPC) and batching strategies for throughput.
- Continuous ingestion pipelines, feature engineering, evaluation, and model versioning.
- LLM agents, RAG pipelines, and observability for cost and quality.

---

## High-Level System Design (overview)

```text
┌───────────────────┐      ┌───────────────────┐      ┌───────────────────┐
│  Client Layer     │ ───► │  API Gateway      │ ───► │  Microservices    │
│  (React / Next)   │      │  (Rate Limit,     │      │  (Node / Go / Py) │
│                   │      │   Auth, Circuit   │      │                   │
└───────────────────┘      │   Breaking)       │      └─────────┬─────────┘
                           └───────────────────┘                │
                                                                 ▼
┌───────────────────┐      ┌───────────────────┐      ┌───────────────────┐
│  Persistence      │ ◄─── │  Caching Layer    │ ◄─── │  Message Queue    │
│  (PostgreSQL)     │      │  (Redis)          │      │  (Kafka / Rabbit) │
└───────────────────┘      └───────────────────┘      └───────────────────┘
         ▲                                                    │
         │              Observability Stack                   │
         │         (Prometheus · Grafana · Datadog)           │
         └────────────────────────────────────────────────────┘
```

---

## Engineering Standards & Principles

```json
{
  "engineering_principles": {
    "code_quality": "Strict type safety, high test coverage, automated linting, and conventional commits.",
    "security": "Least-privilege access, encryption at rest and in transit, secrets management, and continuous vulnerability scanning.",
    "scalability": "Stateless design, efficient caching, horizontal scaling, and back-pressure handling.",
    "reliability": "Comprehensive monitoring, alerting, automated failover, and chaos engineering practices.",
    "observability": "Structured logging, distributed tracing, and actionable metrics across the full stack."
  }
}
```

---

## GitHub & Activity Metrics

I used a few third-party widgets to show GitHub statistics. Some of these services can occasionally go offline (Heroku deprecation, rate limits, etc.).

<!-- Primary (common) widgets -->
<p align="left">
  <img src="https://github-readme-stats.vercel.app/api?username=Maruhsoft&show_icons=true&theme=dark&include_all_commits=true&count_private=true&hide_border=true" alt="GitHub Stats" height="165"/>
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=Maruhsoft&layout=compact&theme=dark&hide_border=true&hide=html,css" alt="Top Languages" height="165"/>
</p>

<!-- Optional / sometimes unreliable widgets: keep them commented as alternatives -->
<!--
<p align="left">
  <img src="https://github-readme-streak-stats.herokuapp.com/?user=Maruhsoft&theme=dark&hide_border=true" alt="GitHub Streak" height="165"/>
</p>
-->

<!-- Fallback badges (Shields.io) -->
<p align="left">
  <img src="https://img.shields.io/github/followers/Maruhsoft?label=Followers&style=flat&color=blue" alt="Followers" />
  <img src="https://img.shields.io/github/stars/Maruhsoft?label=Stars&style=flat&color=yellow" alt="Stars" />
  <img src="https://img.shields.io/github/issues/Maruhsoft/Maruhsoft?label=Open%20Issues&style=flat&color=red" alt="Open issues" />
</p>

---

## Core Focus Repositories

| Repository | Focus Area | Stack |
| :--- | :--- | :--- |
| `enterprise-cloud-sec` | Infrastructure as Code & Hardening | Terraform, AWS / GCP |
| `high-throughput-api-gateway` | Systems Engineering & Edge Services | Go, Redis |
| `ai-microservice-pipeline` | AI / ML Deployment & Inference | Python, FastAPI |

---

## Professional Development & Focus

- Advanced Distributed Systems Patterns & Event Sourcing
- Zero-Trust Cloud Architecture & Security Compliance (SOC 2, ISO 27001 alignment)
- High-Performance Systems with Go and Rust
- Model Fine-Tuning, Quantization, and LLM Agent Frameworks
- Observability-driven development and production reliability engineering

---

## Contact & Links

- **LinkedIn:** https://www.linkedin.com/in/maruh-akporowho-647159124
- **Email:** [maruhsoft@gmail.com](mailto:maruhsoft@gmail.com)

<sub>*Profile repository maintained with CI/CD workflows.*</sub>
