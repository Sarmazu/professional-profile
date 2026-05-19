# Professional Profile Repository Context

This repository is a public, curated professional profile workspace.

It exists to publish approved career materials in a format that is readable by both people and AI agents. It is a public output layer generated or manually curated from private source materials.

## Why this repository exists

The repository solves a practical career-operations problem: one professional profile can be reused across many contexts only if the underlying experience is structured, versioned, safe to publish, and easy for AI tools to read.

The repository should help with:

- preparing role-specific resume versions;
- giving AI agents structured context for screening and matching;
- maintaining a public case portfolio without exposing private source files;
- keeping a version history of public career materials;
- separating internal drafts from external/public wording.

## Intended audience

The repository may be read by:

- the owner of the profile;
- recruiting and career-support agents;
- AI tools that analyze role fit;
- technical recruiters and hiring managers;
- future automation that publishes approved materials from private sources.

Human readers should understand the candidate profile quickly. AI agents should be able to extract target roles, competencies, cases, evidence, limitations, and resume-ready text without guessing.

## Source of truth model

Private source materials live outside this repository. They may include structured tables, notes, case descriptions, chat exports, and drafts.

This repository contains only public-safe outputs derived from those sources.

Agents must treat repository content as approved public material, not as complete raw truth. If a fact is missing here, agents must not invent it. If a private source is available in a separate workflow, it should be used only when explicitly requested.

## What belongs here

Appropriate content:

- public resume versions;
- AI-readable professional profile files;
- role-specific positioning files;
- public case portfolio files;
- target-role notes;
- do-not-claim / limitation notes;
- generated Markdown exports from approved sources;
- repository governance and agent instructions.

## What does not belong here

Do not publish:

- personal contact details unless explicitly approved;
- secrets, tokens, IP addresses, configs, infrastructure details;
- internal employer system names;
- raw internal drafts;
- private chat exports;
- unverified metrics;
- emotionally loaded or internal conflict wording;
- claims that are stronger than the source evidence.


## How agents should use it

Agents should use this repository as a public context package.

Good agent behavior:

- read README.md and AGENTS.md first;
- use this file to understand the repository's purpose;
- preserve factual wording from existing files;
- generate derivative materials only from available facts;
- keep public wording neutral, concise, and evidence-based;
- clearly mark limitations and non-goals;
- avoid upgrading pet projects into production experience.

Bad agent behavior:

- inventing missing dates, metrics, roles, or outcomes;
- turning internal notes into marketing copy;
- adding confidential details;
- overwriting public-safe wording with raw private text;
- treating this repository as a complete biography;
- treating public resume files as the full source of truth.

## Current content model

The repository is expected to contain a small number of Markdown files rather than a large documentation tree.

Typical structure:

```text
README.md
ai-readable-professional-profile.md
resumes/
  technical-program-manager-hh.md
```

The structure can grow, but it should stay simple. New files should be created only when they solve a clear publication, screening, or automation need.
