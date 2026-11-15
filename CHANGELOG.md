# Changelog

All notable changes to this skill are documented here. Format follows [Keep a Changelog](https://keepachangelog.com/en/1.1.0/); versions follow [Semantic Versioning](https://semver.org/).

## [3.0.0] - 2026-11-15

### Added

- **Third knowledge base**: AICPA® & CIMA® *Rise2040: Shaping the Future of Finance and Accounting — Vision Report* (© 2026), alongside GMAP and the CGMA Competency Framework 2019.
- **Progressive disclosure**: `SKILL.md` is now a 206-line routing controller plus seven `references/` modules (01–07).
- **`references/01-rise2040-framework.md`**: report dossier (25 countries / 95 Future Forums / 6,263 participants), collective purpose–mission–vision, five non-negotiable core beliefs, four constants, trust paradox, identity-shift matrix, eight global themes with polling data, the Anticipatory Organization® methodology (Hard Trends / Soft Trends / Predictable Problems / Pre-solve), complete five-driver matrices, eight tensions, four use cases, the five-step research methodology, and a four-source collation note.
- **`references/02-capability-model-2040.md`**: four capability categories / 18 capabilities with original definitions, observable behaviour anchors, and failure signals; mapping to the CGMA 2019 five domains and GMAP four principles; L0–L4 maturity rubric; three role-based development tracks; capability-audit SOP.
- **`references/03-methodology-toolbox.md`**: 21 named tools across eight seats, each with inputs, steps, outputs, and pitfalls — including DCF formulas and traps, relative valuation, scenario/Monte Carlo and reverse stress testing, VaR/CVaR, covenant metrics, CVP/ABC, transfer-pricing and BEPS framing, AI governance loop, data lineage, FMEA/RPN, red teaming and OODA war-gaming.
- **`references/04-engagement-playbooks.md`**: six end-to-end SOPs (strategy diagnostics; valuation and capital transactions; global tax and compliance; AI governance and assurance; organisation and talent; CFO/board reporting), each with stage gates, owners, deliverables, acceptance criteria, and common failure modes; plus a reusable 90-day controlled-experiment SOP and multi-seat deliberation rules.
- **`references/05-templates-and-checklists.md`**: 14 fill-in templates (decision brief, trend log, pre-solve list, option matrix, red-team rebuttals, DCF assumptions, scenario matrix, board one-pager, 90-day experiment card, capability grid, decision memo, bilingual disclaimers, citation format) and seven checklist groups.
- **`references/06-governance-boundaries.md`**: five professional principles, L1 veto hierarchy, explicit refusal list, output labelling rules, copyright and trademark terms, jurisdiction adaptation, AI human-in-the-loop gate, conflicts of interest, and escalation paths.
- **`references/07-glossary-en-zh.md`**: authoritative EN–ZH glossary of Rise2040 terminology, the five driver titles (with the executive-summary vs body-heading discrepancy noted), all 18 capabilities, professional qualifications, and finance/valuation/tax/AI terms.
- **Eight-seat expert deliberation panel** (S1–S8) with a binding four-level adjudication hierarchy and a mandatory red-team review.
- **Dual-loop operating system**: GMAP value-creation loop + Rise2040 anticipatory loop; six-step decision chain `SCAN → CLASSIFY → PRE-SOLVE → DELIBERATE → DECIDE → EXPERIMENT`.
- **Three-tier labelling** `[事实] / [假设] / [判断]` and five mandatory elements for every deliverable.
- `CHANGELOG.md`, updated README, and archived v2.0.0 full edition under `archive/`.

### Changed

- GMAP four principles rewritten from slogans into auditable actions with explicit failure signals.
- CGMA 2019 five domains repositioned from "the capability model" to "the baseline acceptance standard", paired with the 2040 model as a two-track system.
- The 24 integrated finance skills regrouped by the new workflows and explicitly designated as tools, not sources of conclusions.
- `description` expanded from ~12 to 38 trigger terms; `metadata.knowledge_base` added.
- `skill-card.md` rewritten with a risk/mitigation table, new references, output types, version history, and ethical considerations.
- `_meta.json` version 2.0.0 → 3.0.0 with a `localUpgrade` record.

### Retained / Not Changed

- `.clawhub/origin.json` `installedVersion` left at 2.0.0 — it records the registry install state and should be written back by the release flow, not edited by hand.
- Ethical, disclaimer, and copyright boundaries were **strengthened rather than removed**, consistent with the report's own conclusion that trust is the profession's enduring anchor.
- The v2.0.0 1,330-line single-file edition is preserved at `archive/SKILL-v2.0-full.md`.

## [2.0.0] - 2026-04-17

- Integrated 24 professional finance skills across financial analysis, equity research, investment banking, private equity, wealth management, investment decisions, and startup fundraising.
- Added investment management, valuation modelling, and investment decision modules.

## [1.0.0] - 2026-04-11

- Initial release: GMAP four principles, CGMA 2019 five domains, Chinese management-accounting and capital-markets guidance.
- Added MIT license and ClawHub installation badge.
