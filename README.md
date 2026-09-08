# Nguyen An Khang

**Software & Systems Engineer**  
Focusing on Backend Architecture, Offline-First Mobile Systems, and Network Infrastructure.

[Website](https://ankhang0704.vercel.app) • [Email](mailto:ankhang.nguyen0704@gmail.com) • [GitHub](https://github.com/ankhang0704) • [LinkedIn](https://linkedin.com)

---

### 01 / Engineering Thesis

Software systems do not run in an abstract vacuum. They execute on physical operating systems, allocate system memory, and transmit discrete packets across physical networks. 

Having an operational background in **Network Infrastructure & IT Support** shapes how I design applications:
- When writing backend APIs, I account for connection pooling, serialization overhead, and latency budgets.
- When engineering mobile clients, I design for network degradation, partition tolerance, and deterministic local storage.
- My architectural objective is pragmatic: build reliable, maintainable systems that solve business problems without unnecessary operational complexity.

---

### 02 / Architecture & Design Paradigms

#### Network-Aware Application Design
Eliminating black-box assumptions between the application layer (L7) and transport/network layers (L3/L4). Structuring RESTful interfaces and socket lifecycles around packet round-trip times, payload budgets, and connection reuse.

#### Offline-First & Deterministic State Sync
Treating client-side databases (SQLite, Hive, Isar) as the primary source of truth for UI state. Network calls are relegated to asynchronous synchronization pipelines designed to handle intermittent packet loss and offline states gracefully.

#### Modular Monoliths & Bounded Contexts
Prioritizing cohesive, modular backend design over premature distributed microservices. Decoupling business logic from external drivers and database schemas using Clean Architecture and domain partitioning.

#### Infrastructure as Code & Operational Telemetry
Standardizing environments through containerization (Docker) and reproducible Linux runtime configurations. Structuring application logs, health probes, and metrics for automated root-cause isolation.

---

### 03 / Technical Domain & Tooling
