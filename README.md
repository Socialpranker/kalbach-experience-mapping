# Mapping Experiences — Agent Skill

Agent skill generated from **[*Mapping Experiences*](https://www.oreilly.com/library/view/mapping-experiences/9781491923528/)** by James Kalbach (O'Reilly, 2015) with [book-to-skill](https://github.com/virgiliojr94/book-to-skill).

It turns Kalbach's alignment-diagram methodology — customer journey maps, service blueprints, experience maps, mental model diagrams, spatial maps — into a toolkit an agent (GitHub Copilot CLI, Amp, Claude Code, or any compatible host) can apply on demand: named frameworks, decision rules, and ready-to-fill diagram templates, not a book report.

> **Private repository.** The content below is synthesized and reorganized from a commercially published, copyrighted book — not the verbatim text. It stays private per [book-to-skill](https://github.com/virgiliojr94/book-to-skill)'s copyright policy; it is not redistributed publicly.

## Install

```bash
npx skills add https://github.com/Socialpranker/kalbach-experience-mapping --skill kalbach-experience-mapping
```

## What's inside

| File | Contents |
|---|---|
| [`SKILL.md`](SKILL.md) | Core frameworks front-loaded for reference, chapter index, topic index |
| [`chapters/ch01–ch13.md`](chapters/) | One file per chapter: core idea, named frameworks, mental models, anti-patterns, reference tables, a worked example, key takeaways |
| [`glossary.md`](glossary.md) | 74 key terms, alphabetized, each traced to its chapter |
| [`patterns.md`](patterns.md) | 28 named techniques — when to use, how, trade-offs |
| [`cheatsheet.md`](cheatsheet.md) | Single-page decision aid: which diagram type to pick, decision rules, tells & smells, the four-phase process, the seven principles of alignment |
| [`templates.md`](templates.md) | Blank, fillable structure for each of the six diagram archetypes (Alignment Diagram, Customer Journey Map, Experience Map, Service Blueprint, Mental Model Diagram, Spatial Map/Ecosystem Model), with fill-in steps and a diagram-type comparison table |

## Usage

Once installed, ask your agent things like:

- *"What does the kalbach-experience-mapping skill say about service blueprints?"*
- *"Give me a blank customer journey map template."*
- *"Which diagram type fits a cross-department service redesign?"*
- *"Walk me through the Align phase of a mapping project."*

## Source

- Book: *Mapping Experiences* — James Kalbach, O'Reilly Media, 2015, ISBN 9781491923535
- Generator: [book-to-skill](https://github.com/virgiliojr94/book-to-skill)
