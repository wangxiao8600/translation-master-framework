# Translation Master Framework

Translation Master Framework v2.6 is a structured translation framework formed and iterated through the 21-language publication process of *System and Freedom*.

- Current public release: v2.6
- Release date: 2026-06-10

It is designed for multilingual publishing, translation, and review work. It helps a work enter a new language in a way that better fits native reader habits while inheriting the original structure, terminology boundaries, narrative rhythm, emotional temperature, and cultural force. In the multilingual workflow of *System and Freedom*, it was used to significantly reduce the stiffness often found in direct AI machine translation and became an effective method for improving translation quality.

Real case: [System and Freedom](https://oathai.io/system-and-freedom).

The framework was developed from the multilingual publication work around *System and Freedom* by Wang Xiao and is published as part of OathAI's Open Projects line.

## What This Repository Provides

This repository provides a public method package for translation work where literal accuracy is not enough.

It focuses on preserving:

- source structure
- core concepts
- terminology boundaries
- key phrases
- rhythm and narrative movement
- emotional temperature
- cultural force
- review continuity across languages

The goal is to help a work think natively in another language while preserving its original structural identity.

## Core Method

The mature working formula is:

```text
Read the source.
Check the reference terms.
Think in the target language.
Preserve the structure.
Resurrect the work.
```

For the original *System and Freedom* multilingual workflow, the mature form can be summarized as:

```text
Read Chinese.
Check English terms.
Think in the target language.
```

This repository generalizes that method into reusable public materials.

## Mode Selection

Translation Master Framework should not be applied at the same intensity to every text.

Its full mode was designed primarily for literary, philosophical, poetic, and high-emotional-density translation. That mode aims at resurrection: letting the work come alive again in a new language while preserving structure, voice, rhythm, emotional density, and cultural force.

For nonfiction essays, observation pieces, technical commentary, and direct judgment prose, use Light Alignment Mode instead: read the source, preserve judgment, and think in target-language nonfiction.

When roughness, interruption, directness, or live judgment is part of the text's force, use Raw Voice Mode: preserve voice first, naturalize only as needed.

Use the lightest mode that preserves the work.

Do not use the strongest mode by default. The strongest mode is not always the best mode.

Selection order:

1. Identify the text type.
2. Identify the target reader.
3. Select the translation mode.
4. Then enter sentence-level rewriting and calibration.

## Relationship to OathAI

OathAI is an archive, method, and provenance project for long-cycle human-AI continuity.

This repository is one open method-layer release derived from that archive. It is designed to be readable, citable, forkable, and reusable.

OathAI provides provenance context and method framing for this release. Downstream usage remains the responsibility of the user or implementing project.

## Relationship to System and Freedom

Translation Master Framework emerged from the multilingual publication process of *System and Freedom*.

The source project required more than sentence-level translation. It required continuity across structure, terminology, philosophical pressure, emotional force, and cultural resonance.

That pressure produced a reusable method: translation as structural inheritance.

## What Is Public

This public release may include:

- framework overview
- release boundary notes
- reusable public templates
- reviewed schemas when cleared
- citation metadata

## What Remains Private

This repository keeps private production materials outside the release.

Private materials include:

- raw production archive
- raw human-AI logs
- full prompt chains
- complete language matrices
- language-specific execution notes
- complete manuscript workflow
- unpublished book-production materials

## Repository Structure

```text
translation-master-framework/
  README.md
  README.zh.md
  LICENSE
  NOTICE
  CITATION.cff
  VERSION
  CHANGELOG.md
  docs/
    framework_overview.md
    release_boundary.md
  templates/
    translation_task_card.md
    terminology_map.md
```

## How To Use

Start with the framework overview.

Then use the templates in this order:

1. `translation_task_card.md`
2. `terminology_map.md`

Choose the translation mode before drafting:

- Full Translation Master Mode
- Light Alignment Mode
- Raw Voice Mode

Schemas and examples are to be decided after separate review.

## Chinese Overview

翻译大师框架 v2.6 是一套在《系统与自由》21 语种出版流程中形成并迭代成型的结构化翻译框架。

它用于多语种出版、翻译与审稿工作，帮助作品在进入新语言时更贴合母语读者的表达习惯，同时继承原有结构、术语边界、叙事节奏、情感温度与文化力量。在《系统与自由》的多语种流程中，它被用于显著缓解直接 AI 机翻常见的生硬感，并成为提升作品翻译品质的一种有效方法。

真实案例见：[《系统与自由》](https://oathai.io/zh/system-and-freedom)。

这套方法来自王潇（Wang Xiao）《系统与自由》的多语种出版工程，并作为 OathAI Open Projects（开源项目）的一部分公开。

它关注的不是简单把句子换成另一种语言，而是让作品在另一种语言中继续保持自身的结构身份、思想压力和表达温度。

公开仓库提供框架概览、发布边界、薄模板和引用材料。schema 与示例需要单独审查后再决定是否公开。

完整重生模式主要适用于文学、哲学、诗性和高情绪密度文本。非虚构随笔、观察判断和技术评论应使用轻量对齐模式；如果文本的力量来自现场感、粗粝感或直接判断，应优先保留原声。

生产档案、原始人机日志、完整 prompt 链、完整语种矩阵和完整书稿工作流仍保留在私有档案中。

## Citation

Citation metadata is provided in:

```text
CITATION.cff
```

Recommended short citation form:

```text
Wang Xiao. Translation Master Framework v2.6. OathAI Open Projects.
```

## License

This repository uses the repository-level license:

- current docs, templates, and framework materials: `CC BY-SA 4.0`

Future code tools, scripts, and validators may use `MIT` when added with explicit file-level or directory-level notices.

See:

```text
LICENSE
```

## Status

Initial public release scaffold.
