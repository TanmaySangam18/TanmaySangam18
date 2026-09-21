## Tanmay Sangam

CS + PM. I build systems that run autonomously, enforce their own invariants, and fail gracefully.

MS Project Management (STEM) @ Northeastern '26 — Boston, MA.

---

### Active projects

**[FleetMind](https://github.com/TanmaySangam18/fleetmind)** — LLM inference distributed across Android employee phones over mDNS + round-robin load balancing. Exposes a drop-in OpenAI-compatible API on `:8080`; no new hardware, no data egress. The premise: a Snapdragon 8 Gen 1 runs Llama 3.2 1B at ~15 tok/s. 500 phones → 2.3M queries/month at $0 cloud cost. Agent delivered via MDM in under 5 minutes, silent install, zero user interaction.

**[competitor.inc](https://competitor-inc-zeta.vercel.app)** — A governed AI workforce: 56 named roles in a real org hierarchy, each with scoped permissions. The treasury enforces per-department budget envelopes; over-budget spend escalates before money moves. Key invariant: permission is a value only the gate can mint — if a guardrail can be satisfied by passing `approved: true`, it's documentation, not a guardrail. Agents get two-way email; sends queue through governance with AI disclosure appended. Irreducible actions (money, contracts, launches) always return to a human.

**[sentinel](https://github.com/TanmaySangam18/sentinel)** — Self-healing site monitor. Autonomous actions are limited to known-good reverts; patches never run unattended. Autonomy is decided by reversibility, not severity — a 200-probe catastrophic outage cannot unlock code-write. There is a test for that. Built on Gemini + Firestore; sealed audit record for every action.

**[agent-rails](https://github.com/TanmaySangam18/agent-rails)** — Six composable accountability modules extracted from a working agent system: authorization gates, sealed audit logs, mandate verification, incident classification, permission minting. Apache-2.0, zero runtime dependencies, Node 20+. The core failure mode it was extracted to fix: three live publishers that never called the auth check function — it looked like governance and enforced nothing.

**[Bharat Ane Nenu](https://praja-lekka.vercel.app)** — Bilingual (EN / తెలుగు) public ledger of Andhra Pradesh government manifesto promises. Trust model is a type constraint: `Source` is a required field on every `Promise` in `lib/types.ts`. Something a politician said but never wrote in an official document does not appear. No database — all content in local `.ts` files, deploys anywhere.

**[kindred](https://tanmaysangam18.github.io/kindred/)** — Dating matched on reading history, not photos. Validated by competitor.inc before any UI was written: demand analysis, competitor gap, churn-pattern review. The signal: what someone reads is a durable proxy for how they think.

---

**Stack** — TypeScript · Python · Next.js · PostgreSQL · Claude API · Gemini · Firestore · Android (llama.cpp via JNI) · Docker

---

<img align="right" height="150" src="https://github-readme-stats.vercel.app/api?username=TanmaySangam18&show_icons=true&theme=github_dark&hide_border=true&count_private=true&hide_rank=true" />

[portfolio](https://tanmaysangam.vercel.app) · [linkedin](https://linkedin.com/in/tanmaysangam) · tanmaysangam018@gmail.com

*Open to Product Management, Strategy & Operations, and Founder's Associate roles in the US.*
