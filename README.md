# Dennis Sebastian Daynes

**Business Administration, BI Norwegian Business School — graduating 2027**

I work at the intersection of business and applied technology: economics and finance on one side, building and shipping software products on the other. Previously at **Aker Solutions**, on the Valhall PWP project.

---

### LiftQuest

An iOS strength-training app where an LLM coach talks to the athlete and a deterministic engine owns every number it is allowed to say.

Built solo over three months — 94k lines of TypeScript, a 37-table Postgres schema with row-level security on every table, and a validation layer that drops model output which cannot be traced back to computed evidence. 165 test modules, 3,020 assertions, all passing.

The interesting part is not that it calls a language model. It is the architecture that stops the model from being believed: numbers are grounded per-domain against engine-authored evidence, diagnostic claims require a permission granted by a deterministic ledger, and a reply that fails either check is dropped rather than repaired — the app falls back to the engine's own wording.

**→ [Technical case study](https://github.com/dennisdaynes-arch/liftquest-showcase)**

`React Native` · `Expo` · `TypeScript` · `Supabase` · `PostgreSQL` · `Deno Edge Functions` · `Claude / GPT / Gemini`

---

### Background

- **BI Norwegian Business School** — BSc Business Administration, 2027
- **Aker Solutions** — Valhall PWP project
- Interests: applied AI, analytics, financial markets, and energy

I build with AI-assisted engineering — Claude Code and Codex as implementation tools, with the system design, architectural decisions, validation contracts, and correctness bar owned by me. The [case study](https://github.com/dennisdaynes-arch/liftquest-showcase#my-role) is explicit about where that line falls.

---

📍 Oslo, Norway · dennisdaynes@gmail.com
