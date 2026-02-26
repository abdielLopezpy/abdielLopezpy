<div align="center">

# `> Abdiel Lopez_`

<img src="https://readme-typing-svg.demolab.com?font=Fira+Code&size=22&pause=1000&color=00FF41&center=true&vCenter=true&multiline=true&repeat=true&width=600&height=100&lines=%F0%9F%94%A7+Software+Architect;%E2%9A%A1+CRDTs+%7C+Local-First+%7C+Edge+Computing+%7C+IoT" alt="Typing SVG" />

[![Rust](https://img.shields.io/badge/Rust-000000?style=for-the-badge&logo=rust&logoColor=white)](https://www.rust-lang.org)
[![Flutter](https://img.shields.io/badge/Flutter-02569B?style=for-the-badge&logo=flutter&logoColor=white)](https://flutter.dev)
[![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=white)](https://www.typescriptlang.org)
[![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)](https://www.python.org)

<img src="https://media.giphy.com/media/v1.Y2lkPTc5MGI3NjExcDd2OWF0Y2R0ZGxjZGptOGdranBhcW50dGhkNGsyeXE0dHU0NzBiYiZlcD12MV9pbnRlcm5hbF9naWZfYnlfaWQmY3Q9Zw/aNqEFrYVnsS52/giphy.gif" width="400"/>

</div>

---

I build resilient, offline-capable distributed systems that put data ownership back in the user's hands. My work focuses on Conflict-free Replicated Data Types (CRDTs), local-first architectures, edge computing, microservices, and IoT systems that eliminate single points of failure and scale from the cloud to the smallest device.

```rust
// My philosophy in code
fn design_system() -> Architecture {
    Architecture::new()
        .offline_first(true)        // Works without internet
        .conflict_free(true)        // CRDTs handle the rest
        .edge_native(true)          // Compute where data lives
        .scales_to(Device::Smallest) // From cloud to microcontroller
}
```

## What I Do

- **CRDT Implementation** — Designing and implementing conflict-free replicated data types for real-time collaborative applications. From operational transforms to state-based and delta-state CRDTs, I focus on convergence guarantees without coordination overhead.

- **Local-First Architecture** — Building applications where data lives on the device first. Users get instant responses, full offline capability, and seamless sync when connectivity returns. No server dependency, no data loss.

- **Edge Computing** — Pushing computation to the edge to reduce latency, improve privacy, and enable true peer-to-peer collaboration. Architecting systems where nodes are autonomous yet eventually consistent.

- **Microservices Architecture** — Designing domain-driven, loosely coupled services that scale independently. API gateways, service meshes, event-driven communication, and observability patterns for systems that grow without breaking.

- **Clean & Hexagonal Architecture** — Structuring codebases with ports and adapters that isolate business logic from infrastructure. Domain at the center, dependencies pointing inward, and every external concern swappable without touching core rules.

- **Event-Driven Architecture** — Designing systems that communicate through events instead of direct calls. Event sourcing, CQRS, message brokers, and eventual consistency patterns for decoupled services that react in real time.

- **IoT & Embedded Systems** — Connecting the physical and digital world. MQTT/CoAP protocols, sensor data pipelines, device fleet management, and edge-to-cloud architectures for smart devices that operate reliably in constrained environments.

- **Open Source Contributor** — I actively contribute to the open source ecosystem, building tools and libraries that advance local-first and distributed systems for the community.

## Tech Stack

<table>
<tr>
<td align="center" width="150">
<img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/rust/rust-original.svg" width="40" height="40" alt="Rust"/><br><b>Rust</b><br><sub>CRDT engines & sync protocols</sub>
</td>
<td align="center" width="150">
<img src="https://www.vectorlogo.zone/logos/flutterio/flutterio-icon.svg" width="40" height="40" alt="Flutter"/><br><b>Flutter</b><br><sub>Local-first mobile & desktop</sub>
</td>
<td align="center" width="150">
<img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/typescript/typescript-original.svg" width="40" height="40" alt="TypeScript"/><br><b>TypeScript</b><br><sub>Collaborative web apps</sub>
</td>
</tr>
</table>

### Also Proficient In

<p>
<img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white"/>
<img src="https://img.shields.io/badge/Node.js-339933?style=flat-square&logo=node.js&logoColor=white"/>
<img src="https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white"/>
<img src="https://img.shields.io/badge/MongoDB-47A248?style=flat-square&logo=mongodb&logoColor=white"/>
<img src="https://img.shields.io/badge/Redis-DC382D?style=flat-square&logo=redis&logoColor=white"/>
<img src="https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white"/>
<img src="https://img.shields.io/badge/React-61DAFB?style=flat-square&logo=react&logoColor=black"/>
<img src="https://img.shields.io/badge/Next.js-000000?style=flat-square&logo=next.js&logoColor=white"/>
<img src="https://img.shields.io/badge/Tailwind-06B6D4?style=flat-square&logo=tailwindcss&logoColor=white"/>
</p>

## Areas of Expertise

```
Distributed Systems       Conflict Resolution        Eventual Consistency
Peer-to-Peer Protocols    Offline-First Design       Real-Time Collaboration
Event Sourcing            State Synchronization      Merkle-DAGs
WebRTC / WebSockets       Data Replication           System Design
Microservices             API Gateway Design         Service Meshes
Clean Architecture        Hexagonal / Ports+Adapters CQRS
Domain-Driven Design      Event Sourcing             Message Brokers
Event-Driven Architecture Saga Pattern               Observability
IoT / MQTT / CoAP         Device Fleet Management    Sensor Data Pipelines
Embedded Systems          Edge-to-Cloud              Constrained Networks
```

## Open Source & Contributions

| Project | Description |
|---------|-------------|
| [crdt-kit](https://github.com/crdt-kit) | CRDT library for building collaborative, conflict-free distributed applications |
| [curso-py](https://github.com/abdielLopezpy/curso-py) | Simple, hands-on Python course for beginners |

## Current Focus

- Building edge computing solutions with Rust for low-latency data processing at the network edge
- Designing IoT architectures that sync device fleets with CRDT-based conflict resolution
- Developing lightweight embedded runtimes for constrained IoT devices
- Contributing to open source CRDT libraries and local-first tooling

---

<div align="center">

---

```
          +-------------------+
          |    Domain Core    |
          |  (Business Rules) |
          +-------------------+
         /    |          |     \
        /     |          |      \
  [Ports]  [Ports]    [Ports]  [Ports]
    |         |          |        |
 Adapters  Adapters  Adapters  Adapters
    |         |          |        |
  REST    Events     MQTT/CoAP   DB
```

*"The best distributed system is one that doesn't need a central server to work."*

---

### Let's Connect

<a href="mailto:aalh97pa@gmail.com"><img src="https://img.shields.io/badge/Gmail-D14836?style=for-the-badge&logo=gmail&logoColor=white"/></a>
<a href="https://github.com/abdielLopezpy"><img src="https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white"/></a>

<sub>Open to collaborations on local-first, CRDT, edge computing, and IoT projects.</sub>

<br>

```
╔══════════════════════════════════════════════════════════════╗
║  "The best distributed system is one that doesn't need     ║
║   a central server to work."              — Abdiel Lopez   ║
╚══════════════════════════════════════════════════════════════╝
```

</div>
