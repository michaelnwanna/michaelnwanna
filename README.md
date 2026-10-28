# Hi, I'm Michael Nwanna 👋

**Principal software engineer** working where data, performance, determinism, and hardware
meet. I build things from the silicon up: bare-metal microcontroller firmware,
edge-AI inference kernels, circuit simulation, and real-time game systems — all
in modern, allocation-aware programming languages.

---

## 🔧 What I build

| Domain | Repo | What it shows |
| ------ | ---- | ------------- |
| 🛠️ **Bare-metal MCU** | [**mcu-baremetal**](https://github.com/michaelnwanna/mcu-baremetal) | True bare-metal AVR firmware — no Arduino, no RTOS, **no vendor libraries**. Datasheet-level register I/O, raw interrupt vectors, ~1.8 KB flash. |
| 💡 **MCU fundamentals** | [**mcu-blink**](https://github.com/michaelnwanna/mcu-blink) | A minimal, heavily documented bare-metal AVR LED example built directly from registers and the GNU toolchain. |
| 🧠 **Edge AI** | [**microtensor**](https://github.com/michaelnwanna/microtensor) | A tiny, heap-free C++ tensor + **int8 quantized inference** core designed to run on constrained devices. |
| ⚡ **Circuit simulation** | [**microspice**](https://github.com/michaelnwanna/microspice) | An educational SPICE-inspired simulator with nodal analysis, transparent matrix stamping, and a phased path to nonlinear transient simulation and a Qt GUI. |
| 🎮 **Real-time gaming** | [**game-engine-core**](https://github.com/michaelnwanna/game-engine-core) | A **deterministic** fixed-timestep simulation loop and fixed-point math core — the backbone of reproducible real-time engines. |
| **Failure intelligence** | [**platform-inteligence-lab**](https://github.com/michaelnwanna/os-inteligence-lab) | A Python and C#/.NET platform for regression detection, affected-cohort discovery, change correlation, and evidence-grounded AI investigation, with reproducible synthetic fleet scenarios and incident replay. |
| 📡 **Offline edge AI** | [**ai-hotspot**](https://github.com/michaelnwanna/ai-hotspot) | An offline AI gateway: a Wi-Fi hotspot that lets any phone browser chat with a local Ollama model, no SIM or Internet needed. Runs on Raspberry Pi, Linux, Windows, macOS and Android (Termux), with a dependency-free cross-platform launcher and FAQ-grounded answers. |
| **Payment protocols** | [**Iso8583lib**](https://github.com/michaelnwanna/Iso8583lib) | A dependency-free **ISO 8583 codec** in Go, C#, and C++, with strict JSON host profiles, packed BCD, incremental transport framing, and shared cross-language conformance vectors. |
| **Android fleet management** | [**custom-android-mdm-agent**](https://github.com/michaelnwanna/custom-android-mdm-agent) | A Kotlin Android Device Owner agent with API 34 kiosk, silent-update and reboot-recovery evidence; an implemented **ASP.NET Core/PostgreSQL control plane**, **Vue 3/TypeScript fleet console**, and Entra-authenticated Flutter administrator companion. Keystore-backed mTLS enrollment, durable Room event replay and server deduplication are tested. End-to-end remote policy enforcement and managed release delivery remain in development. |
| **Offline synchronization** | [**offline-sync-engine**](https://github.com/michaelnwanna/offline-sync-engine) | A Kotlin/Android and .NET synchronization SDK in development: field-level CRDT merges, encrypted Room/SQLCipher storage, a durable leased outbox, and transactional acknowledgment/pull processing. Eighteen Android 34 instrumentation tests passed locally; HTTP transport, WorkManager, the sample app, and real PostgreSQL validation remain outstanding. |
| **Local-first network inspection** | [**Traceglass**](https://github.com/michaelnwanna/network-anomaly-packet-inspection) | A Go HTTP/HTTPS proxy with **opt-in, per-domain TLS inspection**, encrypted CONNECT passthrough, tracker/size/port signals, a local dashboard, and bounded SQLite/WAL metadata storage. Race-tested with **81.2% statement coverage** and a **1,000,000-retained-record** scale test; no persisted payloads or automatic certificate trust installation. |
| **Automotive diagnostics** | [**LegacyDiag**](https://github.com/michaelnwanna/obd2-canbus-diag) | A read-only C#/.NET 10 OBD-II CLI with serial ELM327 transport, sensor polling, DTC interpretation, local SQLite history, JSON screening rules and M113/M113K-oriented guidance, with serial transport exercised through an ELM327 emulator. |

The thread connecting these projects: **performance-critical, deterministic C++
with no hidden costs.**

---

## 💡 How I work

- **Zero-overhead abstractions** — abstractions manage complexity, never add runtime cost.
- **No heap, no exceptions, no RTTI** on hot/embedded paths; bounded compile-time state.
- **Inject hardware at the boundary** so logic stays portable and unit-testable on a host.
- **Tests + CI, Architecture Diagrams and Documentation are non-negotiable** — every repo builds, tests, and format-checks on every push.
- **Program to the datasheet** — I'd rather understand the silicon than hide behind a vendor HAL.

---

## Technical leadership

My approach: **set clear technical direction, make trade-offs explicit, and make reliable delivery repeatable.**

- **Architecture with intent** — connect design decisions to real constraints: latency, memory, reliability, security, and maintainability.
- **Lead through engineering standards** — favor small, reviewable changes, reproducible tests, and CI-backed evidence over assumptions.
- **Build shared understanding** — explain the reasoning, document the boundaries, and make complex systems easier for others to extend.

---

## 🧰 Tech

![C++](https://img.shields.io/badge/C%2B%2B-17%2F20-00599C?logo=cplusplus&logoColor=white)
![C](https://img.shields.io/badge/C-freestanding-A8B9CC?logo=c&logoColor=black)
![Go](https://img.shields.io/badge/Go-1.24%2B-00ADD8?logo=go&logoColor=white)
![AVR](https://img.shields.io/badge/AVR-avr--gcc-orange)
![ARM](https://img.shields.io/badge/ARM-Cortex--M-0091BD?logo=arm&logoColor=white)
![CMake](https://img.shields.io/badge/CMake-064F8C?logo=cmake&logoColor=white)
![Assembly](https://img.shields.io/badge/Assembly-inline-525252)
![GitHub Actions](https://img.shields.io/badge/CI-GitHub%20Actions-2088FF?logo=githubactions&logoColor=white)

**Focus areas:** AI, offline edge-AI gateways, embedded firmware · device drivers · interrupts & timers ·
real-time systems · quantization & inference · numerical methods · circuit
simulation · deterministic simulation · local-first network inspection · build systems & toolchains.

---

## 📊 GitHub

![Michael's GitHub stats](https://github-readme-stats.vercel.app/api?username=michaelnwanna&show_icons=true&hide_border=true&count_private=true)
![Top languages](https://github-readme-stats.vercel.app/api/top-langs/?username=michaelnwanna&layout=compact&hide_border=true&langs_count=8)

---

<sub>Open to roles in embedded / systems / performance C++.</sub>
