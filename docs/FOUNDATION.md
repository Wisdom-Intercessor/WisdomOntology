# WisdomOntology — Foundational Charter

**Document ID:** WI-FO-001  
**Version:** 0.1.0-proposal  
**Status:** Draft for review  
**Owner:** WisdomCore / Wisdom Intercessor Architecture  
**Repository:** WisdomOntology

## 1. Purpose

The foundational model of what exists and how entities, realms, relations, processes, and states are understood within Wisdom Intercessor. This charter defines the domain, scope, boundaries, principles, responsibilities, and initial vocabulary. It establishes a reviewable foundation, not a claim of completed implementation or universally settled philosophy.

## 2. Architectural position

This root is one of five mutually informing foundations: WisdomOntology, WisdomEpistemology, WisdomAxiology, WisdomTeleology, and WisdomPraxeology. WisdomCore coordinates their shared architecture and standards. The roots inform all eight operational branches and the three realms Wis, Dom, and Land; they do not replace operational ownership.

## 3. Scope

- وجود و موجود
- انسان و عامل
- جهان و محیط
- قلمروهای Wis · Dom · Land
- موجودیت، رابطه، ویژگی، رخداد، فرایند، حالت
- مرز مدل و واقعیت

## 4. Explicit exclusions and interfaces

- روش اثبات ادعاها (WisdomEpistemology)
- داوری ارزش‌ها و اخلاق (WisdomAxiology)
- تصمیم و اجرای عملیاتی (WisdomPraxeology)

Cross-root interfaces must be explicit and bounded: Ontology supplies canonical concepts and relations; Epistemology evaluates claims and evidence; Axiology supplies normative values and criteria; Teleology supplies purpose, ultimate ends and direction; Praxeology organizes context-specific goals, deliberation, authorization and action. None may unilaterally redefine another root's scope.

## 5. Foundational principles

1. مدل هستی‌شناختی نباید با واقعیت نهایی یکی انگاشته شود؛ هر مدل محدودیت و دامنه دارد.
2. موجودیت‌ها، روابط و طبقه‌بندی‌ها باید تعریف، شناسه و نسخه داشته باشند.
3. مدل چندقلمرویی باید مرز میان انسان، فضای دیجیتال و جهان بیرونی را حفظ کند.
4. داده‌های حساس و ویژگی‌های شخصی فقط با ضرورت، مبنای مشروع و کنترل دسترسی مدل شوند.
5. از ادعاهای متافیزیکی غیرقابل‌آزمون به‌عنوان واقعیت مهندسی قطعی استفاده نشود.

## 6. Responsibility

- **WisdomCore:** system-level coordination, architecture compatibility, registry, document control.
- **Root maintainers:** domain definitions, proposals, reviews, traceability, and compatibility notes.
- **Operational repositories:** adopt root concepts only through documented interfaces and use-case fit; record deviations.
- **Human reviewers:** assess normative, ethical, legal, and high-impact decisions; no root document grants automated authority.

## 7. Change control

Definitions, taxonomies, principles, and normative requirements are versioned. Breaking changes require an ADR, impact assessment across other roots and eight branches, migration guidance, and explicit review. Maintain superseded material and decision history; do not delete accepted history.

## 8. Acceptance of this baseline

This v0.1.0 proposal is accepted only through PR review and merge. Acceptance does not imply that all systems implementing it are complete, validated, or production-ready.
