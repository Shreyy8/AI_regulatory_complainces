# AI Regulatory Compliances

Curated YAML policies and guardrails that map AI systems to regulatory requirements across jurisdictions. The repository is organized by country, regulatory domain, and source framework, with each YAML file capturing a self-contained compliance role, scope, and objectives.

## Repository Layout

- **Top level:** Country/jurisdiction folders (**China**, **Singapore**, and **South Korea**).
- **Domain level:** Topical areas such as `core_governance`, `privacy`, `cybersecurity`, `responsible_ai`, `synthetic_media`, `intellectual_property`, `autonomous_systems`, `financial_ai`, `healthcare_ai`, and `labor_governance`.
- **Framework level:** Directories named after the source regulation or standard (e.g., `gb_t_45652_2025`, `mas_feat_principles`, `south_korea_ai_basic_act`).
- **Files:** YAML policy/guard definitions that encode compliance logic for specific roles or controls.

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

## YAML Format

Most files follow a shared schema:
- **metadata:** Provenance for the source framework and policy type.
- **regulatory_scope:** Specific regulatory topics/articles covered.
- **identity:** Compliance role, specialization, and operational posture.
- **scope:** Applicable systems, components, or deployment contexts.
- **objectives:** Concrete compliance actions, checks, and guardrails.

## How to Use

Select a jurisdiction, domain, and framework folder, then consume the YAML files as policy inputs for governance tooling, compliance checklists, or agentic guardrails. Each YAML is intentionally self-contained.

> **Note:** This repository is informational and does not constitute legal advice.
