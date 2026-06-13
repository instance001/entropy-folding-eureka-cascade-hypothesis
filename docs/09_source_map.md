# Source Map

## Purpose

Track which source repositories and files feed which parts of this consolidation repo.

## Suggested Table Fields

- source repo
- source file
- classification
- target doc in this repo
- confidence
- notes

## Classification Values

- hypothesis source
- tooling or method source
- background or provenance
- excluded from this repo

## Drafting Rule

Use file-level traceability where possible, not just repo-level traceability.

## First-Pass Source Map

| Source Repo | Source File | Classification | Target Doc In This Repo | Confidence | Notes |
| --- | --- | --- | --- | --- | --- |
| `entropy-folding-as-directed-thermodynamics-for-cognition-finished` | `README.md` | hypothesis source | `README.md`, `docs/00_reader_guide.md`, `docs/01_hypothesis_summary.md`, `docs/02_claims_and_nonclaims.md`, `docs/05_falsifiability_and_weakening_conditions.md` | high | Best concise statement of repo scope, claims, non-claims, and null-model posture. |
| `entropy-folding-as-directed-thermodynamics-for-cognition-finished` | `paper.md` | hypothesis source | `docs/01_hypothesis_summary.md`, `docs/04_model_structure.md`, `docs/05_falsifiability_and_weakening_conditions.md` | high | Core hypothesis text. |
| `entropy-folding-as-directed-thermodynamics-for-cognition-finished` | `DISCLAIMER.md` | hypothesis source | `docs/00_reader_guide.md`, `docs/02_claims_and_nonclaims.md` | high | Important caution and scope-limiting language. |
| `entropy-folding-as-directed-thermodynamics-for-cognition-finished` | `GLOSSARY.md` | hypothesis source | `docs/03_key_terms_and_minimal_glossary.md` | high | Primary term bank for the cognition-facing EF repo. |
| `entropy-folding-foundational-frameworks` | `README.md` | hypothesis source | `docs/00_reader_guide.md`, `docs/01_hypothesis_summary.md`, `docs/02_claims_and_nonclaims.md`, `docs/04_model_structure.md` | high | Clarifies upstream conceptual-foundation posture. |
| `entropy-folding-foundational-frameworks` | `GLOSSARY.md` | hypothesis source | `docs/03_key_terms_and_minimal_glossary.md` | medium | Useful for term alignment across foundation-layer language. |
| `entropy-folding-foundational-frameworks` | `entropy-folding-foundation-scope/paper.md` | hypothesis source | `docs/04_model_structure.md` | medium | Relevant to scope framing. |
| `entropy-folding-foundational-frameworks` | `entropy-folding-foundation-scale/paper.md` | hypothesis source | `docs/04_model_structure.md` | medium | Relevant to scale framing. |
| `Entropy-Folding-Vector-Theory` | `README.md` | hypothesis source | `docs/01_hypothesis_summary.md`, `docs/04_model_structure.md` | medium | Good orientation to the vector-field framing. |
| `Entropy-Folding-Vector-Theory` | `paper/Paper_v1.0.md` | hypothesis source | `docs/01_hypothesis_summary.md`, `docs/04_model_structure.md`, `docs/06_formalism_and_math_notes.md` | high | Formal substrate-agnostic structural framing. |
| `Entropy-Folding-Vector-Theory` | `GLOSSARY.md` | hypothesis source | `docs/03_key_terms_and_minimal_glossary.md` | medium | Vector-field terminology source. |
| `entropy_folding_scope` | `README.md` | hypothesis source | `docs/04_model_structure.md` | medium | Small but directly on-scope. |
| `entropy_folding_scope` | `entropy_foundation_scope.md` | hypothesis source | `docs/04_model_structure.md` | medium | Likely source for scope-specific language. |
| `entropy_folding_scale` | `README.md` | hypothesis source | `docs/04_model_structure.md` | medium | Scale-specific framing. |
| `entropy-folding-foundational-frameworks` | `entropy-folding-foundation-scope/paper.md` | hypothesis source | `docs/04_model_structure.md`, `docs/05_falsifiability_and_weakening_conditions.md`, `docs/06_formalism_and_math_notes.md` | high | Scope thresholds, domain declaration, abstention logic. |
| `entropy-folding-foundational-frameworks` | `entropy-folding-foundation-scale/paper.md` | hypothesis source | `docs/04_model_structure.md`, `docs/06_formalism_and_math_notes.md` | high | Cross-scale operators and leak-budget formalism. |
| `entropy-folding-foundational-frameworks` | `entropy-folding-foundation-action/paper.md` | hypothesis source | `docs/06_formalism_and_math_notes.md` | high | Action-operator and budget formalism. |
| `entropy-folding-foundational-frameworks` | `entropy-folding-foundation-energy/paper.md` | hypothesis source | `docs/06_formalism_and_math_notes.md` | high | Energy-ledger formalism. |
| `entropy-folding-foundational-frameworks` | `entropy-folding-foundation-ontic/paper.md` | hypothesis source | `docs/06_formalism_and_math_notes.md` | high | Ontic-state and representation formalism. |
| `entropy-folding-foundational-frameworks` | `entropy-folding-foundation-stability/paper.md` | hypothesis source | `docs/05_falsifiability_and_weakening_conditions.md`, `docs/06_formalism_and_math_notes.md` | high | Drift, threshold, hysteresis, rollback conditions. |
| `Symbound-Entropy-Architecture` | `README-2.md` | hypothesis source | `docs/01_hypothesis_summary.md`, `docs/02_claims_and_nonclaims.md`, `docs/04_model_structure.md` | medium | Downstream architecture framing; useful but must not overwrite earlier scope limits. |
| `Symbound-Entropy-Architecture` | `Symbound_Entropy_release.txt` | hypothesis source | `docs/04_model_structure.md` | medium | Extended architecture framing. |
| `Symbound-Entropy-Architecture` | `GLOSSARY.md` | hypothesis source | `docs/03_key_terms_and_minimal_glossary.md` | medium | Operational vocabulary source. |
| `Symbound-Entropy-Architecture` | `README-2.md`, `Symbound_Entropy_release.txt` | hypothesis source | `docs/06_formalism_and_math_notes.md` | medium | Downstream vault, routing, and capacity formal vocabulary; use cautiously. |
| `perpetual_cognition_reactor` | `README.md` | hypothesis source | `docs/01_hypothesis_summary.md`, `docs/08_open_uncertainties.md` | low | Downstream and more expansive; use cautiously. |
| `perpetual_cognition_reactor` | `Perpetual_Cognition_Reactor_OnePage_v1.md` | hypothesis source | `docs/01_hypothesis_summary.md` | medium | Plain-language summary candidate. |
| `perpetual_cognition_reactor` | `PCR_Limitations_Edge_Cases_and_Failure_Modes_v1.md` | hypothesis source | `docs/05_falsifiability_and_weakening_conditions.md`, `docs/08_open_uncertainties.md` | high | Important limitation material. |
| `perpetual_cognition_reactor` | `PCR_Boundary_Conditions_and_Safety_Architecture_v1.md` | hypothesis source | `docs/05_falsifiability_and_weakening_conditions.md` | medium | Boundary-condition source. |
| `perpetual_cognition_reactor` | `PCR_Methodology_and_Replication_Protocol_v1.md` | hypothesis source | `docs/05_falsifiability_and_weakening_conditions.md` | medium | Relevant to testability and replication framing. |
| `perpetual_cognition_reactor` | selected formal, operator, and boundary files | hypothesis source | `docs/06_formalism_and_math_notes.md`, `docs/08_open_uncertainties.md` | medium | Formal downstream material exists, but maturity and consistency vary. |
| `Symbound-Entropy-Architecture` | `CognitiveGenome_ApeTest_v0.1.md` | tooling or method source | `docs/07_methods_and_tools.md` | high | Cognition-topology instrument, not direct hypothesis proof. |
| `Symbound-Entropy-Architecture` | `ape_test_v0_1.py`, `ape_score_v0_1.py`, `ape_score_llm_v0_1.py` | tooling or method source | `docs/07_methods_and_tools.md` | high | Existing scripts that operationalize parts of profiling logic. |
| `Cognitive_Crowbar` | `README.md` | tooling or method source | `docs/07_methods_and_tools.md` | high | Mechanism-only reflection tool. |
| `Cognitive_Crowbar` | `examples/generated_profile/*` | tooling or method source | `docs/07_methods_and_tools.md` | high | Existing example outputs present. |
| `Cognitive_Crowbar_nonverbal` | `README.md` | tooling or method source | `docs/07_methods_and_tools.md` | high | Non-verbal behavioral entropy instrument. |
| `Symbound-UAE-GVS` | `README.md`, `PUBLIC_SUMMARY.md` | tooling or method source | `docs/07_methods_and_tools.md` | medium | Structural analogy / vector sweep tool; method source only. |
| `Symbound_Academia_Spine` | `README.md` | background or provenance | `docs/07_methods_and_tools.md`, `docs/99_provenance_and_editorial_rules.md` | medium | Corpus-processing infrastructure, not hypothesis evidence. |
