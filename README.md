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
- unapproved raw internal drafts;
- private chat exports;
- unverified metrics;
- confidential or unsafe internal conflict details;
- claims that are stronger than the source evidence.


## How agents should use it

Agents should use this repository as a public context package.

Good agent behavior:

- read README.md and AGENTS.md first;
- use this file to understand the repository's purpose;
- preserve factual wording from existing files;
- preserve the candidate's authored voice when it is already present in approved source material;
- generate derivative materials only from available facts;
- keep public wording neutral, concise, and evidence-based;
- clearly mark limitations and non-goals;
- avoid upgrading pet projects into production experience.

Bad agent behavior:

- inventing missing dates, metrics, roles, or outcomes;
- turning internal notes into marketing copy;
- flattening intentionally vivid candidate wording into generic corporate or AI-neutral prose without a reason;
- adding confidential details;
- overwriting public-safe wording with raw private text;
- treating this repository as a complete biography;
- treating public resume files as the full source of truth.

## Current content model

The repository is expected to contain a small number of Markdown files rather than a large documentation tree.

Current public content:

- `README.md` — repository purpose, content model, and publication principles.
- `AGENTS.md` — mandatory rules for AI agents working with the repository.
- `ai-readable-professional-profile.md` — AI-readable professional profile generated from the approved source cases table. This is the main public fact base for derivative materials.
- `target-roles.md` — target role map for screening, matching, positioning, and resume generation.
- `resumes/technical-program-manager-hh.md` — role-specific hh.ru-style resume for Technical Program Manager / Руководитель технических программ.
- `resumes/internal-developer-platform-lead-hh.md` — role-specific hh.ru-style resume for Internal Developer Platform Lead / Руководитель внутренней платформы разработки.
- `resumes/ai-infrastructure-program-manager-hh.md` — role-specific hh.ru-style resume for AI Infrastructure Program Manager / AI Platform Program Manager.

The core workflow is:

1. Private source materials are updated outside this repository.
2. `ai-readable-professional-profile.md` is refreshed from the approved source table while preserving the established Markdown structure.
3. Role-specific materials are generated from the AI-readable profile and `target-roles.md`.
4. Public safety rules from `AGENTS.md` are applied before publishing.

Typical structure:

```text
README.md
AGENTS.md
ai-readable-professional-profile.md
target-roles.md
resumes/
  technical-program-manager-hh.md
  internal-developer-platform-lead-hh.md
  ai-infrastructure-program-manager-hh.md
```

The structure can grow, but it should stay simple. New files should be created only when they solve a clear publication, screening, or automation need.
