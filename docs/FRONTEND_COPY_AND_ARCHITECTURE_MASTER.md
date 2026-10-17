# Reprieve — Master Copywriting, Section Architecture & Page Inventory

> **Document Version:** 1.0.0 (Master Review & Export Edition)  
> **Target Application:** Reprieve Web Platform (`https://reprieve.vercel.app`)  
> **Source Code Repositories:** `webdev-hackthon` & `wemakedevs-hackathon`  
> **Status:** 100% Verified against Production AST & Runtime Components  
> **Purpose:** Comprehensive inventory of every single page, section, header, topic, and tagline across the entire frontend application for context extraction, tone tuning, and editorial enhancement.

---

## 🧭 Page 01: Global Marketing Navigation & Header Bar
* **File Reference:** `frontend/components/marketing/marketing-nav.tsx`
* **Layout:** Top-pinned glassmorphic navigation bar (`#07080a/40` to `#07080a/95` on scroll).

### Structure:
* **Topic (Brand Identifier):**
  > `REPRIEVE` (Icon mark with cyan beacon node `#22D3EE` + wordmark)
* **Header (Navigation Items):**
  > `CLI & MCP` · `Post-Mortems` · `Detection Rules` · `Architecture` · `FAQ`
* **Tagline (Call to Action Elements):**
  > `Live Sandbox (0 Login)` (Instant route to `/w/northwind-pay/home`)  
  > `Sign in` · `Get started`

---

## ⚡ Page 02: Main Marketing Landing Page (`/`)
* **File Reference:** `frontend/app/(marketing)/page.tsx`
* **Route:** `/`

---

### Section 1: Hero Section (The Local Rationality Trap)
* **Component Reference:** `frontend/app/(marketing)/page.tsx` (Lines 128–175) & `hero-graph-circuit-breaker.tsx`
* **Topic (Category Tag):**
  > `PRE-MERGE ARCHITECTURE SAFETY ENGINE`
* **Header:**
  > `Three harmless exceptions. One catastrophic collision.`  
  > `Reprieve intercepts compound risk before merge.`
* **Tagline (Description):**
  > `Sprint boards treat waivers as isolated tickets. Reprieve models temporary bypasses and skipped tests as promises on your microservice graph to stop multi-hop cascading outages.`
* **Interactive Elements & Action Buttons:**
  - `Book Architecture Audit` (Launches scheduling modal)
  - `Launch Live Sandbox (0 Login)` (Routes to `/w/northwind-pay/home`)
  - **Executive Command Center Viewport (Hero Illustration):**
    - Target: `payments-core` (Root Settlement Engine, SPOF #1, Risk `99.1/100`)
    - Colliding Exceptions: `EXP-2024-089` (Timeout Override, Ghost Owner Priya Raman), `EXP-2024-104` (Ledger Skip), `EXP-2024-118` (Concurrency Cap).
    - Living FalkorDB Proof Path: `Customer Path` $\to$ `checkout-api` (84.0) $\to$ `payments-core` (99.1).
    - Steward AI Agent ProposedAction card with interactive `[Approve]` and `[Review Proof]` toggle.

---

### Section 2: Proof & Telemetry Strip (Immediate Integrity Guarantees)
* **Component Reference:** `frontend/components/marketing/proof-strip.tsx`
* **Topic (Category Tag):**
  > `PERFORMANCE AND INTEGRITY GUARANTEES`
* **Header & Metric Grid:**
  1. **Metric 1:** `14 Tools` — *Read-Only Reasoning*
  2. **Metric 2:** `<20ms` — *Pre-Merge Gate Latency*
  3. **Metric 3:** `100%` — *Grounded Proof Paths*
  4. **Metric 4:** `0 Login` — *Developer Sandbox*
* **Taglines (Sublabels):**
  1. `8 pre-compiled Cypher rules (0% LLM)`
  2. `p95 traversal on service graph`
  3. `Living graph nodes, 0 hallucinated IDs`
  4. `Interactive Northwind Pay telemetry`

---

### Section 3: Documented Outage Post-Mortems (Real-World Disaster Evidence)
* **Component Reference:** `frontend/components/marketing/case-studies-section.tsx` & `stacking-card.tsx`
* **Topic (Category Tag):**
  > `INCIDENT POST-MORTEMS · ROOT CAUSE ANALYSIS`
* **Header:**
  > `How graph governance prevents systemic outages`
* **Tagline (Description):**
  > `Real-world engineering disasters from top tech companies. Here is how Reprieve's deterministic graph rules intercept these failure modes before code merges.`
* **Case Studies Detailed:**
  1. **CrowdStrike Falcon Sensor (July 2024):**
     - *Loss Figure:* `8.5M Systems Crashed`
     - *Root Cause:* Rapid-response content update in Channel File 291 passed syntax gates but skipped staged rollout on the kernel path.
     - *Reprieve Intercept:* Flags uncanaried bypasses on root operating dependencies (`Rule R4: Service Concentration`, `Rule R8: Customer-Path Exposure`).
  2. **Change Healthcare / UnitedHealth Group (March 2024):**
     - *Loss Figure:* `$1.6B Claims Freeze`
     - *Root Cause:* Unmonitored legacy Citrix portal had no MFA enabled—a forgotten policy exception left behind after a corporate merger with zero active owner.
     - *Reprieve Intercept:* Flags unowned systems and expired policy exceptions before dormant backdoors reach production (`Rule R2: Ghost Owner`, `Rule R7: Broken Compensating Control`).
  3. **Square / Block, Inc. (September 2023):**
     - *Loss Figure:* `24-Hour Checkout Outage`
     - *Root Cause:* Internal firewall update coincided with a DNS server upgrade, exhausting DNS capacity and severing microservices from checkout payment gateways.
     - *Reprieve Intercept:* Detects compound change collisions when concurrent infrastructure updates intersect on shared resolution paths (`Rule R4: Service Concentration`, `Rule R6: High-Blast Wave`).
* **Interactive Sandbox Banner:**
  - *Topic:* `SIMULATED BENCHMARK · 185 Microservices · $40M Daily Volume`
  - *Header:* `Try It Yourself: Interactive Sandbox Simulation`
  - *Tagline:* `Explore four colliding Cyber Monday waivers 2 hops from customer checkout. Test all 8 detection rules, inspect shortest proof paths, and run temporal collision scrubbers with zero login required.`

---

### Section 4: How It Works (Three Native Developer Interfaces)
* **Component Reference:** `frontend/components/ui/features-card.tsx`
* **Topic (Category Tag):**
  > `HOW IT WORKS`
* **Header:**
  > `Three Native Interfaces. Zero Friction.`
* **Tagline (Description):**
  > `Developers don't want another dashboard. Reprieve comments directly on pull requests, exposes 14 graph reasoning tools to Cursor and Claude Desktop via MCP, and runs in 12ms inside your CI pipeline with zero login.`
* **Bento Grid Interface Tiles:**
  1. **CLI Scanner (Zero-Login):**
     - *Header:* `CLI Scanner`
     - *Command:* `npx reprieve scan --strict`
     - *Tagline:* `Local AST code parser mining #nosec, @skip, and temporary flags. Evaluates multi-hop cascades before push.`
  2. **MCP Protocol (14 Tools):**
     - *Header:* `MCP Protocol`
     - *Config:* `{"mcpServers": {"reprieve": {"url": "https://api.reprieve.dev/mcp"}}}`
     - *Tagline:* `Model Context Protocol endpoint for Cursor and Claude Desktop. Read-only graph reasoning tools with deterministic grounding: uncited entity IDs are stripped automatically.`
  3. **PR Circuit Breaker (Exit Code 1):**
     - *Header:* `PR Circuit Breaker`
     - *Workflow:* GitHub Action step running `npx reprieve check --horizon 30 --fail-threshold 75.0`
     - *Tagline:* `Continuous integration action blocking merges when multi-squad exceptions breach safety thresholds. Halts cascading failures in 12ms.`

---

### Section 5: Living Compound Risk & Simulation (Interactive Dashboard Preview)
* **Component Reference:** `frontend/app/(marketing)/page.tsx` (Lines 187–317)
* **Topic (Category Tag):**
  > `LIVING COMPOUND RISK`
* **Header:**
  > `Exceptions are approved alone. Risk compounds across the graph.`
* **Tagline (Description):**
  > `Sprint boards treat waivers as isolated tickets. Reprieve projects them onto your microservice topology to catch cascading failures before peak traffic.`
* **Interactive Modules:**
  - **Concentration Telemetry Tabs:**
    - `checkout-api`: 4 independent squad waivers directly 2 hops from customer checkout (Score `84.0 / 100`, Tier-1 Alert).
    - `card-vault`: 3 waivers accumulated around HSM tokenization and credential boundary (Score `78.5 / 100`, Tier-2 Alert).
    - `payments-core`: 4 squad waivers concentrated on high-throughput settlement engine (Score `82.4 / 100`, Tier-1 Alert).
  - **Temporal Collision Scrubber:**
    - Live slider simulating Day +0 to Day +30 horizon showing temporal cluster overlap.
  - **Precedent Memory Recall Card:**
    - *Topic:* `FalkorDB Semantic Memory`
    - *Header:* `Precedent Memory Recall`
    - *Tagline:* `Past review decisions automatically resurface when the same control or service is evaluated. (Outcome: "Third renewal with no rotation plan. Revoked; owner to schedule key rotation.")`
  - **Trust Chips:**
    - `A human approves every change`
    - `Scores are deterministic, never AI-guessed`
    - `100% Grounded proof paths cite living nodes`

---

### Section 6: Frequently Asked Questions (FAQ)
* **Component Reference:** `frontend/app/(marketing)/page.tsx` (Lines 320–341)
* **Topic (Category Tag):**
  > `FREQUENTLY ASKED QUESTIONS`
* **Header:**
  > `Frequently Asked Questions`
* **Core Q&A Pairs:**
  1. **Q: What is Reprieve?**  
     *A:* An agentic safety platform that tracks temporary exceptions (security waivers, flag overrides, skipped tests, limit extensions) as a graph, detects when they add up to real risk, and routes a review to the person who can decide today.
  2. **Q: Is it a GRC suite?**  
     *A:* No. Reprieve does one job: exception debt. It does not manage policies, audits or vendor risk. It complements the tools where exceptions are approved.
  3. **Q: How are risk scores calculated?**  
     *A:* With a published, deterministic formula over the graph: exception severity, age, how overdue it is, how central the affected service is, and rule multipliers. The same inputs always give the same score. AI never sets a number.
  4. **Q: What does the AI do, and what is sent to it?**  
     *A:* The Steward answers questions and drafts proposals using tools over your graph. It sends entity IDs, names and short excerpts, never whole documents. Every claim must cite an entity, and uncited claims are removed.
  5. **Q: Can I turn the AI off?**  
     *A:* Yes. Each workspace has an AI mode. With AI off, detection, scoring, proof paths and reviews keep working; only the Steward and AI-written summaries are disabled.
  6. **Q: Does anything change without my approval?**  
     *A:* No. The Steward can only propose. Reviews, activations and other changes need an explicit Approve from someone with the right role.
  7. **Q: Can I try it without my own data?**  
     *A:* Yes. The sample workspace, Northwind Pay, loads a realistic payments company with services, people and exceptions so you can explore every feature on a simulated date with zero login.
  8. **Q: Where is my data stored?**  
     *A:* In a per-workspace FalkorDB graph database. During early beta, use the sample workspace or non-sensitive data.

---

### Section 7: Final Conversion Call To Action (Bottom of Page)
* **Component Reference:** `frontend/app/(marketing)/page.tsx` (Lines 344–372)
* **Topic (Category Tag):**
  > `GET STARTED`
* **Header:**
  > `Map and intercept exception debt across your architecture`
* **Tagline (Description):**
  > `Book a 15-minute confidential architecture audit, or explore our live Northwind Pay environment today.`
* **Action Buttons:**
  - `Book Architecture Audit`
  - `Launch Live Sandbox (0 Login)`

---

## 🔬 Page 03: Detection Rules Reference Page (`/rules`)
* **File Reference:** `frontend/app/(marketing)/rules/page.tsx`
* **Route:** `/rules`

### Header & Value Proposition:
* **Topic (Category Tag):**
  > `DETERMINISTIC GRAPH INVARIANTS`
* **Header:**
  > `Compound Risk Detection Rules`
* **Tagline (Description):**
  > `Explore the 8 deterministic Cypher graph traversal rules (R1–R8) powering Reprieve's exception risk detection engine. Every alert is mathematically proven against living topology with zero generative guesswork.`

### The 8 Architectural Rules:
1. **R8: Customer-Path Exposure (Severity: Critical · Topology)**
   - *Plain English:* An active exception reaches an externally critical user journey via dependency edges within 3 hops.
   - *Why It Matters:* When an unreviewed TLS or auth bypass sits directly upstream of checkout or user registration, an outage hits external revenue immediately.
   - *Query:* `rule_r8_customer_path.cypher`
2. **R2: Orphaned Owner / Ghost Owner (Severity: High · Ownership)**
   - *Plain English:* The exception's assigned owner has left the company or is no longer on any owning team.
   - *Why It Matters:* Reviews and renewals silently route to an unmonitored inbox. The waiver persists indefinitely because no active engineer is accountable for closing it.
   - *Query:* `rule_r2_orphaned_owner.cypher`
3. **R4: Service Concentration (Severity: Critical · Topology)**
   - *Plain English:* At least 3 active exceptions accumulate within 2 dependency hops of a single core service.
   - *Why It Matters:* Microservices degrade gracefully until multiple unmitigated waivers concentrate around the same bottleneck, triggering cascade failures during traffic spikes.
   - *Query:* `radius_paths.cypher`
4. **R3: Shared Fallback Bottleneck (Severity: High · Mitigation)**
   - *Plain English:* Multiple compensating controls across different exceptions depend on the same individual or single point of failure.
   - *Why It Matters:* If three automated compliance controls are waived on condition that 'Sam Okafor manually spot-checks transactions', Sam becomes a single human point of failure.
   - *Query:* `rule_r3_shared_fallback.cypher`
5. **R6: Temporal Expiry Collision (Severity: High · Lifecycle)**
   - *Plain English:* Multiple exceptions across different services are scheduled to expire in the exact same 7-day window.
   - *Why It Matters:* Teams are overwhelmed by simultaneous waiver expirations or concurrent revert rollouts during critical traffic periods like Cyber Week.
   - *Query:* `rule_r6_expiry_collision.cypher`
6. **R7: Broken Compensating Control (Severity: Critical · Mitigation)**
   - *Plain English:* An active exception relies on a compensating control that has failed its automated health check or was never verified.
   - *Why It Matters:* A waiver is only as safe as its safety net. When the fallback control is broken, the service is running unprotected in production.
   - *Query:* `rule_r7_broken_control.cypher`
7. **R5: Renewal Treadmill (Severity: Moderate · Lifecycle)**
   - *Plain English:* An exception has been renewed 3 or more consecutive times without permanent resolution.
   - *Why It Matters:* 'Temporary' waivers become permanent tech debt by default when teams rubber-stamp renewals instead of refactoring root causes.
   - *Query:* `rule_r5_renewal_chain.cypher`
8. **R1: Expiring Exception (Severity: Moderate · Lifecycle)**
   - *Plain English:* An active exception will expire within the configured warning horizon (default: 14 days).
   - *Why It Matters:* Proactive warning before automated security scanners or compliance gates suddenly fail production builds on expired waivers.
   - *Query:* `rule_r1_expiring.cypher`

---

## 🏛️ Page 04: Technical Architecture Page (`/architecture`)
* **File Reference:** `frontend/app/(marketing)/architecture/page.tsx`
* **Route:** `/architecture`

### Header & Value Proposition:
* **Topic (Category Tag):**
  > `THREE-GRAPH FALKORDB ARCHITECTURE`
* **Header:**
  > `Graph-First, LLM-Second`
* **Tagline (Description):**
  > `Why we don't let AI write graph queries. Reprieve uses a three-tier FalkorDB topology to keep tenant identities isolated, detection queries provably deterministic, and agent memory persistent across turns.`

### The Three Graphs Per Workspace:
1. **`platform_<prefix>` (Identity & Multi-Tenancy):**
   - *Purpose:* Stores user accounts, workspace memberships, role-based access control (RBAC), and notifications. Completely decoupled from domain telemetry.
   - *Labels:* `User`, `Workspace`, `Membership`.
2. **`org_<ws_id>` (Domain Risk Fabric):**
   - *Purpose:* Holds the connected microservice landscape: services, dependency edges, people, teams, compensating controls, and active exceptions.
   - *Labels:* `Service`, `Exception`, `Person`, `Team`, `Control`.
3. **`mem_<ws_id>` (Agent Memory & Precedent):**
   - *Purpose:* Persistent episodic, semantic, and procedural memory for the Steward AI assistant. Stores conversational turns, learned domain facts, runbooks, and on-call handoff tasks.
   - *Labels:* `Turn`, `Fact`, `Playbook`, `HandoffTask`, `Ref`.

### The Dual-Agent Engine:
* **The Sentinel Agent:** Autonomous Detection Engine · 0% LLM. Runs on every graph write or schedule; evaluates all 8 Cypher detection rules in under 65ms; computes PageRank centrality; produces immutable alerts.
* **The Steward Agent:** Grounded Conversational Reviewer · Strict Guardrails. The LLM never writes Cypher; tool reads only (max 6 tools/turn); writes require human approval (`ProposedAction`); regex Groundedness Guard strips uncited entity IDs.

---

## 🛡️ Page 05: Compliance & Legal Pages

### 1. Privacy Policy (`/privacy`)
* **File Reference:** `frontend/app/(marketing)/privacy/page.tsx`
* **Topic:** `DATA SOVEREIGNTY & MINIMAL EXTRACTION`
* **Header:** `Privacy Policy`
* **Core Commitments:**
  - Zero Model Training guarantee across all AI subprocessors.
  - Strict metadata-only ingestion (services, dependency links, exception tickets; never production source code or database payloads).
  - Full GDPR / CCPA compliant data controller contact (`privacy@reprieve.dev`).

### 2. Cookie Policy (`/cookies`)
* **File Reference:** `frontend/app/(marketing)/cookies/page.tsx`
* **Topic:** `TRANSPARENCY & TRACKER-FREE DESIGN`
* **Header:** `Cookie Policy`
* **Core Commitments:**
  - Zero third-party advertising cookies, zero behavioral tracking pixels (Meta, Google Ads).
  - Strictly necessary authentication tokens only (`__session` via Clerk, `reprieve_workspace`, `reprieve_theme`).
  - Legally exempt from intrusive cookie popups under EU ePrivacy Directive Article 5(3).

### 3. Terms of Service (`/terms`)
* **File Reference:** `frontend/app/(marketing)/terms/page.tsx`
* **Topic:** `ENTERPRISE AGREEMENT & SAFETY INVARIANTS`
* **Header:** `Terms of Service`
* **Core Commitments:**
  - Human-in-the-Loop Mandate: Automated proposals produce `ProposedAction` objects requiring explicit human confirmation.
  - Your IP Remains Yours: Complete customer ownership of graph schemas, exception registries, and playbooks.
  - Permissive Open Source licensing (MIT).

---

## 🐾 Page 06: Global Marketing Footer
* **File Reference:** `frontend/components/ui/footer-01.tsx`

### Column Structure:
* **Product Column:**
  - `Detection Rules` (`/rules`)
  - `Graph Explorer` (`/w/northwind-pay/graph`)
  - `Architecture` (`/architecture`)
  - `Incident Analyses` (`/#case-studies`)
  - `Compound Telemetry` (`/#telemetry-heading`)
* **Developers Column:**
  - `Zero-Login CLI` (GitHub repo link)
  - `MCP Protocol` (`/api/v1/workspaces/northwind-pay/mcp/tools`)
  - `Pre-Merge CI Gate` (`/#developer-hub`)
  - `Live Sandbox` (`/w/northwind-pay/home`)
  - `API Keys` (`/w/northwind-pay/settings?tab=api-keys`)
* **Governance Column:**
  - `8 Cypher Invariants` (`/rules`)
  - `SOC2 Proof Export` (`/w/northwind-pay/graph`)
  - `FalkorDB C-Engine` (`/architecture`)
  - `Zero Model Training` (`/privacy#model-training`)
* **Legal Column:**
  - `Terms of Service` (`/terms`)
  - `Privacy Policy` (`/privacy`)
  - `Cookie Policy` (`/cookies`)
  - `Security Baseline` (`/architecture`)
* **Bottom Status Bar:**
  - `Steady System Status: All Systems Operational`
  - `© 2026 Reprieve Inc. All rights reserved.`
