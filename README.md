# AI Regulatory Compliances

Curated YAML policies and guardrails that map AI systems to regulatory requirements across jurisdictions. The repository is organized by country, regulatory domain, and source framework, with each YAML file capturing a self-contained compliance role, scope, and objectives.

## Repository Layout

- **Top level:** Compliant jurisdiction folders (`compliant_china`, `compliant_eu`, `compliant_japan`, `compliant_singapore`, `compliant_south_korea`, `compliant_us`) and interoperability mappings (`interop`).
- **Domain level:** Simplified topical areas such as `core`, `privacy`, `security`, `responsible`, `synthetic`, `ip`, `autonomous`, `finance`, `healthcare`, `labor`, `consumer`, `defense`, `transportation`, `state`, and `energy`.
- **Files:** YAML policy/guard definitions that encode compliance logic for specific roles or controls, moved directly into domain folders (no framework-level subdirectories).

## Regulatory Coverage

This repository currently tracks compliance adherence for the following frameworks:

### 🇨🇳 China AI Governance
*Focus: Security, Ideological Alignment, Labeling, and Labor Rights.*
- **Generative AI:** CAC Interim Measures for Generative AI Services (2023).
- **Synthetic Media:** CAC Deep Synthesis Provisions (2023) & GB 45438-2025.
- **Algorithms:** CAC Recommendation Algorithm Provisions (2022) & GB/T Technical Standards.
- **Law & Judiciary:** China Draft AI Law (2025-2026) & Labor Court Precedents on AI Redundancy.
- **Cybersecurity:** China Cybersecurity Law Amendments (2026) & National Security Integration.

### 🇸🇬 Singapore AI Governance
*Focus: Interoperability, Financial Fairness, and Model Assurance.*
- **Core Governance:** Singapore Model AI Governance Framework (2024) & Enterprise Framework.
- **Testing & Verification:** AI Verify Interoperability Framework & AI Verify Toolkit.
- **Financial Sector:** MAS FEAT Principles & Veritas Initiative (Project MindForge).
- **Legal/Judiciary:** Singapore Courts’ Guide on Generative AI Tools (2024).
- **Privacy:** PDPC Advisory Guidelines on AI Systems (2024).

### 🇰🇷 South Korea AI Governance
*Focus: High-Impact Gating, Transparency, and Medical Device Safety.*
- **Foundational Law:** South Korea AI Basic Act (Transparency & High-Impact AI Gating).
- **Financial Sector:** FSC Guidelines on AI in the Financial Sector.
- **Healthcare:** MFDS AI Medical Device Approval Guidelines & Continuous Learning Guards.
- **Privacy & IP:** PIPA Article 37-2 (Automated Decision Rights) & MCST Copyright Guidelines.
- **Ethics:** MSIT National Guidelines for AI Ethics.

### 🇯🇵 Japan AI Governance
*Focus: Sovereignty, Innovation Promotion, and Medical Data.*
- **Core Governance:** AI Promotion Act (2025) & METI/MIC AI Guidelines.
- **Healthcare:** Next-Gen Medical Infrastructure Act & PMD Act (SaMD Continuous Learning).
- **Intellectual Property:** Copyright Act Article 30-4 (AI Training).
- **Privacy:** APPI 2026 Amendments (Privacy Preserving AI).

### 🇺🇸 USA AI Governance
*Focus: Executive Mandates, State-Level Privacy, and Algorithmic Accountability.*
- **Federal Strategy:** Executive Order 14110 (Safety & Security) & EO 14179 (Leadership).
- **Core Principles:** White House Blueprint for an AI Bill of Rights & National AI Initiative Act.
- **State Privacy:** CCPA/CPRA (California), BIPA (Illinois), ADMT (Colorado), CTDPA (Connecticut), MCDPA (Minnesota).
- **Sectoral Regulation:** FDA PCCP (Healthcare), FAA Reauthorization (Aviation), FTC Consumer Protection.
- **Specialized Domains:** Tennessee ELVIS Act (Voice/Likeness), NYC AEDT (Employment Fairness).

### 🇪🇺 EU AI Governance
*Focus: Risk-Based Classification, Conformity Assessments, and Fundamental Rights.*
- **AI Act:** High-Risk AI Systems, Prohibited Practices, and General Purpose AI.
- **Healthcare:** Annex I & III Conformity for Medical AI.

## YAML Format

Most files follow a shared schema:
- **metadata:** Provenance for the source framework and policy type.
- **regulatory_scope:** Specific regulatory topics/articles covered.
- **identity:** Compliance role, specialization, and operational posture.
- **scope:** Applicable systems, components, or deployment contexts.
- **objectives:** Concrete compliance actions, checks, and guardrails.

## How to Use

Select a jurisdiction and domain folder, then consume the YAML files as policy inputs for governance tooling, compliance checklists, or agentic guardrails. Each YAML is intentionally self-contained.

> **Note:** This repository is informational and does not constitute legal advice.
