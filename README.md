# DIKWP DesireBalance Studio V2

Created by Yucong Duan (段玉聪).

A standalone, offline-first interactive prototype for transforming desire-driven prosperity and anti-involution governance from abstract debate into a DIKWP semantic workbench.

## Core workflow

Desire expression → Purpose Contract → Desire portfolio → D/I/K/W/P/R ledger → 3-No SemanticClosure → Involution pressure map → Prosperity conversion lab → Role playbook → Action Tickets → Audit and export.

## Quick start

1. Double-click `index.html` in a modern browser.
2. Select a synthetic scenario: individual, family, organization, platform, community, or policy.
3. Explore Dashboard → Desire Portfolio → DIKWP Ledger → SemanticClosure → Involution Map → Prosperity Lab → Role Playbook → Action Tickets → Audit.
4. Edit sliders and export JSON, CSV, or Markdown.

No server, database, API key, model endpoint, account, or network is required.

Optional CLI:

```bash
python cli/desirebalance_cli.py analyze data/sample_scenarios.json \
  --scenario organization_kpi_involution \
  --out outputs/organization_demo

python cli/desirebalance_cli.py static-audit . \
  --out outputs/static_boundary_audit_report.json
```

Or run all bundled scenarios:

```bash
python run_demo.py
```

## What V2 implements

- Single-file browser studio for direct demonstration
- Six user modes: individual, household, organization, platform, community, policy
- Six synthetic scenario families
- Live parameter editing and immediate re-scoring
- DIKWP D/I/K/W/P/R ledger
- Three-No analysis: incompleteness, imprecision, inconsistency
- SemanticClosure S0–S4 grading
- Desire Quality Index (DQI)
- Prosperity Contribution Index (PCI)
- Involution Pressure Index (IPI)
- Capture Risk Index (CRI)
- Capability Conversion Efficiency (DCCE)
- Time Sovereignty Index (TSI)
- Purpose Coherence Score (PCS)
- Desire–Prosperity Balance Index
- Interactive policy and organizational intervention simulator
- Role-specific governance playbooks
- Action Tickets with evidence, owner, rollback, and kill conditions
- Local JSON import and JSON/CSV/Markdown export
- Standard-library-only CLI, tests, schemas, demo outputs, and static boundary audit

## Important boundary

This project is a deliberation, education, workshop, organizational-redesign, and reversible policy-pilot prototype. It must not be used for:

- punitive social scoring
- welfare or benefit eligibility decisions
- employment, dismissal, promotion, compensation, or disciplinary decisions
- credit, insurance, policing, immigration, or education admission decisions
- covert profiling or manipulation of inferred intentions
- automatic denial of services
- moral ranking of persons or groups
- replacing qualified social-science, labour, legal, clinical, or policy professionals

All bundled people, organizations, and cases are synthetic.

## Suggested Chinese name

DIKWP欲望—繁荣—反内卷语义治理工作台 V2

## Design lineage

This V2 package extends the earlier `DIKWP DesireBalance OS` reference implementation. It follows the recent YucongDuan GitHub demonstration pattern: standalone, offline-first, browser-openable, role/scenario driven, with optional CLI and auditable exports.

## License and attribution

Apache-2.0. See `NOTICE` and `CITATION.cff` for DIKWP / Yucong Duan attribution.
