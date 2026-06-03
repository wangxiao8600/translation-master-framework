# Release Boundary

Translation Master Framework v2.6 is published as a public method-layer release.

The public repository is intended to establish a citable source, provide a thin reusable method surface, and make the framework understandable without exposing the private production archive behind it.

---

## Core Rule

```text
Publish the judgment framework.
Do not publish the production capability.
```

This means:

- materials that help readers understand, cite, and reuse the method may be public
- materials that help reconstruct the real production system remain private

---

## Disclosure Layers

The framework uses three disclosure layers:

```text
Public for citation.
Invite-only for collaboration.
Private for production memory.
```

### Public

The public layer is for citation, canonical source attribution, basic reuse, and public boundary.

It may include:

- README
- license and notice
- citation metadata
- framework overview
- release boundary
- thin public templates
- reviewed schemas when cleared

### Invite-only

The invite-only layer is for collaboration with people who show visible contribution trace, citation discipline, and concrete collaboration intent.

It may include after separate approval:

- fuller templates
- redacted case notes
- short before / after fragments
- review checklist variants
- community feedback notes
- contributor experiments

Invite-only access is not automatic. It is based on visible contribution trace, citation discipline, and concrete collaboration intent.

### Private

The private layer is for production memory and archive continuity.

It remains private by default and includes:

- raw production archive
- raw human-AI logs
- full prompt chains
- complete language matrices
- language-specific execution details
- complete manuscript workflow
- unpublished book-production materials
- private review traces

---

## First Public Release Scope

The first public release should stay thin.

Recommended first public scope:

```text
README.md
README.zh.md
LICENSE
LICENSE-POLICY.md
NOTICE
CITATION.cff
docs/framework_overview.md
docs/release_boundary.md
templates/translation_task_card.md
templates/terminology_map.md
```

Deferred from the first public release:

```text
examples/
case_notes/
schemas/review_note.schema.yaml
any real production case
any complete before / after chain
```

Schemas may be added after separate review.

Examples and case notes require separate clearance.

---

## Mode Selection Boundary

Translation Master Framework is a mode-selection framework, not a one-size-fits-all polishing engine.

Do not use the strongest mode by default. The strongest mode is not always the best mode.

Use the lightest mode that preserves the work.

Working modes:

- Full Translation Master Mode: for literary, philosophical, poetic, and high-emotional-density translation
- Light Alignment Mode: for nonfiction essays, observation pieces, technical commentary, and direct judgment prose
- Raw Voice Mode: for voice-first translation when roughness, interruption, directness, or live judgment is part of the text's force

Selection order:

1. identify text type
2. identify target reader
3. select translation mode
4. enter sentence-level rewriting and calibration

---

## What This Repository Does Not Claim

This repository does not:

- certify downstream translation quality
- guarantee high-quality output by itself
- replace human review
- require full-mode treatment for every text type
- publish the full System and Freedom production workflow
- expose all production prompts or review evidence
- provide an OathAI endorsement of third-party implementations

Downstream use remains the responsibility of the user or implementing project.

---

## Public Review Checklist

Before adding a file to the public repository, check:

- Does it help readers understand, cite, or reuse the method?
- Does it reveal private production capability?
- Does it include raw logs, full prompt chains, or internal source paths?
- Does it expose real production terminology matrices?
- Does it include private reviewer notes or unpublished manuscript fragments?
- Does it imply certification, endorsement, or guaranteed quality?
- Does it belong in public, invite-only, or private archive?

If a file helps reconstruct the private production system, keep it out of the public repository.
