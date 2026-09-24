---
name: technical-article-writing
description: Write technically authoritative software-engineering articles for experienced developers. Use a concrete problem or running example to introduce concepts, explain why techniques matter, and favor precise technical claims over feature lists or marketing language.
---

# Technical Article Writing

## Purpose

Write technically authoritative articles for experienced software developers. The article should teach through a concrete problem and progressively reveal the concepts needed to solve it. Explain why a technique matters, not merely what it does.

## Narrative

- Prefer one concrete running example over a catalogue of unrelated examples.
- Introduce the problem before introducing the feature that solves it.
- Let examples evolve rather than repeatedly replacing them with unrelated snippets.
- Give every code example a purpose in the argument.
- Prefer explaining a small number of ideas deeply over mentioning many features superficially.
- Return to the original problem near the end and show what changed.

## Technical style

- Be precise about what the language, compiler, runtime, libraries, and tools actually guarantee.
- Distinguish compile-time checking, runtime checking, static compilation, dynamic dispatch, and documentation.
- Prefer concrete consequences over adjectives such as "powerful", "elegant", or "revolutionary".
- When comparing technologies, compare mechanisms and resulting code rather than declaring one technology superior.
- Do not turn release notes into prose without adding a narrative or explaining significance.
- Do not make claims about performance, productivity, AI capability, or token savings without evidence.

## Tone

- Professional and conversational.
- Confident but not promotional.
- Assume the reader is technically capable.
- Explain unfamiliar concepts when they become relevant.
- Avoid defensive arguments about why a technology is still relevant.
- Avoid marketing copy and generic introductions.
- Avoid padding and repetition.

## Structure

A useful default structure is:

1. Start with a concrete problem or running example.
2. Establish only the context needed to understand it.
3. Introduce language or library features when they solve a problem in the example.
4. Explain the underlying concept after the reader has seen why it is useful.
5. Deepen the discussion with implementation, trade-offs, or comparisons where relevant.
6. End by returning to the original problem.

## Code examples

- Keep examples small enough to read in context.
- Prefer code that demonstrates a specific semantic or architectural point.
- Do not show code merely to enumerate syntax.
- Preserve continuity between examples where practical.
- Do not hide important mechanics in pseudocode when the exact behavior matters.

## AI-related discussion

- Treat AI coding agents as software-engineering consumers of program semantics, not as the primary audience unless the article explicitly concerns AI.
- Distinguish source-code summarisation from machine-checkable specifications.
- Prefer concrete examples showing what information an agent can avoid reconstructing.
- Make clear when an observed result comes from a specific example rather than a general benchmark.
- Do not imply that an AI-generated explanation has the same status as a specification that is part of and checked against the program.

## Avoid

- "In today's rapidly evolving world..."
- "X is more relevant than ever..."
- feature-by-feature release-note lists
- exaggerated claims
- generic AI enthusiasm
- artificial rhetorical questions
- unexplained acronym accumulation
- repeating the same point in different words
- section padding whose only purpose is transition
- turning every section into a formulaic "What is X? / Why X matters / Example" sequence
