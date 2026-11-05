<div align="right">
  <a href="README.md">English</a> | <strong>Português</strong>
</div>

<div align="center">
  <h1>WEL</h1>
  <p><strong>Engenheiro de Software & Arquiteto de Sistemas | Baixo Nível, Segurança & Sistemas Distribuídos de Alta Performance</strong></p>
  
  <p>
    <a href="https://github.com/welzim19-star"><img src="https://img.shields.io/badge/GitHub-welzim19--star-black?logo=github" alt="GitHub"></a>
    <a href="https://github.com/Lorinmr-dev"><img src="https://img.shields.io/badge/Organização-Lorinmr--dev-0969da?logo=github" alt="Organização"></a>
    <img src="https://img.shields.io/badge/Foco-DevSecOps%20%7C%20Kernel%20%26%20Hardware%20%7C%20Arquitetura%20Crítica-brightgreen" alt="Foco">
    <img src="https://img.shields.io/badge/Localização-Brasil-blue" alt="Localização">
  </p>
</div>

---

### 🛡️ Filosofia de Engenharia & Pilares Centrais

Desenvolvo software resiliente e auditável com forte ênfase em programação defensiva, aceleração direta por hardware e paradigmas de Confiança Zero (*Zero Trust*).

* **Isolamento Galvânico & Desacoplamento:** Separação estrita entre fronteiras públicas não confiáveis e a lógica interna de execução, mitigando falhas sistêmicas em cascata.
* **Padrões Seguros de Falha (*Fail-Secure* & *Fail-Closed*):** Qualquer anomalia criptográfica, falha de asserção ou validação de fronteira encerra a conexão imediatamente, sem expor rastros da infraestrutura.
* **Desempenho com Acesso Direto ao Hardware:** Eliminação de camadas intermediárias por meio de buffers de cópia zero (*zero-copy*), pontes assíncronas JNI, codificação por GPU (`MediaCodec`) e mapeamento direto de memória (`mmap`).
* **Concorrência Determinística:** Pipelines assíncronos orientados a eventos, operações de I/O não bloqueantes e loops de execução com isolamento de threads para garantir vazão previsível.

---

### 🛠️ Matriz de Competências Técnicas

| Domínio | Tecnologias & Ferramental | Padrões Arquiteturais |
| :--- | :--- | :--- |
| **Sistemas & Baixo Nível** | C++20, NDK r26, JNI, Kotlin, Engenharia Reversa, POSIX, Mapeamento de Memória (`mmap`) | Buffers Zero-Copy, Sistemas de Arquivos FAT Binários, ABIs Nativas |
| **Backend & Sistemas Distribuídos** | Python (FastAPI, Asyncio), Node.js (ESM), WebSockets (Socket.io), APIs REST | Arquitetura Orientada a Eventos, Políticas ABAC, Portais Fail-Closed |
| **Segurança & DevSecOps** | Criptografia Envelope (KMS), AES-256-GCM, Integridade HMAC, Bandit, Ruff, SAST/SCA | Pipelines Zero-Trust, Trilhas de Auditoria (JSONL / SQLite WAL), Sanitização de Dados |
| **Mobile & Frontend** | Android 14 (API 34), React 18, TypeScript, Tailwind CSS, Tauri, Capacitor | Armazenamento com Escopo (SAF), Streaming de Vídeo por Hardware, Sincronização Offline-First |
| **Armazenamento & Dados** | SQLite (Modo WAL), PostgreSQL, Redis, Buffers Circulares em Memória | Registro Atômico ACID, Reconciliação Idempotente de Eventos |

---

### 🚀 Vitrine Pública de Arquitetura

Seleção de projetos de código aberto que demonstram competências práticas de engenharia e arquitetura:

<table width="100%">
  <tr>
    <td width="50%" valign="top">
      <h4><a href="https://github.com/welzim19-star/archon-v">🛡️ Archon-V</a></h4>
      <p><em>Interceptor de Segurança e API Gateway de Alta Disponibilidade para Padrão Bancário.</em></p>
      <ul>
        <li>FastAPI, Python 3.12+, Uvicorn</li>
        <li>Defesa contra ameaças com Token Bucket O(1) e validador de políticas ABAC</li>
        <li>Criptografia de envelope por locatário (KMS) e trilha imutável SHA-256</li>
        <li>Zero vazamento de stack traces e encerramento estrito em caso de falha</li>
      </ul>
      <p>
        <img src="https://img.shields.io/badge/Cobertura-%3E85%25-brightgreen" alt="Cobertura">
        <img src="https://img.shields.io/badge/SAST-Bandit%20Aprovado-blue" alt="Bandit">
      </p>
    </td>
    <td width="50%" valign="top">
      <h4><a href="https://github.com/welzim19-star/capivara-emu">🎮 Capivara EMU</a></h4>
      <p><em>Motor de Emulação Retrô Multi-Sistemas de Alta Performance para Android.</em></p>
      <ul>
        <li>C++20, Android NDK r26b, JNI, API Libretro, React 18</li>
        <li>Isolamento galvânico desacoplando a UI TypeScript do pipeline nativo</li>
        <li>Renderização direta no <code>SurfaceView</code> via texturas GLES3 sem cópia</li>
        <li>Engenharia reversa do sistema de arquivos FAT binário do Sega Dreamcast VMU</li>
      </ul>
      <p>
        <img src="https://img.shields.io/badge/Performance-60FPS%20Est%C3%A1vel-brightgreen" alt="FPS">
        <img src="https://img.shields.io/badge/Lat%C3%AAncia%20de%20Entrada-%3C4.2ms-blue" alt="Latência">
      </p>
    </td>
  </tr>
  <tr>
    <td width="50%" valign="top">
      <h4><a href="https://github.com/welzim19-star/bastion-core">🛡️ Bastion-Core</a></h4>
      <p><em>Motor Assíncrono de Auditoria de Rede e Registro Criptográfico Imutável.</em></p>
      <ul>
        <li>Python 3.12+, Concorrência com ThreadPool, Zero-PII Sanitizado</li>
        <li>Ledger imutável encadeado criptograficamente com SHA-256</li>
        <li>Síntese multi-camadas de inteligência de ativos de rede</li>
        <li>Varredura sub-segundo de sub-rede e persistência SQLite WAL</li>
      </ul>
      <p>
        <img src="https://img.shields.io/badge/Testes-13%20Aprovados-brightgreen" alt="Testes">
        <img src="https://img.shields.io/badge/Persist%C3%AAncia-SQLite%20WAL-blue" alt="Persistência">
      </p>
    </td>
    <td width="50%" valign="top">
      <h4><a href="https://github.com/welzim19-star/zero-ping-mirror">⚡ ZeroPingMirror</a></h4>
      <p><em>Motor de Espelhamento de Tela Android e Telemetria em Tempo Real com Latência Ultrabaixa.</em></p>
      <ul>
        <li>Kotlin 1.9+, Android 14 (API 34), MediaCodec, WebSockets</li>
        <li>Codificação H.264 1080p60 acelerada diretamente por hardware na GPU</li>
        <li>Latência de transmissão sub-frame (11,4 ms) em rede local</li>
        <li>Captura de tela zero-copy via <code>MediaProjection</code> nativo do Android</li>
      </ul>
      <p>
        <img src="https://img.shields.io/badge/Lat%C3%AAncia-11.4ms-brightgreen" alt="Latência">
        <img src="https://img.shields.io/badge/Uso%20de%20CPU-%3C3.5%25-blue" alt="CPU">
      </p>
    </td>
  </tr>
  <tr>
    <td colspan="2" valign="top">
      <h4><a href="https://github.com/welzim19-star/pw-opsdesk-showcase">🏢 Arquitetura PW OpsDesk</a></h4>
      <p><em>Especificação Arquitetural de Central Operacional e Despacho de Campo B2B.</em></p>
      <ul>
        <li>Arquitetura orientada a eventos com Socket.io e Node.js ESM</li>
        <li>Governança RBAC granular (Operador, Supervisor, Administrador)</li>
        <li>Fila SQLite WAL offline-first com reconciliação idempotente</li>
        <li>Trilha de auditoria pericial e biométrica selada por coordenadas e hash de hardware</li>
      </ul>
      <p>
        <img src="https://img.shields.io/badge/SLA-%3E12k%20msg%2Fseg-brightgreen" alt="SLA">
        <img src="https://img.shields.io/badge/Padr%C3%A3o-Compat%C3%ADvel%20Cherwell-blue" alt="Padrão">
      </p>
    </td>
  </tr>
</table>

---

### 🌐 Governança Corporativa & Sistemas Comerciais

Para explorar as arquiteturas corporativas, sistemas de operações de campo em missões críticas e plataformas B2B privadas, acesse a organização **[Lorinmr-dev](https://github.com/Lorinmr-dev)**. Regras de negócio de produção, microsserviços privados e suítes de inspeção proprietárias são mantidos sob governança corporativa estrita.

---

<div align="center">
  <sub>Engenharia desenvolvida com precisão técnica, design defensivo e padrões rigorosos de qualidade.</sub>
</div>
