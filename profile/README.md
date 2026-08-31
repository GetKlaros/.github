<p align="center">
  <a href="https://getklaros.com">
    <img
      src="https://github.com/GetKlaros.png?size=160"
      width="112"
      alt="Klaros"
    />
  </a>
</p>

<h1 align="center">Klaros</h1>

<p align="center">
  <strong>Find what attackers will.</strong>
</p>

<p align="center">
  Security systems for the applications organizations build and the AI systems they use.
</p>

<p align="center">
  <a href="https://getklaros.com">Website</a>
  ·
  <a href="mailto:hello@getklaros.com">Contact</a>
  ·
  <a href="mailto:hello@getklaros.com?subject=Klaros%20early%20access">Request early access</a>
</p>

---

Klaros builds security products that help organizations prevent exposure, discover exploitable weaknesses and verify that their defenses work.

Our approach combines protection at the AI boundary with continuous offensive testing of applications, APIs and code.

## What we build

### AI and LLM security

Klaros protects the interactions between organizations, their users and AI providers.

The LLM security layer is designed to:

- inspect requests and responses passing through AI systems;
- detect and protect sensitive or personal data;
- enforce organizational AI usage policies;
- identify prompt injection and unsafe model interactions;
- provide visibility into how AI services are used;
- reduce direct exposure to external model providers.

### Autonomous offensive security

The first security product currently being developed by Klaros actively tests web applications, APIs, source code and pull requests.

It maps the attack surface, pursues viable attack paths and independently reproduces the impact before a vulnerability becomes a customer-facing finding.

## From signal to proof

Traditional security tools are good at identifying suspicious patterns. Klaros goes further:

- **Map the boundary** — understand routes, identities, permissions, state transitions and data flows before active testing.
- **Pursue exploitability** — investigate authorization, authentication, injections, browser behavior, SSRF, APIs and business logic.
- **Prove the impact** — execute controlled tests against the authorized target rather than stopping at a theoretical weakness.
- **Replay independently** — reproduce candidates from a clean baseline before reporting them.
- **Preserve the evidence** — retain the execution context required to understand, reproduce and retest each finding.

## The offensive security method

```text
MAP → TEST → VERIFY
```

### 01 / Map

Build a shared model of the target, its trust boundaries and its reachable attack surface.

### 02 / Test

Explore viable attack paths across identities, interfaces, state transitions and security controls.

### 03 / Verify

Replay the candidate independently with positive and negative controls. Only reproducible impact becomes a finding.

## Security across the organization

Klaros is being built to protect:

- web applications;
- APIs;
- source code and pull requests;
- authentication and authorization boundaries;
- business logic and stateful workflows;
- AI applications and agents;
- employee interactions with external LLM providers;
- sensitive data crossing AI boundaries.

## Our principles

### Prevent where possible

Apply controls before sensitive information or unsafe instructions reach an AI provider.

### Test what matters

Focus offensive effort on realistic attack paths rather than maximizing alert volume.

### Prove before reporting

Separate suspicious signals from vulnerabilities with reproducible impact.

### Preserve the evidence

Keep the context required to understand, replay and retest every verified security failure.

## Current focus

Our current development focus is the autonomous offensive-security product:

- **PR** — focused validation around changed code and newly reachable attack paths.
- **Web** — live application testing across browser, API and out-of-band surfaces.
- **Deep** — broader offensive exploration across identities, state, data flows and business logic.

## Early access

Klaros is opening early access to organizations that want stronger control over AI usage and reproducible security findings instead of another stream of alerts.

- **Website:** [getklaros.com](https://getklaros.com)
- **Contact:** [hello@getklaros.com](mailto:hello@getklaros.com)
