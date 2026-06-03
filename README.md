# Wiley Advanced Materials Writing Skill

A Codex / Agent Skills package for polishing materials-science manuscripts toward an Advanced Materials / Advanced Functional Materials style.

This skill is designed for authors working on coatings, superhydrophobic or superamphiphobic surfaces, anti-corrosion systems, anti-icing materials, self-healing polymers, epoxy/siloxane systems, micro/nanostructures, mechanism narratives, figure captions, cover letters, and reviewer-facing revisions.

It is not affiliated with Wiley, Advanced Materials, Advanced Functional Materials, or any journal publisher. It does not copy journal text. It provides reusable writing workflows, section patterns, quality gates, and reviewer-style checks.

## What It Helps With

- Abstracts with a clear problem -> strategy -> quantified performance -> mechanism arc
- Introductions that move from field pressure to unresolved bottleneck to design insight
- Results and discussion sections that connect characterization to structure-property mechanisms
- Figure captions with panel-level clarity, sample names, units, and test conditions
- Chinese-to-English academic translation for high-impact materials manuscripts
- Claim-evidence maps for reducing overclaiming before submission
- De-AI and clarity passes while preserving a formal scientific register

## Install

Copy the skill folder into your Codex skills directory:

```powershell
Copy-Item -Recurse .\wiley-advanced-materials-writing "$env:USERPROFILE\.codex\skills\"
```

Then restart Codex so it rescans local skills.

For other Agent Skills-compatible tools, copy the `wiley-advanced-materials-writing` folder into that tool's skills directory.

## Usage

Example prompts:

```text
Use $wiley-advanced-materials-writing to polish this abstract for an Advanced Functional Materials submission.
```

```text
Use $wiley-advanced-materials-writing to rewrite this introduction and return a claim-evidence map.
```

```text
Use $wiley-advanced-materials-writing to translate this Chinese figure caption into AM/AFM-style English.
```

## Included Files

```text
wiley-advanced-materials-writing/
  SKILL.md
  agents/openai.yaml
  references/style-guide.md
  references/writing-quality-gates.md
```

## Guardrails

- Do not invent performance values, mechanisms, durability tests, citations, or journal claims.
- Mark unsupported claims with `[need evidence]`.
- Use "synergy", "durable", "long-term", "self-healing", and "robust" only when the manuscript provides evidence.
- Treat this as writing support, not journal acceptance advice.

## License

MIT License. See `LICENSE`.
