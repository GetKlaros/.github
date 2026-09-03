<p align="center">
  <a href="https://getklaros.com">
    <img src="https://github.com/GetKlaros.png?size=160" width="112" alt="Klaros" />
  </a>
</p>

<h1 align="center">Klaros</h1>

<p align="center">
  <strong>Security that attacks, proves, and protects.</strong>
</p>

<p align="center">
  Autonomous offensive security + runtime protection for the AI era.
</p>

<p align="center">
  <img src="https://img.shields.io/badge/⚔️_Offensive_Security-Klaros_Engine-111827?style=flat-square" alt="Klaros Engine" />
  <img src="https://img.shields.io/badge/🛡️_AI_Security-Klaros_Firewall-111827?style=flat-square" alt="Klaros Firewall" />
  <img src="https://img.shields.io/badge/status-early_access-f59e0b?style=flat-square" alt="Early access" />
</p>

<p align="center">
  <a href="https://getklaros.com"><strong>Website</strong></a>
  ·
  <a href="mailto:hello@getklaros.com?subject=Klaros%20early%20access"><strong>Early access</strong></a>
  ·
  <a href="mailto:hello@getklaros.com">Contact</a>
</p>

---

## 🔐 Two products. One security philosophy.

<p align="center">
  <strong>Prove what can be exploited. Control what crosses your AI boundary.</strong>
</p>

<table>
<tr>
<td width="50%" align="center" valign="top">
<br />
<h3>⚔️ Klaros Engine</h3>
<p><strong>Prove what is actually exploitable.</strong></p>
<p><sub>AUTONOMOUS OFFENSIVE SECURITY</sub></p>
<p>Web & APIs · Source code · Pull requests · Web3 / EVM</p>
<p><code>MAP → ATTACK → PROVE → REPLAY</code></p>
<p>Multi-agent pentesting that executes real tests, preserves evidence and independently validates material findings before reporting them.</p>
<p><strong>Proof, not another alert feed.</strong></p>
<p><a href="https://github.com/GetKlaros/klaros-engine"><strong>Explore Klaros Engine →</strong></a></p>
<br />
</td>
<td width="50%" align="center" valign="top">
<br />
<h3>🛡️ Klaros Firewall</h3>
<p><strong>Control what reaches your models.</strong></p>
<p><sub>LOCAL-FIRST AI RUNTIME SECURITY</sub></p>
<p>Prompt attacks · PII · Secrets · Policy enforcement</p>
<p><code>INSPECT → DETECT → DECIDE → ENFORCE</code></p>
<p>A provider-neutral AI security layer that inspects content locally and applies policy before sensitive or unsafe interactions continue.</p>
<p><strong>Keep the AI boundary under your control.</strong></p>
<p><a href="https://github.com/GetKlaros/klaros-firewall"><strong>Explore Klaros Firewall →</strong></a></p>
<br />
</td>
</tr>
</table>

---

## 🧠 Why Klaros

**✅ Proof over alerts**  
A finding should survive validation and replay, not just match a rule.

**🔒 Local-first where it matters**  
Security-sensitive content can stay inside your environment.

**🔌 Provider-neutral**  
Klaros is designed around your security boundary, not a single model or cloud provider.

**🤖 Built for automation**  
CLI, API, CI/CD, hosted campaigns and machine-readable evidence are first-class workflows.

---

## 🔄 From code to runtime

```mermaid
flowchart LR
  subgraph PRE["⚔️ BEFORE DEPLOYMENT"]
    direction TB
    E0["Klaros Engine"]
    E1["Map attack surface"]
    E2["Attack"]
    E3["Prove exploitability"]
    E4["Replay independently"]
    E0 --> E1 --> E2 --> E3 --> E4
  end

  subgraph RUN["🛡️ DURING AI RUNTIME"]
    direction TB
    F0["Klaros Firewall"]
    F1["Inspect AI traffic"]
    F2["Detect risky content"]
    F3["Decide policy"]
    F4["Enforce"]
    F0 --> F1 --> F2 --> F3 --> F4
  end

  E4 -. "release" .-> F0

  classDef engine fill:#f5f3ff,stroke:#7c3aed,color:#111827;
  classDef firewall fill:#ecfeff,stroke:#0891b2,color:#111827;
  class E0,E1,E2,E3,E4 engine;
  class F0,F1,F2,F3,F4 firewall;
```

<p align="center">
  <strong>Before deployment:</strong> find and prove exploitable weaknesses.<br />
  <strong>During AI runtime:</strong> inspect traffic and enforce policy in real time.
</p>

Klaros is being built around a simple idea: **security controls should either prevent a real failure or prove that a real failure exists.**

---

## 🚧 Current product stage

- **Klaros Engine** — Alpha; real Web/API/code/CI/Web3 offensive workflows are running today.
- **Klaros Firewall Community** — Pre-alpha; local API, policy engine, built-in detectors, proxy and operator UI are available in development.
- **Klaros SaaS** — Early hosted control plane with campaigns, immutable snapshots, live events, findings and reports.

We are actively working with early users while the public product surface is being finalized.

---

## 📬 Early access

If you are building AI systems, running application security programs, or want autonomous pentesting with reproducible evidence:

<p align="center">
  <a href="mailto:hello@getklaros.com?subject=Klaros%20early%20access"><strong>→ Request early access</strong></a>
  &nbsp;&nbsp;·&nbsp;&nbsp;
  <a href="https://getklaros.com"><strong>getklaros.com</strong></a>
</p>

<p align="center">
  <sub>Authorized security testing only. Klaros offensive products are intended for systems you own or are explicitly permitted to test.</sub>
</p>
