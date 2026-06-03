# License Policy

Copyright (c) Wang Xiao.

Status: repository licensing policy note

This document clarifies the layered licensing policy for Translation Master Framework.

It does not replace the repository-level `LICENSE`.

This policy note is not legal advice.

## 1. Current Repository Materials

Unless otherwise stated, current repository materials are licensed under:

```text
Creative Commons Attribution-ShareAlike 4.0 International
CC BY-SA 4.0
```

See:

```text
LICENSE
https://creativecommons.org/licenses/by-sa/4.0/
```

This applies to current documentation, framework materials, release-boundary notes, and templates in this repository.

This layer is intended to keep the public method surface open while requiring attribution and share-alike continuity for public derivatives.

Attribution should identify:

```text
Translation Master Framework / Wang Xiao / OathAI Open Projects
```

and link to this repository where feasible.

## 2. Future Code / Scripts / Validators

Code, scripts, validators, build tools, and automation utilities may be released under:

```text
MIT License
```

when they are added with an explicit file-level or directory-level license note.

This repository does not currently include code tools in the first public release.

## 3. Examples And Case Notes

Future `examples/`, `case_notes/`, or real before / after materials require a separate file-level or directory-level license decision when added.

They are not included in the first public release.

## 4. Private And Invite-Only Materials

Private archive materials and invite-only collaboration materials are not covered by this public repository license unless they are separately released into this repository.

This includes:

- raw production archive
- raw human-AI logs
- full prompt chains
- complete language matrices
- complete manuscript workflow
- invite-only collaboration notes

## 5. File-Level Notes Override Defaults

If a file, directory, or submodule includes an explicit license notice, that notice controls that file, directory, or submodule.

If a future code file is marked under MIT, that file-level or directory-level note controls the code file.

If no specific notice is present and the file is not covered by a future code-layer rule, the repository default in section 1 applies.

## 6. Current Practical Rule

For current repository use:

- current docs, templates, and framework materials: `CC BY-SA 4.0`
- future code tools, scripts, and validators: `MIT`
- examples and case notes: separately cleared before release

Short form:

```text
Public method materials are open under share-alike.
Future code tools should follow open-source software practice when added.
Production archives remain private unless separately released.
```
