# License Policy

Copyright (c) Wang Xiao.

Status: repository licensing policy note

This document clarifies the layered licensing policy for Translation Master Framework.

It does not replace the repository-level `LICENSE`.

This policy note is not legal advice.

## 1. Repository Default

Unless otherwise stated, framework explanation, narrative method notes, release-boundary notes, and other explanatory documents in this repository remain licensed under:

```text
Creative Commons Attribution-NonCommercial-ShareAlike 4.0 International
CC BY-NC-SA 4.0
```

See:

```text
LICENSE
https://creativecommons.org/licenses/by-nc-sa/4.0/
```

This layer is intended for method-document protection.

## 2. Protocol / Template / Schema Materials

Reusable protocol-layer materials are licensed under:

```text
Creative Commons Attribution 4.0 International
CC BY 4.0
```

This includes:

- translation task cards
- terminology map templates
- schema-like materials
- reusable review forms
- public method templates
- public declaration or provenance patterns if added later

For the current repository state, this applies to:

```text
templates/**
```

Future `schemas/` or `protocol/` directories should be treated as protocol-layer materials when added, unless a more specific license notice says otherwise.

Future `examples/` require a separate file-level or directory-level license decision when added, because examples may contain public text samples, synthetic text, case notes, or other materials that do not automatically belong to the reusable protocol layer.

This layer is intended to make the reusable method surface easier to adopt, cite, extend, and implement.

Attribution should identify:

```text
Translation Master Framework / Wang Xiao / OathAI Open Projects
```

and link to this repository where feasible.

## 3. Code / Scripts / Validators

Code, scripts, validators, build tools, and automation utilities may be released under:

```text
MIT License
```

when they are added with an explicit file-level or directory-level license note.

This repository does not currently include code tools in the first public release.

## 4. File-Level Notes Override Defaults

If a file, directory, or submodule includes an explicit license notice, that notice controls that file, directory, or submodule.

If a file is covered by section 2, the protocol-layer `CC BY 4.0` policy applies unless a more specific notice says otherwise.

If a future code file is marked under MIT, that file-level or directory-level note controls the code file.

If no specific notice is present and the file is not covered by the protocol-layer or code-layer rules, the repository default in section 1 applies.

## 5. Current Practical Rule

For current repository use:

- method explanation and release-boundary documents: `CC BY-NC-SA 4.0`
- reusable templates and future schemas: `CC BY 4.0`
- future code tools, scripts, and validators: `MIT`

Short form:

```text
Method documents are protected.
Reusable templates are meant to spread.
Code tools should follow open-source practice when added.
```
