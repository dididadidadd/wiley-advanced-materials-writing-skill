# Writing Quality Gates

This file compresses useful principles from recently reviewed open writing skills into rules tailored for AM/AFM-style materials manuscripts.

## Sources Absorbed

- `sciwrite-manuscript-review`: manuscript writing review, clutter removal, active verbs, sentence architecture, keyword consistency, numerical/citation consistency.
- `research-paper-writing`: paragraph flow, reverse outlining, claim-evidence mapping, skeptical reviewer self-review.
- `deslop`: removal of formulaic AI prose while preserving scientific register.
- Existing `scientific-writing`: IMRaD structure, full-paragraph scientific prose, citation and figure/table discipline.

## Pre-Writing Questions

Before drafting or rewriting an abstract/introduction, answer:

1. What technical problem is solved?
2. Why is the existing solution insufficient?
3. What design insight enables the solution?
4. What material architecture implements that insight?
5. What data prove performance and mechanism?
6. What exact application boundary is justified?

If any answer is missing, use `[need ...]` placeholders instead of inventing content.

## Paragraph Flow Gate

Each paragraph must pass four checks:

1. The first sentence states the paragraph's message.
2. The paragraph contains one message, not a pile of related facts.
3. Each sentence connects to the previous sentence by cause, contrast, consequence, refinement, example, or evidence.
4. The paragraph maps to the section thesis.

For weak sections, do a reverse outline:

- write the section thesis;
- list each paragraph's topic sentence;
- list the evidence under each paragraph;
- remove or rewrite paragraphs that do not support the thesis.

## Claim-Evidence Map

For substantial edits, produce this internal or visible map:

`Claim: ... | Evidence: ... | Status: supported / needs evidence / overclaimed`

Hard rule: if a claim cannot be mapped to data, comparison, mechanism, or citation, weaken it or mark it.

Common AM/AFM overclaims:

- durable, without abrasion/corrosion/UV/cycle evidence;
- long-term, without time data;
- self-healing, without recovery data;
- synergistic, without control groups separating component roles;
- universal applicability, based on one substrate or one test environment.

## Five-Pass Language Review

### 1. Cut clutter

Delete filler: "it is worth noting", "it should be emphasized", "in order to", "due to the fact that", "a number of", "in terms of", "plays an important role in" when the role is not specified.

### 2. Resurrect verbs

Prefer verbs over noun stacks:

- "demonstrates" not "provides a demonstration of";
- "confirms" not "offers confirmation of";
- "reduces" not "achieves a reduction in";
- "analyzes" not "conducts an analysis of";
- "protects" not "provides protection for".

### 3. Repair sentence architecture

Keep the subject and main verb close. If a sentence delays the main verb with a long stack of modifiers, split it.

### 4. Enforce terminology

Do not rename samples, mechanisms, or metrics casually. Repetition of technical terms is good when it prevents ambiguity.

### 5. Verify numbers and units

Check values, units, signs, sample labels, percentages, durations, and conditions. Do not round or convert unless the user asks.

## Anti-AI Prose Gate

Remove:

- generic field openings: "In today's rapidly evolving world/field";
- vague stakes: "has important implications";
- formulaic contrasts: "not only... but also..." when unsupported;
- broad "landscape", "ecosystem", "realm", "delve", "underscore";
- rhetorical questions answered immediately;
- repeated three-item rhythms;
- excessive adverbs and decorative adjectives.

Scientific writing can remain formal. The goal is not casual prose; it is direct, specific, evidence-led prose.

## Reviewer-Risk Self-Review

Before finalizing, check:

1. Novelty: does the text clearly state what is new and why it is non-obvious?
2. Mechanism: is the proposed mechanism supported by characterization or controls?
3. Evaluation: are durability, corrosion, wetting, thermal, or mechanical claims backed by suitable tests?
4. Scope: does the language match the tested materials and environments?
5. Reproducibility: are sample names, preparation steps, and test conditions specific enough?
6. Tone: does the section sound confident without claiming more than the data show?
