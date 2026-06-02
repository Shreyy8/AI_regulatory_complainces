"# AI_Regulatory_Complainces

Curated YAML policies and guardrails that map AI systems to regulatory requirements across jurisdictions. The repository is organized by country, regulatory domain, and source framework, with each YAML file capturing a self-contained compliance role, scope, and objectives.

## Repository layout

- **Top level:** country/jurisdiction folders (currently **china_ai_governance** and **south_korea_ai_governance**).
- **Domain level:** topical areas such as `core_governance`, `privacy`, `cybersecurity`, `responsible_ai`, `synthetic_media`, `intellectual_property`, `autonomous_systems`, `financial_ai`, and `healthcare_ai`.
- **Framework level:** directories named after the source regulation or standard (for example, `gb_t_45652_2025`, `cac_interim_measures_generative_ai_services`, `south_korea_ai_basic_act`).
- **Files:** YAML policy/guard definitions (snake_case filenames) that encode the compliance logic for a specific role or control.

## YAML format (typical)

Most files follow a shared schema:

- **metadata:** provenance for the source framework (and sometimes policy type).
- **regulatory_scope:** the regulatory topics covered.
- **identity:** the compliance role, specialization, and operational posture.
- **scope:** where the policy applies (systems, components, or deployment contexts).
- **objectives:** the concrete compliance actions and checks.

Some frameworks include additional keys, but the structure above is the common baseline.

## How to use

Select a jurisdiction, domain, and framework folder, then consume the YAML files as policy inputs for governance tooling, compliance checklists, or prompt/agent guardrails. Each YAML is intentionally self-contained so it can be loaded independently or composed with others.

> **Note:** This repository is informational and is not legal advice."
