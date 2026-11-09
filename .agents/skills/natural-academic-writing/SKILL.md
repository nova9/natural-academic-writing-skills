---
name: natural-academic-writing
description: Draft, revise, or critique academic prose while preserving meaning, evidence, and the author's voice. Use for research papers, theses, reports, literature reviews, abstracts, and academic paragraphs, including requests to make writing less formulaic, generic, inflated, or AI-like.
---

# Natural academic writing

## Objective

Produce clear, precise, discipline-appropriate prose that develops a specific argument. Prioritize faithful meaning, evidence, and the author's voice. Do not optimize for AI-detector scores or introduce deliberate imperfections.

## Workflow

1. **Identify the task and constraints.**
   Determine whether the user wants revision, drafting, or feedback.
   Follow any supplied word limit, audience, section type, venue requirements,
   and style guide. Infer reasonable defaults for ordinary edits; ask only
   when missing information would materially affect the result.

2. **Establish the intended meaning.**
   Identify the claims, supporting evidence, reasoning, and qualifications.
   Preserve technical terminology, numbers, units, mathematical notation,
   citations, and distinctions between proposed work and completed work.
   If ambiguity would materially change a claim, ask a focused question or
   flag it rather than silently choosing an interpretation.

3. **Choose the appropriate editing depth.**
   Default to the smallest useful edit. Preserve effective sentences.
   Restructure substantially when requested or when the existing organization
   prevents readers from following the argument. Do not expand the scope,
   add arguments, or change the author's position without making that explicit.

4. **Improve substance and organization.**
   Address unclear reasoning, missing connections, repetition, and unsupported
   generalizations before polishing individual sentences. Replace vague
   abstractions with actors, mechanisms, conditions, or observations supported
   by the supplied material. Flag essential gaps instead of filling them
   with invented details.

5. **Improve sentences and flow.**
   Prefer concrete wording and clear relationships between ideas. Combine,
   split, or reorder sentences when the argument benefits. Vary sentence
   length naturally; do not manufacture variation. Keep each paragraph
   focused without forcing a fixed paragraph structure.

6. **Check fidelity and evidence.**
   Compare the revision against the original or supplied notes. Check for
   changes in scope, certainty, causality, attribution, numerical meaning,
   and citation support. Do not imply that facts or references were verified
   unless their sources were actually checked.

7. **Return the requested output.**
   For revisions, provide the revised text first. Add brief notes only for
   substantive changes, ambiguities, or evidence gaps. For feedback-only
   requests, give localized examples and actionable suggestions without
   rewriting the entire passage. Respect requests for clean text only.

## Editing principles

- Preserve prose that already works. Do not replace words merely to make
  the revision look different.
- Start with the relevant problem, claim, observation, method, or context.
  Avoid broad openings that do not help establish the argument.
- Prefer direct, concrete sentences while retaining established technical
  vocabulary.
- Remove framing such as "It is important to note that" when it adds no
  meaning.
- Use transitions when they express a real relationship. Do not add them
  automatically at the start of each paragraph.
- Treat repeated structures, conventional phrases, and symmetrical contrasts
  as diagnostic clues, not automatic errors.
- Keep repetition when it maintains terminological precision or makes a
  difficult argument easier to follow. Do not introduce synonyms that
  obscure whether two terms refer to the same concept.
- Prefer evidence and explanation to unsupported claims of novelty,
  importance, transformation, or broad impact.
- Preserve differences between association and causation, possibility and
  demonstration, and absence of evidence and evidence of absence.
- Match hedging to the evidence. Do not automatically strengthen cautious
  claims or weaken well-supported findings.
- Distinguish statistical significance from practical importance. Do not
  infer either from the other.
- Use active or passive voice according to what the sentence needs to
  emphasize. Do not impose a blanket ban on either.
- Preserve the author's spelling convention, appropriate first-person usage,
  and disciplinary conventions unless instructed otherwise.
- Use supplied writing samples to match register, terminology, and degree
  of directness. Do not invent personal characteristics or experiences.
- Do not add grammatical errors, awkwardness, slang, or arbitrary sentence
  variation to make writing appear human.

## Drafting from notes or incomplete material

- Build the draft from the supplied claims, evidence, and intended argument.
- Add connective explanation only when it follows from the supplied material
  without introducing unsupported factual claims.
- Do not invent data, sources, quotations, methods, findings, or experiences.
- Use specific placeholders such as `[sample size needed]` or
  `[source needed for this claim]` when missing information is essential.
- Keep planned methods, hypotheses, expected outcomes, and observed results
  clearly distinguished.
- Ask for clarification when a missing detail determines the central argument.
  Otherwise, produce a useful draft and identify the remaining gaps.
- Do not pad sparse material with generic background or repeated claims.

## Citations and source handling

- Keep each citation attached to the claim it supports.
- When splitting or combining sentences, check that citation placement does
  not imply support for additional claims.
- Preserve citation keys and reference details unless a correction is
  supported by the source or requested by the user.
- Do not invent citations or treat a plausible reference as a verified one.
- Distinguish language editing from factual verification. If sources were
  unavailable, do not claim that they support the revised wording.
- Preserve direct quotations exactly. If paraphrasing is requested, remove
  quotation marks, retain attribution, and preserve the source's meaning.
- When a suspected factual error cannot be resolved, flag it separately
  rather than silently substituting a guess.

## Document preservation

- Preserve LaTeX commands, citation keys, labels, cross-references, equations,
  and other structural markup.
- Do not alter mathematical expressions or numerical values during a prose
  edit unless the user requests it or a confirmed correction is necessary.
- Maintain terminology and abbreviation consistency across the supplied text.
- Respect word limits and required headings. Do not remove essential caveats
  merely to shorten the passage.

## Section-specific guidance

- **Abstract:** Represent the actual problem, approach, findings, and
  contribution. Follow the venue's format. Do not invent quantitative results
  or claim more than the paper establishes.
- **Introduction:** Establish the concrete problem, relevant context, gap,
  and contribution. Avoid generic praise for the field or unsupported claims
  that no prior work exists.
- **Related work:** Organize around relevant questions, approaches, assumptions,
  findings, or limitations. Make comparisons supported by the sources.
  Paper-by-paper organization is acceptable when it serves the argument;
  avoid disconnected summaries.
- **Methods:** Prioritize reproducible detail, clear sequencing, and precise
  terminology. Preserve distinctions between what was planned and performed.
- **Results:** Report observations with units, baselines, uncertainty, and
  exceptions where supplied. Keep interpretation distinct from observation,
  following the document's section structure.
- **Discussion:** Explain what the findings support, consider plausible
  mechanisms and alternatives, and identify limitations. Mark speculation
  clearly.
- **Conclusion:** Answer the research question at the level supported by the
  findings. Avoid repeating the entire introduction or adding new evidence
  and unsupported impact claims.

## Example

### Original

"The experiment used one server. It is important to note that the findings
may not generalize to deployments with multiple servers. This highlights
the crucial importance of further evaluation."

### Revised

"The experiment used one server, so the findings may not generalize to
deployments with multiple servers. Further evaluation is needed to assess
whether the findings hold in those deployments."

### Rationale

Remove empty framing, connect the experimental limitation to the qualification,
and make the purpose of further evaluation explicit. Preserve the original
claim and its uncertainty without adding findings.

## Final self-check

- Does each paragraph contribute a clear point to the argument?
- Have effective sentences been preserved where possible?
- Has any claim changed in meaning, scope, certainty, or causal strength?
- Are factual additions supported by supplied or checked sources?
- Do citations still support exactly the claims associated with them?
- Are proposed work and observed results clearly distinguished?
- Are terminology, numbers, units, notation, and markup intact?
- Have essential gaps been flagged rather than concealed by fluent prose?
- Does the output follow the requested format, length, and editing depth?