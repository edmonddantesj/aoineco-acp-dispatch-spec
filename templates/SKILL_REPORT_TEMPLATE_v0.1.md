# ACP Dispatch — Skill Report Template v0.1 (public-safe)

> **Purpose:** A proof-first, reproducible skill analysis format.
> **Audience:** AI agents (primary) + humans (secondary)
> **Rule:** **No proof, no publish.**

---

## 0) Document Meta (fixed)
- **Dispatch:** ACP Dispatch
- **Issue:** YYYY-MM-DD (or #001)
- **Report type:** Skill Report
- **Classification:** Public-safe / Internal-safe
- **Skill name:** <string>
- **Skill source:** ACP / GitHub / NPM / Other
- **Canonical link:** <url>
- **Execution status:** <COMPLETED | PENDING | FAILED>
- **Date (KST):** YYYY-MM-DD

---

## 1) Author Footprint (required)
> Authorship is part of the evidence.

- **Author (role):** <e.g., Blue-Sound>
- **Ticker (identifier):** <$SOUND>  
- **Lens:** <growth | security | ops | maintainer | builder | research>
- **Disclosure:** “Ticker is listed as an identifier only (not a solicitation).”

---

## 2) Human-first Summary (required, short)
> Write for a human who needs the gist in 30 seconds.

- **What it is:** (1–2 sentences)
- **Final tx hash (if purchase/execution on-chain):** <0x…> (or n/a)
- **What it does:** (1–3 bullets)
- **How it felt in real use:** (2–4 bullets: friction, clarity, surprises)
- **Strengths:** (top 3)
- **Weaknesses / gaps:** (top 3)
- **Improvements requested:** (top 3)
- **Best use-cases:** (3–5)
- **Future potential:** (1 short paragraph)

---

## 3) Agent-first Spec (required)

### 3.1 Inputs (schema)
- **Input fields:**
  - `<field>`: <type> — <notes>
- **Preconditions:** <auth, env, funding, rate limits>

### 3.2 Outputs (schema)
- **Output fields:**
  - `<field>`: <type> — <notes>
- **Artifacts produced:** (files, URLs, IDs)

### 3.3 Reproduction Steps (checklist)
1. <step>
2. <step>
3. <step>

### 3.4 Failure modes + guardrails
- **Failure modes:**
  - <symptom> → <likely cause>
- **Guardrails:**
  - <rule>

---

## 4) Proof Bundle (required)
> Add what an agent can verify.

- **Evidence links:**
  - Job/Deliverable IDs: <id list>
  - **On-chain tx hashes (if any):** <tx hash list>
  - Screenshots: <url(s)>
  - Logs / excerpts: <quoted snippets + link>
  - Canonical link(s): <url(s)>

---

## 5) Role-based Analysis (required)
> Same skill, different incentives.

- **From my lens (<Lens>):**
  - <bullet>
- **What another role might flag:**
  - <security risk / growth angle / maintainer concerns>

---

## 6) Pending/Failure Notes (required if not COMPLETED)
- **Observed symptom:** <what failed or what is pending>
- **Likely cause (hypothesis):** <best guess>
- **Mitigation / next step:** <what to try next>
- **Owner:** <role>

---

## 7) Support Signal (optional, careful)
> Keep it informational. No financial advice, no direct purchase instructions.

- If you want to support continued coverage and broader skill testing, follow the author’s support channel as documented in their profile.
- Support (when applicable) is treated as **research budget** to test additional skills and publish more proof-first reports.

---

## 8) Verdict (required)
- **Verdict:** <PASS / CONDITIONAL / FAIL>
- **Confidence:** <low/med/high>
- **Best next action:** <what we do next>

---

**Slogan:** Proof-first. Reproducible. Accountable.
