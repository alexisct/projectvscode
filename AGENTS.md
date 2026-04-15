# AGENTS.md

## Project Purpose

This workspace is for a focused literature review of Nicolas Brantut's research.

The main objective is to produce a clear, decision-useful executive summary of his work, with special emphasis on:

- fault stability
- induced seismicity
- modelling approaches
- the interaction between laboratory experiments and models

## Core Working Rule

This project is synthesis-first. The goal is not to produce a long generic bibliography dump. The goal is to identify the most relevant papers, read them efficiently, and extract the mechanisms, modelling choices, and research trajectory that matter for the user's interests.

## Research Scope

Prioritize papers that address one or more of the following:

- fault friction, fault stability, rupture nucleation, or slip instability
- fluid effects, pore pressure, permeability evolution, injection-related processes, or mechanically induced changes relevant to induced seismicity
- constitutive, analytical, or numerical modelling of fault or rock deformation processes
- experimental rock mechanics or laboratory seismology that is explicitly tied to theoretical or modelling interpretation

Lower priority:

- general rock deformation papers with no clear connection to the target themes
- purely methodological papers unless they are central to Brantut's modelling or interpretation strategy
- papers where Brantut is a coauthor but the work is clearly outside this topic cluster

## Source Rules

### Discovery

- Use the GFZ profile as the starting point for author identity and publication context.
- Use the Crossref API to build the initial bibliography.
- De-duplicate records by DOI whenever possible.
- Record title, year, venue, DOI, URL, coauthors, and abstract when available.

### Reading

- Do not assume Crossref provides full text.
- Use Crossref for discovery and metadata first, then retrieve accessible full texts from publisher pages, profile links, accepted manuscripts, or preprints.
- If full text is unavailable, use the abstract and accessible metadata, but clearly mark that limitation in notes.

### Evidence Standard

- Distinguish clearly between direct statements supported by papers and higher-level synthesis or inference.
- Prefer statements that can be supported by multiple papers when making broader claims about Brantut's research program.
- Avoid overstating induced seismicity relevance if a paper is really about broader fault mechanics unless the connection is explicit or carefully framed as inference.

## Paper Triage Rules

Every paper should be tagged as one of:

- `core`: directly relevant to fault stability, induced seismicity, modelling, or lab-model coupling
- `secondary`: useful background or supporting context
- `peripheral`: outside the main review scope

Every `core` paper should also be tagged by theme:

- `fault-stability`
- `induced-seismicity`
- `modelling`
- `lab-model-iteration`
- `friction`
- `fluids`
- `rupture`
- `rock-deformation`

## Reading Workflow

Read papers in layers:

1. Scan titles, abstracts, and conclusions for the full relevant set.
2. Read methods, figures, results, and discussion for `core` papers.
3. Deep read the subset that most clearly links experiments and models.

Do not spend equal time on every paper. Depth should track relevance.

## Extraction Template

For each `core` paper, capture:

- full citation
- year
- DOI or stable URL
- paper type: experiment, model, theory, review, or mixed
- research question
- geological or laboratory setting
- experimental design
- modelling framework or theoretical approach
- main findings
- implications for fault stability
- implications for induced seismicity
- how the experiments and models connect
- important assumptions
- limitations and open questions
- relevance score: high, medium, or low

## Synthesis Rules

The final synthesis should answer these questions:

1. What are the main mechanisms Brantut identifies for changes in fault stability?
2. What parts of his work are most relevant to induced seismicity, directly or indirectly?
3. What modelling approaches does he use repeatedly, and what are they used to explain?
4. How does he iterate between laboratory evidence and modelling?
5. How has his research emphasis changed over time?

The review should also identify:

- recurring physical variables or controls
- where his evidence is strongest
- where interpretation depends on modelling assumptions
- unresolved debates or open questions

## Writing Style Rules

- Write for an informed reader who wants a fast executive understanding, not a specialist-only technical memo.
- Lead with high-level conclusions, then support them with selected evidence.
- Prefer short, direct prose over exhaustive description.
- Avoid jargon when a simpler phrase will do; if jargon is needed, explain it briefly.
- Keep the distinction clear between:
  - what individual papers show
  - what the body of work suggests overall

## Deliverable Structure

The final output should contain:

### 1. Executive Summary

- short and synthesis-first
- focused on the user's stated interests

### 2. Thematic Findings

- fault stability
- induced seismicity
- modelling approaches
- lab-model iteration

### 3. Research Trajectory

- early work
- mid-period development
- recent direction

### 4. Reference Table

Include for each `core` paper:

- citation
- year
- theme
- approach
- one-sentence contribution
- relevance to the user's interests

### 5. Limits and Open Questions

- evidence gaps
- access limitations
- unresolved scientific issues

## Output Quality Bar

The final review is successful only if it:

- identifies the papers most relevant to the target themes
- explains Brantut's main scientific contributions in plain language
- shows how the lab and modelling work interact
- makes induced seismicity relevance explicit without over-claiming
- provides a concise but credible executive summary backed by source-level reading

## File Conventions

- Keep planning material in markdown files in the workspace root unless a clearer structure is created later.
- If notes are created for individual papers, use consistent filenames.
- Prefer human-readable tables and checklists over dense raw exports.

## Current Project Files

- `brantut_research_plan.md`: task checklist and initial research plan

