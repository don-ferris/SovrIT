# Sovrit  
**Personal Information Technology Platform**

Sovrit is a personal information technology platform with autonomy at its core, designed to return ownership of your digital life to you. It is private by default, transparent by design, and built to be understood by anyone in your home. Sovrit defines the philosophy, architecture, and long‑term practices that guide every module in the ecosystem.

---

## 🌱 Purpose

Most personal data today lives inside third‑party clouds that you do not control. Sovrit exists to reverse that pattern. It provides a stable, sovereign foundation for identity, communication, storage, automation, and other services—engineered with the same care you’d expect from enterprise infrastructure.

Where third‑party services are unavoidable (such as mobile carriers), Sovrit offers patterns and tools to minimize exposure. Mobile devices can operate on data‑only plans routed through a self‑hosted VPN, and voice/text communication can be handled through sovereign services rather than carrier‑managed channels. The goal is simple: your data should belong to you, not to the companies that move it.

---

## 🧱 What Sovrit (Core-this repo) Provides

- A clear definition of Sovrit’s mission and principles  
- Architectural patterns for building sovereign, long‑lived services  
- Naming conventions, repo structure, and documentation standards  
- A map of the Sovrit ecosystem and how each module fits together  
- Guidance for reducing reliance on third‑party providers  
- Patterns for self‑hosted VPN, messaging, and communication layers  
- Human‑centered documentation designed for a non-technical spouse/partner to follow confidently

Sovrit is not a single application. It is the blueprint for a personal digital infrastructure.

---

## 🛡️ Sovrit Brand Pillars

### Sovereignty by Design
Your data, your systems, your rules. Sovrit minimizes external dependencies, avoids lock‑in, and keeps every component inspectable and replaceable. Third‑party services are used only when necessary, and always behind sovereign layers of privacy and control.

### Infrastructure‑Grade Reliability
Sovrit behaves like a utility: predictable, quiet, and steady. Procedures are atomic and documented. Failure modes are understood and recoverable.

### Modular, Composable Architecture
Each Sovrit module is independent but interoperable. You can adopt one component or the entire suite without friction.

### Human‑Centered Clarity
Sovrit is built for a spouse/partner to operate confidently. Documentation is plain‑spoken, visual, and stepwise. No jargon unless necessary, and always explained.

### Craftsmanship and Transparency
Every decision is intentional. Every configuration is annotated. Nothing is hidden or magical. Sovrit values clarity over cleverness.

### Longevity and Stewardship
Sovrit is designed to outlive any single device or trend. Migration paths, backups, and future‑proofing are first‑class concerns.

---

## 🧩 Sovrit Ecosystem Overview

- **Sovrit Identity** — authentication, MFA, and account stewardship  
- **Sovrit Vault** — secrets, passwords, and encrypted storage  
- **Sovrit Mesh** — networking, VPN, and secure remote access  
- **Sovrit Ledger** — budgeting, financial data, and long‑term records  
- **Sovrit Presence** — home automation, sensors, and daily routines  
- **Sovrit Docs** — the printed binder and digital manual for household operations  
- **Sovrit Relay** — notifications, alerts, and cross‑system messaging  
- **Sovrit Archive** — backups, snapshots, and long‑term data preservation  
- **Sovrit Comms** — sovereign voice, text, and messaging layers for mobile devices  

Each module has its own repo, documentation, and responsibilities, but all follow the same Sovrit principles.

---

## 📐 Architecture Principles

- Small, focused services instead of monoliths  
- Clear boundaries between modules  
- Declarative configuration wherever possible  
- Idempotent provisioning for predictable rebuilds  
- Documented interfaces between components  
- Minimal external dependencies to reduce fragility  
- Local‑first design with cloud as an optional extension  
- Self‑hosted VPN and communication layers to protect mobile traffic  
- Preference for open standards and long‑term maintainability  

These principles ensure Sovrit remains maintainable, teachable, and resilient.

---

## 🔒 Sovereign Communication and Connectivity

Sovrit includes patterns for reclaiming privacy in areas traditionally controlled by third parties:

- **Data‑only mobile plans** routed through a sovereign VPN  
- **Self‑hosted VPN infrastructure** (e.g., WireGuard, Tailscale‑compatible, or Pangolin‑style deployments)  
- **Sovereign voice and messaging** using encrypted, self‑hosted services  
- **Carrier‑independent communication** so no provider can read or log your calls or texts  

Even VPN providers can be a point of trust. Sovrit encourages self‑hosting wherever feasible so that no external party can observe or monetize your traffic.

---

## 📘 Documentation Standards

- Plain language, short paragraphs, and clear steps  
- Visuals and diagrams where helpful  
- Explanations of *why*, not just *how*  
- Glossaries for technical terms  
- Procedures that assume the reader may be stressed or tired  
- A tone that is calm, respectful, and empowering  

The goal is simple: anyone in the household should be able to operate Sovrit without fear.

---

## 🔭 Roadmap

- Expand the ecosystem map with module‑to‑module relationships  
- Add architectural diagrams for the full Sovrit stack  
- Define the Sovrit glossary and terminology guide  
- Publish the Sovrit documentation style guide  
- Establish versioning and lifecycle policies for modules  
- Create templates for new Sovrit repos  
- Develop Sovrit Comms and sovereign mobile workflows  
- Document self‑hosted VPN patterns and migration paths  

---

## 🤝 Contributing

Sovrit is a personal platform, but the practices and patterns here are meant to be shared. Contributions that improve clarity, reliability, or long‑term stewardship are welcome.

---

## 📜 License

Sovrit is released under the MIT License. See `LICENSE` for details.
