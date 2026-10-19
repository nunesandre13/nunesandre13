<div align="center">

# André Nunes

**Backend Engineering · Distributed Systems · Cloud Infrastructure**

MSc Computer Engineering @ **NOVA FCT** · Computer Engineering graduate @ **ISEL**  
Former Technical Support Engineer Intern @ **Cloudflare**

[LinkedIn](https://www.linkedin.com/in/andr%C3%A9-nunes-32131833a/) · [Email](mailto:andre.oliv.nunes@gmail.com) · [Projects ↓](#selected-projects)

</div>

---

### A little about me

I enjoy building software at the intersection of **backend engineering and infrastructure** — from designing APIs and service boundaries to understanding how systems behave under load, fail, recover, and communicate.

I studied Computer Engineering at **ISEL** and am now pursuing an MSc at **NOVA FCT**, with a particular interest in distributed systems and software engineering. During my internship at **Cloudflare**, I worked on troubleshooting edge and networking issues and built internal automation tooling using **Go, TypeScript, and Cloudflare Workers**.

Outside of coursework, I like building developer tools, experimenting with systems architecture, and working on projects where implementation details really matter.

## Selected projects

### 01 / [OmniAI Gateway & SDK](https://github.com/OmniAI-Gateway/project-management)

**A unified AI gateway and multiplatform SDK for interoperable LLM integrations.**  
`Kotlin Multiplatform` · `Ktor` · `MCP` · `OAuth2/OIDC` · `OpenTelemetry` · `SSE`

My bachelor's final project (**19/20**), built around an extensible architecture for routing, adapting, and operating requests across multiple LLM providers.

- **Interoperability:** provider-independent models and bidirectional adaptation between OpenAI, Anthropic, and Gemini APIs, including streaming responses.
- **Architecture & reliability:** ports-and-adapters design and a configurable request pipeline with authentication/authorization, rate limiting, circuit breaking, and provider fallback.
- **Tooling & observability:** MCP integration for tool invocation and external servers; OpenTelemetry instrumentation with Prometheus/Grafana for system visibility.
- **Cross-platform development:** Kotlin Multiplatform SDK targeting JVM and JavaScript, alongside a Ktor-based gateway.

**[Repository, documentation & architecture →](https://github.com/OmniAI-Gateway/project-management)**

### 02 / [Agent Execution Engine](https://github.com/nunesandre13/Agent-Execution-Engine)

**An MCP-powered execution engine for AI agents, with container-isolated workspaces.**  
`Go` · `Docker` · `MCP` · `Git` · `JSON-RPC`

A personal systems project exploring how to give agents useful execution capabilities while keeping filesystem changes explicit and inspectable.

- **Execution model:** exposes command execution and workspace operations through MCP over JSON-RPC/stdio.
- **Isolation:** Docker-based environments with read-only host mounts and separate writable workspaces.
- **Versioning:** Git-backed snapshots, diffs, restoration, and explicit application of changes.
- **Extensibility:** layered design with interchangeable sandbox and versioning providers.

**[Source code & technical README →](https://github.com/nunesandre13/Agent-Execution-Engine)**

### 03 / [Poker Dice — Web](https://github.com/nunesandre13/daw-poker-dice)

**A full-stack web implementation of Poker Dice.**  
`Kotlin` · `Spring Boot` · `PostgreSQL` · `JDBI` · `React` · `TypeScript` · `SSE`

Built the backend API and web frontend, combining persistent data with Server-Sent Events for real-time game updates. Academic project graded **19/20**.

**[Explore the project →](https://github.com/nunesandre13/daw-poker-dice)**

### 04 / [Poker Dice — Android](https://github.com/nunesandre13/pdm-poker-dice)

**A native Android client for the Poker Dice backend.**  
`Kotlin` · `Jetpack Compose` · `REST APIs` · `SSE`

Created a native mobile experience using Jetpack Compose, reusing the web project's backend through REST endpoints and real-time SSE updates. Academic project graded **20/20**.

**[Explore the Android app →](https://github.com/nunesandre13/pdm-poker-dice)**

## Technical skills

| Area | Technologies & concepts |
| --- | --- |
| **Languages** | Kotlin · Go · TypeScript · Java · C · JavaScript · SQL |
| **Backend & APIs** | Ktor · Spring Boot · REST APIs · SSE · MCP · JSON-RPC |
| **Frontend & mobile** | React · Jetpack Compose |
| **Databases & persistence** | PostgreSQL · Firestore · JDBI |
| **Cloud & developer tooling** | Docker · Cloudflare Workers · Git · GitHub · Azure · Terraform |
| **Networking & security** | TCP/IP · DNS · HTTP/TLS · OAuth 2.0 · OpenID Connect |
| **Observability** | OpenTelemetry · Prometheus · Grafana |
| **Engineering concepts** | Distributed Systems · Concurrency · Hexagonal Architecture · Fault Tolerance |

*Current interests: platform engineering, infrastructure automation, and production reliability.*

## Background

- **MSc in Computer Engineering** — NOVA FCT · 2026–2028 (expected)
- **BEng in Computer Engineering** — ISEL · 2026 · Final grade: **16/20**
- **Technical Support Engineer Intern** — Cloudflare · Summer 2026
- **Merit scholarship** — *Next Level Higher Education for All @ Politécnico de Lisboa* · 2024/2025

---

<div align="center">

*Interested in backend systems, cloud infrastructure, and the engineering that connects them.*

[Let's connect on LinkedIn](https://www.linkedin.com/in/andr%C3%A9-nunes-32131833a/)

</div>
