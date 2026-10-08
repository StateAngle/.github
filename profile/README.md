# 🏛️ StateAngle

> **Decentralized, Document-Driven Control Plane as a Service (CaaS)**

Welcome to the **StateAngle** ecosystem. StateAngle provides an unopinionated, decentralized foundation for compute, networking, and state coordination across cloud and edge environments.

---

## 🧭 Ecosystem Architecture

### 🏛️ Core Platform
* **[`statoven`](https://github.com/StateAngle/statoven)** — The core control plane and orchestration stack:
  * **Stangine**: Decentralized, document-driven state plane (SurrealKV / SurrealDB)
  * **StatOven App**: Product coordination and BFF layer
  * **Studio**: Capability library authoring, CUE validation, catalog, and marketplace
  * **Seed**: Node agent & decentralized Nebula mesh overlay daemon
  * **Host-Kit**: Bare-metal systemd host service manager

### 📦 Runtime & Capability Packages (`pkg-*`)
* **[`pkg-crackerbox`](https://github.com/StateAngle/pkg-crackerbox)** — Firecracker microVM runtime package for StatOven

---

## 🏷️ Repository Taxonomy

To keep the ecosystem modular, predictable, and clean:

| Prefix | Category | Description |
| :--- | :--- | :--- |
| *(core)* | **Platform** | Foundational control plane components (`statoven`) |
| `pkg-*` | **Packages** | Runtime providers, capability binaries, and driver packages (`pkg-crackerbox`) |
| `sdk-*` | **SDKs** | Public client libraries for TypeScript, Rust, Python, and Go |
| `tool-*` | **Tools** | Developer utilities, bootstrappers, and CLIs |
