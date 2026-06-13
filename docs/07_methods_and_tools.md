# Methods And Tools

## Purpose

Catalogue existing tools that may operationalize, probe, or structure parts of the hypothesis.

These tools are not proof of the hypothesis.

## Material That Belongs Here

- what the tool is
- what it was intended to surface
- what the source material says about its scope
- whether existing outputs are present
- whether the tool is measurement, profiling, analogy search, or corpus processing

## Material That Must Not Go Here

- new runs
- newly inferred findings
- tool output interpreted as confirmation

## Likely Tooling Sources

- `Symbound-Entropy-Architecture/CognitiveGenome_ApeTest_v0.1.md`
- `Symbound-Entropy-Architecture/ape_test_v0_1.py`
- `Symbound-Entropy-Architecture/ape_score_v0_1.py`
- `Symbound-Entropy-Architecture/ape_score_llm_v0_1.py`
- `Cognitive_Crowbar/README.md`
- `Cognitive_Crowbar/examples/generated_profile/*`
- `Cognitive_Crowbar_nonverbal/README.md`
- `Symbound-UAE-GVS/README.md`
- `Symbound_Academia_Spine/README.md`
- `docs/06_formalism_and_math_notes.md`

## Suggested Internal Sections

- cognition topology and profiling
- structural analogy and vector sweep tooling
- corpus processing and extraction tooling
- existing outputs
- methods that remain prospective only

## First-Pass Methods And Tools Catalogue

This catalogue includes existing tools that may help operationalize, probe, structure, or document parts of the broader entropy-folding ecosystem.

None of these tools should be treated as proof of the hypothesis.

## 1. ApeTest / Cognitive Genome Tooling

Primary sources:

- `Symbound-Entropy-Architecture/CognitiveGenome_ApeTest_v0.1.md`
- `Symbound-Entropy-Architecture/CognitiveGenome-ApeTest-v0.1/README.md`
- `Symbound-Entropy-Architecture/ape_test_v0_1.py`
- `Symbound-Entropy-Architecture/ape_score_v0_1.py`
- `Symbound-Entropy-Architecture/ape_score_llm_v0_1.py`
- `Symbound-Entropy-Architecture/CognitiveGenome-ApeTest-v0.1/spec/README_scoring_layer_snippet.md`

What it is:

- a non-clinical cognition-topology snapshot tool
- a probe-and-scoring pipeline for structural traits such as recursion depth, representation preference, compression style, ambiguity tolerance, and overload failure mode
- a profiling instrument designed to leave downstream hook points for scaffolding, support design, and human-AI adaptation work

What it appears intended to surface:

- differences in how thinking is structured
- cognitive-topology signatures that may matter for catalyst fit, gear-mesh, and support design
- preconditions or pressure points relevant to folding-like dynamics, such as overload, ambiguity handling, recursion pressure, compression behaviour, and profile instability
- downstream hook points for scaffolding or prosthetic support
- a structured profile format that other tools can consume

Existing outputs present:

- `sample_profile_manual.json`
- `sample_profile_llm.json`
- `sample_raw_response.json`

Important methodological role in this repo:

- ApeTest is the closest existing instrument in the source ecosystem to the cognitive-topology side of the hypothesis.
- It does not prove entropy folding or eureka cascade.
- It does help show that the ecosystem already contains an instrument intended to snapshot profile shape, overload response, ambiguity handling, compression tendency, and related structural traits.
- That makes it relevant to the question of what kind of topology a later catalyst may be fitting, even when no full stuck-vault-pivot-cascade sequence is demonstrated.

What it can support in this repo:

- examples of existing instrumentation for structural profiling
- vocabulary for discussing operational profiling layers in the ecosystem
- a concrete methods reference for the "cognitive topology snapshot/profiling instrument" lane
- separation between topology profiling, analogy sweep, and reflective extraction tooling

What it must not be used as:

- proof of entropy folding
- a psychometric truth device
- evidence that a given profile confirms the hypothesis
- proof of cognition, sentience, or intelligence
- a conclusion engine that can turn profile scores into theory confirmation

## 2. Cognitive Crowbar

Primary sources:

- `Cognitive_Crowbar/README.md`
- `Cognitive_Crowbar/docs/architecture_overview.md`
- `Cognitive_Crowbar/docs/faq_for_researchers.md`
- `Cognitive_Crowbar/examples/example_summary.md`

What it is:

- a small local-only reflection tool with three stages: pattern sampling, guided reflection, and summary generation

How it differs from ApeTest:

- Cognitive Crowbar is primarily a reflective and pattern-extraction aid.
- ApeTest is a cognitive-topology snapshot/profiling instrument.

What it appears intended to surface:

- mechanical differences in text-pattern profiles
- user-authored descriptions of associated internal states
- compact descriptive term summaries

Existing outputs present:

- `examples/generated_profile/pattern_samples.json`
- `examples/generated_profile/introspective_notes.json`
- `examples/generated_profile/mechanisms.json`

What it can support in this repo:

- a conservative example of mechanism-only introspective tooling
- evidence that some parts of the ecosystem already separate measurement, self-report, and summary

What it must not be used as:

- diagnosis
- automated inference of hidden mental states
- proof that entropy-folding constructs are correct

## 3. Cognitive Crowbar - Non-Verbal Edition

Primary sources:

- `Cognitive_Crowbar_nonverbal/README.md`
- `Cognitive_Crowbar_nonverbal/Recommended_layout.md`

What it is:

- a non-verbal behavioral-entropy segmentation tool for time-series behavior logs

What it appears intended to surface:

- high-entropy versus low-entropy episodes
- transition windows
- recurring problem-solving or friction patterns in non-verbal agents

Existing outputs present:

- the recommended layout names `episodes.json` and `state_summary.json`
- no bundled example output files were confirmed during this pass

What it can support in this repo:

- a methods example showing how the ecosystem tries to generalize structure-tracking beyond text

What it must not be used as:

- proof of cross-substrate equivalence
- mind reading
- evidence that behavioral segmentation validates the core hypothesis

## 4. UAE / GVS

Primary sources:

- `Symbound-UAE-GVS/README.md`
- `Symbound-UAE-GVS/PUBLIC_SUMMARY.md`
- `Symbound-UAE-GVS/RESEARCHER_EDITION.md`

What it is:

- a structured analogy, property-mapping, and vector-sweep reasoning framework

How it differs from ApeTest:

- UAE/GVS is a structural analogy and vector-sweep lens.
- ApeTest is a topology snapshot/profiling instrument rather than an analogy search method.

What it appears intended to surface:

- cross-domain property overlap
- analogy spaces
- implication-space mapping
- candidate high-value, low-risk structural correspondences

What it can support in this repo:

- documentation of an existing reasoning lens already present in the ecosystem
- clarification that some later correspondences may have been imagined through structured analogy methods

What it must not be used as:

- a creativity-free proof generator
- evidence merely because an analogy can be found
- justification for inflating weak correspondences into strong claims

## 5. Symbound Academia Spine

Primary sources:

- `Symbound_Academia_Spine/README.md`
- `Symbound_Academia_Spine/academic_abstract.md`

What it is:

- a corpus-processing and academic-consolidation pipeline for large research archives

What it appears intended to surface:

- domain sorting
- extraction and slicing
- consolidation into publication-ready fragments

What it can support in this repo:

- provenance for how large bodies of source material may have been made tractable
- evidence that corpus-processing and consolidation tooling already exists in the reference ecosystem

What it must not be used as:

- evidence for the hypothesis
- a substitute for source-specific reading

## 6. Method-Like Materials In Downstream Theory Repos

Some downstream theory repos also include proposed measurement or replication language.

Examples:

- `entropy-folding-as-directed-thermodynamics-for-cognition-finished/paper.md`
- `perpetual_cognition_reactor/PCR_Methodology_and_Replication_Protocol_v1.md`

What these can support:

- a record that parts of the source corpus attempt to specify measurement, replication, and cross-substrate procedures

Current caution:

- some of this material is more expansive than the narrowest responsible core-hypothesis reading
- use it as methodological context, not as settled confirmation

## Practical Rule For This Repo

When a tool or method is mentioned in the hypothesis repo, the default interpretation should be:

- this is an existing attempt to operationalize or inspect structure
- this does not by itself validate the underlying theory
