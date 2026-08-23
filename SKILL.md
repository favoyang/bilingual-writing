---
name: bilingual-writing
description: Create, translate, edit, restructure, or audit writing explicitly requested in both English and Chinese, or explicitly translate English content into Chinese or Chinese content into English. Covers bilingual, bi-language, dual-language, English/Chinese, Chinese and English, EN/ZH, ZH/EN, 中英双语, 英中双语, 中英文, and 双语版本 requests. Do not use for monolingual writing merely mentioning China, Chinese terms, or English product names.
---

# Bilingual Writing

Create natural, equivalent English/Chinese content for documentation, reports, research, guides, articles, messages, plans, proposals, notes, UI copy, Markdown, HTML, and ordinary prose. Preserve the user's meaning, tone, audience, format, and technical depth.

## Set the language and layout

- Default to English and Simplified Chinese. Honor requested variants such as Traditional Chinese.
- Follow explicit instructions for language order, side-by-side columns, separate files, translation only, or an authoritative language with a summary.
- Otherwise, interleave semantic pairs: English heading then Chinese heading, English paragraph then Chinese paragraph, and each English list item, note, warning, caption, or compact thought immediately followed by its Chinese counterpart. Never default to two whole-language blocks.
- In tables, use paired columns/cells or adjacent text, whichever is clearer. For UI copy, pair corresponding labels and supporting text without changing keys.

## Write for equivalence

- Write idiomatically in each language; do not translate word for word.
- Keep every claim, decision, caveat, example, date, number, quantity, unit, commitment, warning, and uncertainty semantically aligned. Do not add a substantive point to only one language.
- Keep terminology consistent. When retaining an original term aids clarity, use a natural form such as `adjustment factor（复权因子）` or `复权因子（adjustment factor）` according to context and preference.
- Preserve code, commands, schemas, identifiers, keys, paths, URLs, filenames, established product names, and proper nouns. Translate the explanatory prose around them.
- Preserve links and citations and associate them with the corresponding claim in each language.

## Respect the artifact

- Preserve Markdown hierarchy, lists, tables, links, frontmatter, callouts, and code fences. Share a code block rather than duplicating it when that is clearer.
- In HTML, preserve existing structure and styling unless redesign is requested. Apply suitable language metadata such as `lang="en"` and `lang="zh-CN"`, and make relevant navigation, captions, accessibility labels, summaries, and metadata bilingual.
- For email, messages, and short prose, match the requested tone and keep greetings, calls to action, deadlines, and commitments aligned without imposing document-style structure.
- When editing existing bilingual content, find missing, reordered, outdated, mismatched, or contradictory counterparts. Treat neither language as authoritative unless the user says so; ask only when a material contradiction cannot be resolved from context.

## Check before delivery

- Confirm every translatable semantic unit has its intended counterpart and no English or Chinese claim is orphaned.
- Recheck names, terminology, numbers, dates, units, links, citations, code, commands, identifiers, caveats, and warnings.
- Confirm the requested language variant, order, and layout; validate Markdown or HTML syntax when relevant and visually inspect designed artifacts when supported.
- State any unresolved mismatch. Do not claim complete parity unless it was checked.
