<div align="right">
  <a href="README.md">English</a> | <strong>Português</strong>
</div>

<div align="center">
  <img src="assets/banner.svg" alt="Wel - Engenheiro de Software Android &amp; Sistemas" width="100%" />
  <br/><br/>
  <a href="https://github.com/welzim19-star">
    <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&pause=1200&color=00FF66&center=true&vCenter=true&width=750&lines=Full-Spectrum+Android:+Jetpack+Compose+ao+NDK+r26;C%2B%2B20+%2F+JNI+%E2%80%A2+Clean+Architecture+%E2%80%A2+MVI%2FMVVM;Streaming+1080p60+por+Hardware+(Sub-12ms+Zero-Copy);Arquiteturas+Fail-Secure+%E2%80%A2+DevSecOps+Padr%C3%A3o+Banc%C3%A1rio" alt="Typing SVG" />
  </a>
  <br/><br/>
  <p>
    <a href="https://github.com/welzim19-star"><img src="https://img.shields.io/badge/GitHub-welzim19--star-black?logo=github" alt="GitHub"></a>
    <a href="https://github.com/PW-SYSTEM"><img src="https://img.shields.io/badge/Organização-PW--SYSTEM-0969da?logo=github" alt="Organização"></a>
    <img src="https://img.shields.io/badge/Foco-Full--Spectrum%20Android%20%7C%20C%2B%2B20%20%7C%20NDK%20r26-brightgreen" alt="Foco">
    <img src="https://komarev.com/ghpvc/?username=welzim19-star&label=RADAR+VIEWS&color=00ff66&style=flat-square" alt="Radar Views">
    <img src="https://img.shields.io/badge/Localização-Brasil-blue" alt="Localização">
  </p>
</div>

---

### 🛡️ Filosofia de Engenharia & Pilares Centrais

Desenvolvo software resiliente e auditável com forte ênfase em programação defensiva, aceleração direta por hardware e paradigmas de Confiança Zero (*Zero Trust*).

* **Isolamento Galvânico & Desacoplamento:** Separação estrita entre fronteiras públicas não confiáveis e a lógica interna de execução, mitigando falhas sistêmicas em cascata.
* **Padrões Seguros de Falha (*Fail-Secure* & *Fail-Closed*):** Qualquer anomalia criptográfica, falha de asserção ou validação de fronteira encerra a conexão imediatamente, sem expor rastros da infraestrutura.
* **Desempenho com Acesso Direto ao Hardware:** Eliminação de camadas intermediárias por meio de buffers de cópia zero (*zero-copy*), pontes assíncronas JNI, codificação por GPU (`MediaCodec`), detours em memória de processo (MinHook) e mapeamento direto (`mmap`).
* **Concorrência Determinística:** Pipelines assíncronos orientados a eventos, operações de I/O não bloqueantes e loops de execução com isolamento de threads para garantir vazão previsível.

---

### 🛠️ Matriz de Competências Técnicas

| Domínio | Tecnologias & Ferramental | Padrões Arquiteturais |
| :--- | :--- | :--- |
| **Android Moderno (Alto Nível)** | Kotlin (Coroutines, StateFlow), Jetpack Compose, Android 14 (API 34), Hilt (Injeção de Dependência), Room, Retrofit, WorkManager, Scoped Storage (SAF) | Clean Architecture, MVI / MVVM, Fluxos de Estado Reativos, Sincronização Offline-First |
| **Sistemas Nativos & Baixo Nível** | C++20, Android NDK (r26b), JNI (Java Native Interface), MediaCodec (GPU H.264), OpenGL ES 3.0, POSIX, `mmap`, MinHook x64 | Buffers Diretos Zero-Copy, Streaming Sub-12ms, Sistemas de Arquivos FAT em Memória, ABIs Nativas |
| **Segurança & DevSecOps** | CI/CD Automatizado (GitHub Actions), Criptografia Envelope (KMS), AES-256-GCM, HMAC, Bandit SAST, Ruff, Pytest | Portais Zero-Trust, Padrões Fail-Secure, Livro-Razão Criptográfico (Cadeia SHA-256) |
| **Backend & Distribuído** | Python 3.12+ (FastAPI, Asyncio), Node.js (ESM), WebSockets (Socket.io), APIs RESTful | Microserviços Orientados a Eventos, Rate Limiting Token-Bucket, Governança ABAC |
| **Armazenamento & Persistência** | SQLite (Modo WAL), PostgreSQL, Redis, Buffers Circulares em Memória | Registro Atômico ACID, Reconciliação Idempotente de Eventos, I/O de Alta Vazão |
| **Multiplataforma & Híbrido** | React 18, TypeScript, Tailwind CSS, Tauri, Capacitor | Desacoplamento Galvânico UI/Engine, Interoperabilidade Headless WebView |

---

### 🚀 Vitrine Pública de Arquitetura

Seleção de projetos de código aberto que demonstram competências práticas de engenharia e arquitetura:

<table width="100%">
  <tr>
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
        <a href="https://github.com/welzim19-star/capivara-emu/releases/latest"><img src="https://img.shields.io/badge/Release-APK%20Download-brightgreen?logo=android" alt="APK"></a>
        <a href="https://github.com/welzim19-star/capivara-emu/actions/workflows/ci.yml"><img src="https://github.com/welzim19-star/capivara-emu/actions/workflows/ci.yml/badge.svg" alt="CI"></a>
        <img src="https://img.shields.io/badge/Performance-60FPS%20Est%C3%A1vel-brightgreen" alt="FPS">
        <img src="https://img.shields.io/badge/Lat%C3%AAncia%20de%20Entrada-%3C4.2ms-blue" alt="Latência">
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
        <a href="https://github.com/welzim19-star/zero-ping-mirror/releases/latest"><img src="https://img.shields.io/badge/Release-Download%20APK-brightgreen?logo=android" alt="APK"></a>
        <a href="https://github.com/welzim19-star/zero-ping-mirror/actions/workflows/build-apk.yml"><img src="https://github.com/welzim19-star/zero-ping-mirror/actions/workflows/build-apk.yml/badge.svg" alt="CI"></a>
        <img src="https://img.shields.io/badge/Lat%C3%AAncia-11.4ms-brightgreen" alt="Latência">
        <img src="https://img.shields.io/badge/Uso%20de%20CPU-%3C3.5%25-blue" alt="CPU">
      </p>
    </td>
  </tr>
  <tr>
    <td width="50%" valign="top">
      <h4><a href="https://github.com/welzim19-star/mario-physics-hook">🔧 Mario Physics Hook</a></h4>
      <p><em>Hook de Memória Nativo em C++ e Ponte de Física para Elden Ring.</em></p>
      <ul>
        <li>C++20, detours de assembly x86_64 via MinHook, core libsm64</li>
        <li>Trampolins interceptando a memória do Havok Character Controller</li>
        <li>Sincronização de relógio de física multi-taxa (30Hz para 60Hz)</li>
        <li>Injeção dinâmica de malhas de colisão na memória do processo</li>
      </ul>
      <p>
        <img src="https://img.shields.io/badge/Hook-MinHook%20x64-red" alt="Hook">
        <img src="https://img.shields.io/badge/Alvo-Processo%20AAA%20PE-purple" alt="Alvo">
      </p>
    </td>
    <td width="50%" valign="top">
      <h4><a href="https://github.com/welzim19-star/minebot-c2-engine">🤖 Minebot C2 Engine</a></h4>
      <p><em>Agente Autônomo e Orquestrador Command & Control (C2) para Minecraft Java.</em></p>
      <ul>
        <li>Node.js 18+, Mineflayer, Socket.io, HUD Web Express</li>
        <li>Rotinas de mineração subterrânea anti-freeze e pathfinding 3D A*</li>
        <li>Combate reativo, mitigação de ameaças e seleção de armas</li>
        <li>Autodescoberta sem configuração em LAN via broadcast UDP</li>
      </ul>
      <p>
        <img src="https://img.shields.io/badge/Protocolo-Mineflayer%20Java-green" alt="Protocolo">
        <img src="https://img.shields.io/badge/Interface-Dual%20CLI%20%2B%20Web-orange" alt="Interface">
      </p>
    </td>
  </tr>
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
        <a href="https://github.com/welzim19-star/archon-v/actions/workflows/ci.yml"><img src="https://github.com/welzim19-star/archon-v/actions/workflows/ci.yml/badge.svg" alt="CI"></a>
        <img src="https://img.shields.io/badge/Cobertura-%3E85%25-brightgreen" alt="Cobertura">
        <img src="https://img.shields.io/badge/SAST-Bandit%20Aprovado-blue" alt="Bandit">
      </p>
    </td>
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
        <a href="https://github.com/welzim19-star/bastion-core/releases/latest"><img src="https://img.shields.io/badge/Release-Windows%20EXE-blue?logo=windows" alt="EXE"></a>
        <a href="https://github.com/welzim19-star/bastion-core/actions/workflows/ci.yml"><img src="https://github.com/welzim19-star/bastion-core/actions/workflows/ci.yml/badge.svg" alt="CI"></a>
        <img src="https://img.shields.io/badge/Testes-13%20Aprovados-brightgreen" alt="Testes">
        <img src="https://img.shields.io/badge/Persist%C3%AAncia-SQLite%20WAL-blue" alt="Persistência">
      </p>
    </td>
  </tr>
  <tr>
    <td width="50%" valign="top">
      <h4><a href="https://github.com/welzim19-star/bedrock-autonomous-agent">⚡ Bedrock Autonomous Agent</a></h4>
      <p><em>Agente Nativo UDP e Máquina de Estados para Bedrock Dedicated Server (BDS).</em></p>
      <ul>
        <li>Node.js, <code>bedrock-protocol</code>, stream binário UDP RakNet</li>
        <li>Negociação dinâmica de versões para servidores BDS 1.26.x</li>
        <li>Lógica de reconexão com backoff exponencial contra flood</li>
        <li>Pesquisa experimental em cinemática autônoma orientada a pacotes</li>
      </ul>
      <p>
        <img src="https://img.shields.io/badge/Status-Pesquisa%20Experimental-orange" alt="Status">
        <img src="https://img.shields.io/badge/Wire-UDP%20Nativo-blue" alt="Wire">
      </p>
    </td>
    <td width="50%" valign="top">
      <h4><a href="https://github.com/welzim19-star/pw-opsdesk-showcase">🏢 Arquitetura PW OpsDesk</a></h4>
      <p><em>Especificação Arquitetural de Central Operacional e Despacho de Campo B2B.</em></p>
      <ul>
        <li>Arquitetura orientada a eventos com Socket.io e Node.js ESM</li>
        <li>Governança RBAC granular (Operador, Supervisor, Administrador)</li>
        <li>Fila SQLite WAL offline-first com reconciliação idempotente</li>
        <li>Trilha de auditoria pericial e biométrica selada por coordenadas e hash de hardware</li>
      </ul>
      <p>
        <a href="https://github.com/welzim19-star/pw-opsdesk-showcase#-vitrine-operacional-em-produ%C3%A7%C3%A3o"><img src="https://img.shields.io/badge/Vitrine-Prints%20Reais-blueviolet" alt="Prints"></a>
        <img src="https://img.shields.io/badge/SLA-%3E12k%20msg%2Fseg-brightgreen" alt="SLA">
        <img src="https://img.shields.io/badge/Padr%C3%A3o-Compat%C3%ADvel%20Cherwell-blue" alt="Padrão">
      </p>
    </td>
  </tr>
</table>

---

### 📊 Telemetria de Atividade & Engenharia em Tempo Real

<div align="center">
  <a href="https://github.com/welzim19-star">
    <img src="https://github-readme-streak-stats.herokuapp.com/?user=welzim19-star&theme=tokyonight&hide_border=true&background=0d1117" alt="GitHub Streak" />
  </a>
</div>

---

### 🌐 Governança Corporativa & Sistemas Comerciais

Para explorar as arquiteturas corporativas, sistemas de operações de campo em missões críticas e plataformas B2B privadas, acesse a organização **[PW-SYSTEM](https://github.com/PW-SYSTEM)**. Regras de negócio de produção, microsserviços privados e suítes de inspeção proprietárias são mantidos sob governança corporativa estrita.

---

<div align="center">
  <sub>Engenharia desenvolvida com precisão técnica, design defensivo e padrões rigorosos de qualidade.</sub>
</div>
