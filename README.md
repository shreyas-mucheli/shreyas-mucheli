# Shreyas Mucheli

<p align="center">
  Backend & Systems Engineer focused on distributed systems, high-throughput media platforms, and cloud infrastructure.
</p>

<p align="center">
  <a href="mailto:m.d.shreyas210@gmail.com">Email</a>
  ·
  <a href="https://www.linkedin.com/in/shreyas-mucheli">LinkedIn</a>
  ·
  <a href="https://github.com/shreyas-mucheli">GitHub</a>
  ·
  <a href="https://x.com/shreyasmucheli">Twitter</a>
  ·
  <a href="https://www.instagram.com/mdshreyas">Instagram</a>
</p>

## About

I build backend and systems services that stay fast, reliable, and operable under production load. With 3+ years of experience across distributed systems, event-driven architectures, and cross-platform native software, I focus on system performance, scalability, and end-to-end technical ownership.

My work has centered on:

- Building high-throughput backend services and systems in **Java**, **Python**, and **Rust**
- Architecting asynchronous and event-driven workflows with **Kafka**, **Google Cloud Pub/Sub**, and **KEDA**
- Optimizing database access patterns and query execution (MongoDB, PostgreSQL, Neo4j, QDrant), slashing latencies from multi-second bottlenecks to sub-200ms paths
- Engineering adaptive video streaming pipelines (HLS/DASH via FFmpeg & Shaka Packager) and live-streaming workflows over RTMPS
- Developing native cross-platform agents and components with Rust via JNI/FFI
- Driving platform reliability, CI/CD automation, and observability with Prometheus, Grafana, and Loki

## Work Experience

### Senior Software Engineer — ShriAikyam (Aikyam)
*February 2026 – August 2026 | Bengaluru, India*

*Faith-based social platform for temple discovery, live darshan, spiritual learning, and video/live-streaming experiences.*

- Built the backend media platform from scratch using **Java**, **Spring Boot**, **Python**, **Kafka**, **Kubernetes**, and **KEDA**, supporting asynchronous video transcoding and live-streaming workflows with **Cloudflare R2** for media storage.
- Engineered an adaptive-bitrate video pipeline using **FFmpeg** and **Shaka Packager** to generate multiple HLS renditions, reducing playback startup latency from **5.8s to under 500ms**.
- Built end-to-end live-streaming workflows over **RTMPS** and **Cloudflare**, integrating Android broadcasting and secure stream lifecycle management.
- Re-architected feed entity resolution across MongoDB collections, replacing per-post N+1 lookups with batched parallel fetches and in-memory mapping, reducing feed generation latency from **over 7s to under 200ms**.
- Analyzed MongoDB execution plans and introduced a targeted compound index to optimize user profile retrieval, reducing API latency from approximately **5s to under 150ms**.
- Designed the architecture for an automated text and image moderation service using **Python**, **FastAPI**, **Kafka**, **Glin Profanity**, and **CLIP** models, guiding a developer through implementation.
- Led CI/CD and observability initiatives using **GitHub Actions**, **Helm**, **ClickStream**, **Prometheus**, **Grafana**, and **Loki**.
- Mentored engineers and interns, led architecture discussions, conducted technical interviews, and drove cross-functional code reviews.

### Software Engineer 2 — ShepherdWatch
*February 2024 – July 2025 | Bengaluru, India*

*Enterprise endpoint security and Mobile Device Management (MDM) platform for Android, Windows, Linux, and macOS devices.*

- Designed and maintained ShepherdWatch's Android agent, integrating a cross-platform **Rust** core with Android through **JNI/FFI** for native device functionality and code reuse.
- Built **Java-Rust-based policy engine** and device locator components, implementing remote wipe, device lock/reset, geofencing, password policies, and location tracking using Wi-Fi and cellular data.
- Led backend development for Android Enterprise MDM, building **Java/Spring Boot** microservices for device enrollment, policy management, compliance, and telemetry ingestion.
- Designed bidirectional device communication and real-time policy synchronization using **Android Management API** and **Google Cloud Pub/Sub**.
- Developed Rust and Java telemetry components collecting **150+ endpoint metrics**, integrating **Prometheus**, **Grafana**, and **Loki** for monitoring and diagnostics.
- Implemented a private app distribution system enabling silent application installation and remote management on enrolled Android devices.
- Automated cross-platform build, testing, and deployment using **Ansible** and **GitLab Runners**, saving 10–15 hours of manual validation effort per week.
- Served as technical lead for AOSP-based **ShepherdOS** and Android Enterprise initiatives, driving architecture and contributing to **Google Silver Partner certification**. Delivered technical PoCs and onboarded 5+ enterprise clients.

### Founding Software Engineer — SmartGraph
*January 2023 – December 2023 | Bengaluru, India*

*Social graph platform helping early-stage startups discover leads, funding opportunities, and strategic partnerships.*

- Led the migration of performance-critical backend services from Python to **Rust** using **Tokio**, improving execution efficiency, runtime reliability, and performance predictability.
- Designed integrations with **LinkedIn** and **Twitter APIs** to ingest relationship data and build professional social graphs, supporting onboarding of 300+ beta users within 4 months.
- Built high-throughput **Rust** and **Python** NLP pipelines for entity resolution and lead scoring, improving recommendation relevance by **40%**.
- Modeled people, companies, investors, and their relationships using **Neo4j**, enabling graph traversal for relationship mapping and lead discovery.
- Integrated **QDrant** vector database to store entity and profile embeddings, enabling semantic similarity search and more relevant recommendations.
- Improved service reliability through comprehensive test coverage, production debugging, and root-cause analysis; contributed to system architecture, product strategy, and MVP development.

## Core Stack & Skills

- **Languages:** Java, Python, Rust, Shell, Bash
- **Backend & Systems:** Spring Boot, FastAPI, Tokio, Async-std, Microservices, REST APIs, Multithreading, Concurrency, Memory Safety
- **Distributed Systems:** Apache Kafka, Google Cloud Pub/Sub, KEDA, ZooKeeper, Event-Driven Architecture
- **Databases & Search:** PostgreSQL, MongoDB, Redis, Neo4j, QDrant, Elasticsearch
- **Cloud & Infrastructure:** Kubernetes, Docker, Helm, AWS, GCP, Cloudflare (R2), Ansible, Terraform
- **CI/CD & Observability:** GitHub Actions, GitLab Runners, Maven, Gradle, Cargo, ClickStream, Prometheus, Grafana, Loki, Sentry
- **Media & Streaming:** FFmpeg, Shaka Packager, HLS, DASH, RTMPS, Video Transcoding, Live Streaming
- **AI/ML & Data:** GenAI, LLMs, RAG, MCP, Vector Embeddings, TensorFlow, GANs, CLIP, Prompt Engineering, Airbyte, Apache Superset, Trino
- **Engineering Practices:** System Design (HLD/LLD), Design Patterns, Profiling, Benchmarking, API Optimization, Performance Engineering

## Publications & Research

- **A Comparative Analysis on the Effectiveness of GAN Performance**  
  *International Conference on Computing and Networking Technology (ICCNT) — IEEE*
- **A Study on Machine Learning Based Diabetic Retinopathy**  
  *International Conference on Inventive Computation Technologies (ICICT) — IEEE*

## Education

- **Bachelor of Engineering (B.E.), Computer Science and Engineering**  
  *Visvesvaraya Technological University (Dr. Ambedkar Institute of Technology, Bengaluru)*  
  *CGPA: 8.67 | 2019 – 2023*

## Connect

- **LinkedIn:** [linkedin.com/in/shreyas-mucheli](https://www.linkedin.com/in/shreyas-mucheli)
- **GitHub:** [github.com/shreyas-mucheli](https://github.com/shreyas-mucheli)
- **Twitter / X:** [@shreyasmucheli](https://x.com/shreyasmucheli)
- **Instagram:** [mdshreyas](https://www.instagram.com/mdshreyas)
- **Email:** [m.d.shreyas210@gmail.com](mailto:m.d.shreyas210@gmail.com)
