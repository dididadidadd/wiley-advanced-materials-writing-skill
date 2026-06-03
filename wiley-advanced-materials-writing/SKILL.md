---
name: wiley-advanced-materials-writing
description: Write, polish, translate, and restructure materials-science manuscripts in a Wiley Advanced Materials / Advanced Functional Materials style. Use for Advanced Materials, Advanced Functional Materials, Advanced Science, Small, Angewandte-adjacent materials papers, especially coatings, superhydrophobic/superamphiphobic surfaces, anti-corrosion, anti-icing, self-healing polymers, epoxy/siloxane systems, micro/nanostructures, mechanism narratives, abstracts, introductions, results/discussion, conclusions, graphical-abstract text, figure captions, cover letters, and reviewer-facing revisions. Trigger when the user asks for Wiley, Advanced Materials, AFM, AM, high-impact materials writing, Nature/AM-style polishing, Chinese-to-English academic translation for these journals, or journal-style manuscript editing.
---

# Wiley Advanced Materials Writing

## Purpose

Use this skill to help authors draft, polish, translate, or reorganize materials-science writing toward a Wiley Advanced Materials / Advanced Functional Materials voice. The style profile was built from representative AM/AFM materials papers and strengthened with open writing-skill patterns focused on manuscript review, claim-evidence alignment, paragraph flow, and removal of AI-like prose patterns.

The goal is not to mimic any paper sentence-by-sentence. Preserve the user's claims, data, and mechanism while shaping the prose into a high-impact materials journal rhythm.

For detailed sample-derived patterns, read `references/style-guide.md` when doing substantial writing or polishing. For review gates and language-cleanup rules, read `references/writing-quality-gates.md`.

## Default Workflow

1. Identify the section type: title, abstract, introduction, results/discussion, conclusion, figure caption, graphical abstract text, cover letter, or reviewer response.
2. Build a mini-outline before drafting or polishing. For each paragraph, assign one role such as opening, bottleneck, design strategy, evidence, mechanism, limitation, or implication.
3. Extract the scientific chain before editing:
   - problem or application pressure
   - limitation of existing approaches
   - design strategy
   - material/system architecture
   - quantified performance
   - mechanism attribution
   - practical significance
4. Rewrite around a clear high-impact arc:
   - "field-level need -> unresolved bottleneck -> this work's design -> evidence -> mechanism -> broader value"
5. Run a claim-evidence map for the revised text. Each major claim must be supported, weakened, or marked with `[need evidence]`.
6. Run a language-quality pass: remove clutter, resurrect smothered verbs, check terminology consistency, and vary sentence rhythm.
7. Run an AM/AFM voice pass: quantify performance, connect structure to function, and remove unsupported hype.
8. Keep the user's data and technical meaning intact. Never invent performance values, mechanisms, durability tests, citations, or journal claims.
9. If the user provides Chinese text, translate for scientific argument first, then polish the English. Do not translate literally when Chinese word order weakens the logic.

## Section Patterns

### Title

Use a noun-phrase title that pairs the material/strategy with the function:

- "[Mechanism/strategy]-Enabled [Material/System] for [Application]"
- "[Architecture]-Based [Coating/Surface] with [Key Performance]"
- "[Process]-Induced [Structure] for [Durable Function]"
- "[Component A]-[Component B] Hybrid [System] Enabling [Function]"

Keep titles specific. Name the strategy, material, and application if space allows.

### Abstract

Use one paragraph with 6-8 sentences. Choose the structure that fits the user's material:

- Challenge -> contribution -> quantified performance.
- Challenge -> insight -> material architecture -> quantified performance.
- Multiple contributions, each paired with a technical advantage.

For AM/AFM coating papers, the default 6-move arc is:

1. Application need or field-level importance.
2. Core bottleneck, usually durability, compatibility, stability, healing, scaling, or harsh-service failure.
3. "Herein/Here, ..." design statement naming the material architecture.
4. Key performance with numbers and conditions.
5. Mechanistic explanation connecting structure/composition to function.
6. General significance or practical route forward.

Use numbers early and sparingly. The abstract should feel evidence-led, not adjective-led. If the abstract claims "durable", "robust", "long-term", "self-healing", or "superamphiphobic", include the measurement or test condition that earns the word.

### Introduction

Build 4-5 compact paragraphs:

1. Field importance and practical stakes.
2. Existing strategies and why they are insufficient.
3. Design principle or inspiration that could overcome the bottleneck.
4. This work: material architecture, test logic, key performance, and mechanism.
5. Optional final contribution map if the manuscript needs explicit contribution bullets, but prefer flowing prose for AM/AFM style.

End the introduction by previewing what the system proves, not by repeating that the topic is important.

When the introduction feels weak, reason backward first:

- What exact failure case does this work solve?
- Why have existing coatings/surfaces/resins not solved it?
- What is the non-obvious design insight?
- Which result proves that insight?

### Results And Discussion

For each result unit, use this paragraph rhythm:

1. State the experiment's purpose.
2. Report the observation and key numerical result.
3. Compare to controls or relevant benchmarks.
4. Explain the mechanism using structure-property logic.
5. Close with the claim this result supports.

Tie FTIR/XPS/SEM/EDS/contact-angle/electrochemical/thermal data to one coherent material story rather than listing characterizations separately.

### Figure Captions

Make captions self-contained but concise:

- Start with the figure's purpose or schematic identity.
- Use panel-by-panel clauses for experimental evidence.
- Include conditions, sample names, and units when needed.
- End with the takeaway only if it is not obvious from the panels.

Avoid captions that merely restate panel labels.

## Voice Rules

- Prefer active, precise verbs: enables, affords, suppresses, promotes, stabilizes, confines, reinforces, delays, recovers, maintains, extends.
- Use contrast words when they carry logic: however, whereas, in contrast, despite, nevertheless.
- Use mechanism verbs for materials papers: attributed to, arises from, results from, is governed by, is associated with.
- Use "synergy" only when two components/functions are both necessary and experimentally supported.
- Use "robust", "durable", "long-term", "self-healing", "anti-corrosion", and "anti-icing" only when specific evidence follows.
- Prefer "demonstrates" for experimental evidence and "suggests/indicates" for interpretation.
- In methods-heavy sentences, passive voice is acceptable when the actor is irrelevant. In claims and interpretation, prefer active structure-property wording.
- Keep technical terms stable. Do not vary defined terms only to avoid repetition; consistency helps reviewers.

## Quality Gates

Use these gates before returning polished manuscript prose:

1. **Paragraph message gate**: one paragraph carries one message, and the first sentence reveals that message.
2. **Flow gate**: every sentence connects by cause, contrast, consequence, refinement, or evidence.
3. **Claim-evidence gate**: every major claim in Abstract/Introduction/Conclusion maps to a figure, measurement, comparison, or mechanism.
4. **Terminology gate**: sample names, abbreviations, mechanisms, and performance metrics are consistent across text, captions, and tables.
5. **Numerical gate**: values, units, signs, sample names, and conditions match the user's data.
6. **Reviewer-risk gate**: flag unclear novelty, insufficient controls, unsupported mechanism, weak durability evidence, or overbroad application claims.
7. **AI-pattern gate**: remove filler phrases, formulaic contrasts, generic "landscape/challenge/underscore" wording, and repetitive sentence rhythm.

## Common Fixes

- Replace broad openings like "With the development of society..." with a field-specific application pressure.
- Replace lists of generic advantages with one bottleneck and one consequence.
- Replace "good performance" with measured performance and test conditions.
- Replace "the reason is that..." with structure-property mechanism language.
- Replace overlong Chinese-translated sentences with two English sentences: claim first, mechanism second.
- Remove unsupported "excellent", "outstanding", "remarkable", and "significant" unless paired with data.
- Replace "It is worth noting that..." and "It should be emphasized that..." by stating the claim directly.
- Replace "provides a demonstration of" with "demonstrates"; "has an effect on" with "affects"; "conducts an analysis of" with "analyzes".
- Avoid self-posed rhetorical questions, dramatic fragments, and generic phrases like "in today's rapidly evolving field".
- Avoid a formulaic "not only... but also..." structure unless it expresses a real two-part contribution.

## SCI Formatting And Submission Pass

When the user asks for SCI format, journal style, or submission preparation:

- Check section identity: title, abstract, keywords, introduction, experimental section, results/discussion, conclusion, supporting information, acknowledgments, data availability, conflict of interest.
- For abstracts, ensure the text is standalone and includes problem, strategy, performance, mechanism, and significance.
- For figure captions, ensure panel labels, sample names, methods, conditions, and units are readable without searching the main text.
- For references/citations, do not invent citation metadata. Mark missing sources as `[need citation]`.
- For cover letters, use a concise editor-facing pitch: unmet need, core advance, strongest evidence, fit for Advanced Materials/AFM readership.

## Output Expectations

When polishing text, return:

1. A polished English version.
2. A short Chinese note explaining the main writing changes if the user is Chinese.
3. A compact claim-evidence map for substantial sections.
4. Any factual gaps that block journal-grade wording, such as missing test conditions, controls, or quantitative values.

When drafting from notes, ask only for missing scientific facts that cannot be reasonably inferred. Otherwise, draft decisively and mark uncertain placeholders with `[need value]`.
