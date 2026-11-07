<div align="right">
  <strong>English</strong> | <a href="README.pt-BR.md">Português</a>
</div>

<div align="center">
  <h1>WEL</h1>
  <p><strong>Android & Systems Software Engineer | Kotlin, C++20, NDK & JNI | Low-Level Architecture & Distributed Systems</strong></p>
  
  <p>
    <a href="https://github.com/welzim19-star"><img src="https://img.shields.io/badge/GitHub-welzim19--star-black?logo=github" alt="GitHub"></a>
    <a href="https://github.com/PW-SYSTEM"><img src="https://img.shields.io/badge/Organization-PW--SYSTEM-0969da?logo=github" alt="Organization"></a>
    <img src="https://img.shields.io/badge/Focus-Android%20NDK%20%7C%20C%2B%2B%20%7C%20Low--Latency%20Streaming-brightgreen" alt="Focus">
    <img src="https://img.shields.io/badge/Location-Brazil-blue" alt="Location">
  </p>
</div>

---

### 🛡️ Engineering Philosophy & Core Pillars

I engineer resilient, audit-grade software with a strong focus on defensive programming, hardware acceleration, and zero-trust paradigms.

* **Galvanic Decoupling & Isolation:** Strict separation between untrusted public boundaries and internal execution logic, preventing systemic cascading failures.
* **Fail-Secure & Fail-Closed Defaults:** Every assertion, boundary anomaly, or cryptographic validation failure drops operations immediately without leaking execution footprints.
* **Hardware-First Performance:** Bypassing abstraction overhead through zero-copy buffers, JNI bridges, GPU encoding (`MediaCodec`), and kernel-level direct memory mapping.
* **Deterministic Concurrency:** Event-driven async pipelines, non-blocking asynchronous I/O, and thread-isolated execution loops designed for deterministic throughput.

---

### 🛠️ Technical Competency Matrix

| Domain | Core Technologies & Tooling | Architectural Patterns |
| :--- | :--- | :--- |
| **Systems & Low-Level** | C++20, x86_64 Detours (MinHook), NDK r26, JNI, Kotlin, Reverse Engineering, POSIX, Memory Mapping (`mmap`) | Zero-Copy Buffers, In-Memory Detours, Binary FAT Filesystems, Native ABIs |
| **Backend & Distributed** | Python (FastAPI, Asyncio), Node.js (ESM), WebSockets (Socket.io), REST APIs | Event-Driven Architecture, ABAC Policies, Fail-Closed Gates, C2 Hubs |
| **Security & DevSecOps** | Envelope Encryption (KMS), AES-256-GCM, HMAC Integrity, Bandit, Ruff, SAST/SCA | Zero-Trust Pipelines, Audit Trails (JSONL / SQLite WAL), PII Sanitization |
| **Mobile & Frontend** | Android 14 (API 34), React 18, TypeScript, Tailwind CSS, Tauri, Capacitor | Scoped Storage (SAF), Hardware Video Streaming, Offline-First Sync |
| **Storage & Data** | SQLite (WAL Mode), PostgreSQL, Redis, In-Memory Ring Buffers | ACID Atomic Journaling, Idempotent Event Reconciliation |

---

### 🚀 Public Architectural Showcase

Here is a curated selection of open-source architectures demonstrating core engineering competencies:

<table width="100%">
  <tr>
    <td width="50%" valign="top">
      <h4><a href="https://github.com/welzim19-star/capivara-emu">🎮 Capivara EMU</a></h4>
      <p><em>High-Performance Multi-System Retro Emulation Engine for Android.</em></p>
      <ul>
        <li>C++20, Android NDK r26b, JNI, Libretro API, React 18</li>
        <li>Galvanic isolation decoupling TypeScript UI from native rendering</li>
        <li>Zero-copy direct framebuffer output to <code>SurfaceView</code> via GLES3</li>
        <li>Reverse-engineered Sega Dreamcast VMS FAT binary filesystem</li>
      </ul>
      <p>
        <img src="https://img.shields.io/badge/Performance-60FPS%20Stable-brightgreen" alt="FPS">
        <img src="https://img.shields.io/badge/Input%20Latency-%3C4.2ms-blue" alt="Latency">
      </p>
    </td>
    <td width="50%" valign="top">
      <h4><a href="https://github.com/welzim19-star/zero-ping-mirror">⚡ ZeroPingMirror</a></h4>
      <p><em>Ultra-Low-Latency Android Screen Mirroring & Telemetry Engine.</em></p>
      <ul>
        <li>Kotlin 1.9+, Android 14 (API 34), MediaCodec, WebSockets</li>
        <li>Hardware-accelerated 1080p60 H.264 encoding directly on GPU</li>
        <li>Sub-frame transmission latency (11.4ms) over local networks</li>
        <li>Zero-copy screen capture via OS <code>MediaProjection</code></li>
      </ul>
      <p>
        <img src="https://img.shields.io/badge/Latency-11.4ms-brightgreen" alt="Latency">
        <img src="https://img.shields.io/badge/CPU%20Usage-%3C3.5%25-blue" alt="CPU">
      </p>
    </td>
  </tr>
  <tr>
    <td width="50%" valign="top">
      <h4><a href="https://github.com/welzim19-star/mario-physics-hook">🔧 Mario Physics Hook</a></h4>
      <p><em>Native Memory Hook & Physics Engine Bridge for Elden Ring.</em></p>
      <ul>
        <li>C++20, x86_64 assembly detours via MinHook, libsm64 core</li>
        <li>Trampoline detours overriding Havok character controller memory</li>
        <li>Multi-rate 30Hz-to-60Hz physics clock synchronization</li>
        <li>Dynamic collision surface injection into process memory</li>
      </ul>
      <p>
        <img src="https://img.shields.io/badge/Hook-MinHook%20x64-red" alt="Hook">
        <img src="https://img.shields.io/badge/Target-AAA%20PE%20Process-purple" alt="Target">
      </p>
    </td>
    <td width="50%" valign="top">
      <h4><a href="https://github.com/welzim19-star/minebot-c2-engine">🤖 Minebot C2 Engine</a></h4>
      <p><em>Autonomous Agent & Command & Control (C2) Orchestrator for Minecraft Java.</em></p>
      <ul>
        <li>Node.js 18+, Mineflayer, Socket.io, Express Web HUD</li>
        <li>Anti-freeze subterranean mining routines and A* 3D navigation</li>
        <li>Reactive combat, automatic threat mitigation, and weapon sorting</li>
        <li>Zero-configuration LAN multicast UDP world discovery</li>
      </ul>
      <p>
        <img src="https://img.shields.io/badge/Protocol-Mineflayer%20Java-green" alt="Protocol">
        <img src="https://img.shields.io/badge/Interface-Dual%20CLI%20%2B%20Web-orange" alt="Interface">
      </p>
    </td>
  </tr>
  <tr>
    <td width="50%" valign="top">
      <h4><a href="https://github.com/welzim19-star/archon-v">🛡️ Archon-V</a></h4>
      <p><em>Bank-Grade High-Availability Security Interceptor & API Gateway.</em></p>
      <ul>
        <li>FastAPI, Python 3.12+, Uvicorn</li>
        <li>O(1) Token-Bucket threat shield and ABAC policy validator</li>
        <li>KMS tenant envelope encryption and SHA-256 immutable audit stream</li>
        <li>Zero stack trace disclosure and strict fail-secure defaults</li>
      </ul>
      <p>
        <img src="https://img.shields.io/badge/Coverage-%3E85%25-brightgreen" alt="Coverage">
        <img src="https://img.shields.io/badge/SAST-Bandit%20Pass-blue" alt="Bandit">
      </p>
    </td>
    <td width="50%" valign="top">
      <h4><a href="https://github.com/welzim19-star/bastion-core">🛡️ Bastion-Core</a></h4>
      <p><em>High-Throughput Asynchronous Network Audit & Cryptographic Ledger Engine.</em></p>
      <ul>
        <li>Python 3.12+, ThreadPool concurrent batching, Zero-PII</li>
        <li>SHA-256 chained tamper-evident append-only ledger</li>
        <li>Multi-layer non-invasive device intelligence synthesis</li>
        <li>Sub-second subnet sweep with SQLite WAL persistence</li>
      </ul>
      <p>
        <img src="https://img.shields.io/badge/Tests-13%20Passing-brightgreen" alt="Tests">
        <img src="https://img.shields.io/badge/Persistence-SQLite%20WAL-blue" alt="Persistence">
      </p>
    </td>
  </tr>
  <tr>
    <td width="50%" valign="top">
      <h4><a href="https://github.com/welzim19-star/bedrock-autonomous-agent">⚡ Bedrock Autonomous Agent</a></h4>
      <p><em>Native UDP Protocol Agent & Finite State Machine for Bedrock Dedicated Server.</em></p>
      <ul>
        <li>Node.js, <code>bedrock-protocol</code>, UDP RakNet wire stream</li>
        <li>Dynamic version negotiation for BDS 1.26.x releases</li>
        <li>Exponential backoff reconnection logic preventing flood bans</li>
        <li>Experimental research on packet-driven autonomous kinematics</li>
      </ul>
      <p>
        <img src="https://img.shields.io/badge/Status-Experimental%20R%26D-orange" alt="Status">
        <img src="https://img.shields.io/badge/Wire-Native%20UDP-blue" alt="Wire">
      </p>
    </td>
    <td width="50%" valign="top">
      <h4><a href="https://github.com/welzim19-star/pw-opsdesk-showcase">🏢 PW OpsDesk Architecture</a></h4>
      <p><em>Enterprise Operations & ITSM Dispatch Architecture Showcase.</em></p>
      <ul>
        <li>Event-driven architecture with Socket.io and Node.js ESM</li>
        <li>Granular RBAC governance (Operator, Supervisor, Administrator)</li>
        <li>Offline-first SQLite WAL queue with idempotent reconciliation</li>
        <li>Biometric and forensic audit trail sealed with GPS and device hashes</li>
      </ul>
      <p>
        <img src="https://img.shields.io/badge/SLA-%3E12k%20msg%2Fsec-brightgreen" alt="SLA">
        <img src="https://img.shields.io/badge/Standard-Cherwell%20Compliant-blue" alt="Standard">
      </p>
    </td>
  </tr>
</table>

---

### 🌐 Enterprise Governance & Commercial Systems

For enterprise architectures, mission-critical field operations systems, and private B2B platforms, visit the **[PW-SYSTEM](https://github.com/PW-SYSTEM)** organization. Production business rules, private microservices, and proprietary inspection suites are maintained under strict enterprise governance.

---

<div align="center">
  <sub>Engineered with precision, defensive design, and strict quality standards.</sub>
</div>
