## P-MATRIX

**The Coordinate System & Protocol for Autonomous Agent Runtime Governance.**

P-MATRIX gives AI agents a structured risk coordinate system and real-time governance layer — so you always know what your agents are doing, and can stop them when it matters.

---

### Runtime Safety Monitors

One governance engine, two runtimes:

#### OpenClaw Plugin

[![npm](https://img.shields.io/npm/v/@pmatrix/openclaw-monitor?label=%40pmatrix%2Fopenclaw-monitor&color=blue)](https://www.npmjs.com/package/@pmatrix/openclaw-monitor)

```bash
openclaw plugins install @pmatrix/openclaw-monitor
```

→ Source: **[p-matrix/openclaw-monitor](https://github.com/p-matrix/openclaw-monitor)**

#### Claude Code Monitor

[![npm](https://img.shields.io/npm/v/@pmatrix/claude-code-monitor?label=%40pmatrix%2Fclaude-code-monitor&color=blue)](https://www.npmjs.com/package/@pmatrix/claude-code-monitor)

```bash
npm install -g @pmatrix/claude-code-monitor
```

→ Source: **[p-matrix/claude-code-monitor](https://github.com/p-matrix/claude-code-monitor)**

#### Shared Capabilities

- 🛡️ **Safety Gate** — blocks or confirms high-risk tool calls before execution
- 🔑 **Credential Guard** — detects OpenAI, AWS, GitHub, Stripe patterns on-device
- ☠️ **Kill Switch** — terminates runaway agents instantly
- 📊 **Live Grade A–E** — real-time risk trajectory via 4-axis coordinate system

→ Dashboard: **[app.pmatrix.io](https://app.pmatrix.io)**

---

### Research Papers

- 📄 [**Runtime State Representation** (v3.5)](https://doi.org/10.5281/zenodo.18682846) — 4-axis coordinate system + R(t) risk formula
  - Reference encoder: [pmatrix-encoder](https://github.com/p-matrix/pmatrix-encoder)
- 📄 [**Mutual Verification Protocol** (v4.0)](https://doi.org/10.5281/zenodo.18683912) — two-node runtime governance protocol
  - Reference encoder: [pmatrix-protocol-encoder](https://github.com/p-matrix/pmatrix-protocol-encoder)

---

### Links

🌐 [p-matrix.io](https://p-matrix.io) · 📦 [npm](https://www.npmjs.com/org/pmatrix) · 🐦 [@pmatrix_](https://x.com/pmatrix_) · ✉️ architect@p-matrix.io
