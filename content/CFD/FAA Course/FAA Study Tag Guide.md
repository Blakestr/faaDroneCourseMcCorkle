---
publish: true
title: FAA Study Tag Guide
description: A practical guide to the tags used throughout the FAA drone pilot study notes.
created: 2026-11-17T02:43:04.437Z
modified: 2026-11-17T02:43:04.437Z
---

# FAA Study Tag Guide

These notes use a small set of consistent tags to make **exam preparation, review, and real-world drone operations** easier to navigate. Every study tag starts with `FAA/` so it stays grouped with the aviation material in Obsidian and Quartz.

**Tags describe why a section matters—not simply what subject it covers.** Headings organize the chapters; tags help identify useful material _across_ chapters.

## Quick reference

| Tag | What it means |
| --- | --- |
| `#FAA/Exam` | Instructor-emphasized or specifically identified exam material |
| `#FAA/TodoReview` | A concept that needs another study pass |
| `#FAA/Trap` | An easy-to-miss distinction or a misleading exam answer |
| `#FAA/Formula` | A calculation, equation, or conversion worth practicing |
| `#FAA/Safety` | A hazard, operating limit, or important safety consideration |
| `#FAA/Practical` | Information applicable to actual drone flights |
| `#FAA/Definition` | A term whose precise meaning matters |

## Tag explanations and examples

### `#FAA/Exam` — High-priority exam material

**Use when:** An instructor explicitly says a question or slide is likely to appear on the FAA knowledge test, or a question has been specifically flagged for exam practice. This is a _priority marker_, not a claim that other material will not be tested.

**Chapter 1 example:** The instructor specifically called attention to two slides covering **center of gravity (CG) and aircraft loading** as exam material. Mark the associated explanation with `#FAA/Exam`.

**Study action:** Revisit the flagged material and check that you can explain the answer without looking at the notes.

### `#FAA/TodoReview` — Still needs attention

I'm using this (Blake) for stuff that is still near completely clear for me.  It may very well be an issue for you, but this is the personal part of the notes.

**Chapter 1 example:** If you still mix up **static stability** (initial tendency after a disturbance) and **dynamic stability** (response over time), mark that comparison with `#FAA/TodoReview` until you can distinguish them confidently.

**Study action:** Review, test yourself, then remove the tag.

### `#FAA/Trap` — Important distinctions and misleading answers

**Use when:** A question depends on careful wording, or an intuitive answer turns out to be incorrect. This is especially useful for multiple-choice exam practice.

**Chapter 1 example:** **Increasing aircraft weight raises stall speed, but does not by itself change the airfoil's critical angle of attack** for a given configuration. Current angle of attack and _critical_ angle of attack are not the same thing. Mark that distinction with `#FAA/Trap`.

**Study action:** Ask: _What tempting answer would I choose if I read this too quickly?_

### `#FAA/Formula` — Calculations and conversions

**Use when:** You need an equation, a units conversion, or a repeatable method for solving a numerical question.

**Chapter 1 example:** **Moment = Weight × Arm**, where _arm_ is the distance from the reference datum to the item's location. A moment describes the turning effect of a weight around the datum. Mark this with `#FAA/Formula`.

**Study action:** Work an example with numbers, label the units, and check what the result means.

### `#FAA/Safety` — Aircraft limitations and hazards

**Use when:** A concept affects whether a flight can be conducted safely, including loading limits, stability, stall behavior, and environmental operating limits.

**Chapter 1 example:** Loading an aircraft **outside its approved CG envelope** can undermine controllability and stability. Excessive aft CG can make stall recovery especially difficult. Mark the CG-envelope discussion with `#FAA/Safety`.

**Study action:** Connect the rule to a preflight or in-flight decision.

### `#FAA/Practical` — Apply it on an actual mission

**Use when:** The information is especially relevant to real drone operations, not just passing a written test. This includes mission preparation, launch decisions, and operational judgment.

**Chapter 1 example:** **Hot, humid weather can reduce aircraft performance**. For a fire-department drone launch on a hot Florida afternoon, consider aircraft performance, payload, and manufacturer limits before taking off. Mark that application with `#FAA/Practical`.

**Study action:** Ask: _How could this change a real launch, flight, or go/no-go decision?_

### `#FAA/Definition` — Terms to know precisely

**Use when:** The definition has a specific technical meaning that could be misunderstood or confused with another term.

**Chapter 1 example:** **Load factor** describes the aerodynamic load on an aircraft relative to its weight, commonly expressed in Gs. In a coordinated, level turn, load factor increases with bank angle. Mark its definition with `#FAA/Definition`.

**Study action:** Explain the term in one sentence, then give a concrete example.

## How to apply tags

Tags belong **next to the specific material they describe**. For example, in a chapter note:

> **Moment = Weight × Arm**\
> `#FAA/Formula`

Or:

> **Stall speed increases with load factor.**\
> `#FAA/Safety` `#FAA/Trap`

A passage can have more than one tag when the categories genuinely overlap. Avoid tagging every sentence: the tags should identify material you will want to find again.

**Important:** The tags displayed in _this guide_ are formatted as code so that the guide does not acquire all seven tags automatically. In the actual study notes, enter tags as plain text without backticks (for example, type `#FAA/Exam` directly in Obsidian).

## How these tags work with Obsidian and Quartz

- **Obsidian:** Search for a tag such as `tag:#FAA/Formula` to find notes containing it. The tag is indexed at the **note level**, even when you place it beside a particular paragraph. Use the search result to jump to the relevant occurrence.
- **Quartz tag pages:** With Quartz's tag-page feature enabled, tags used in published content get their own browsing pages. Nested names under `FAA/` keep related categories grouped together. A tag mentioned only as an example inside code does not make this guide a member of that tag.
- **Quartz graph:** With tag nodes enabled, published chapter pages sharing the same tag can connect through that tag node. A separate Markdown page such as this guide is a **page node**, not automatically a hub for all the tags it describes.
- **Page-to-page links:** Add actual internal links between related chapters or from your site's index to this guide if you want those documents connected directly in the graph. Merely mentioning a chapter's name in prose is not the same as creating a link.

### Example of a growing study graph

Once several chapters are published, a tag like `#FAA/Safety` might connect notes on **weight and balance**, **weather**, and **emergency procedures**. That makes the graph useful for seeing which topics feed into the same operational concern, even across different course chapters.

## Related course notes

- [[Chapter 1. Loading and Performance]] — introductory aerodynamics, loading, CG, and performance. This internal link also creates a direct page-to-page connection in the Quartz graph, provided the Chapter 1 note uses that filename.

## Tagging principles

1. **Tag for future usefulness**, not completeness.
2. **Keep `#FAA/Exam` selective:** prioritize instructor-identified or explicitly flagged exam questions.
3. **Treat `#FAA/TodoReview` as actionable:** remove it after the concept is mastered.
4. **Use overlaps sparingly:** two well-chosen tags are better than five generic ones.
5. **Use chapter headings for topics:** don't create a separate tag for every force of flight, axis, or aircraft component.
6. **Verify technical details:** tags help prioritize knowledge, but don't establish that a statement is correct.

---

_This guide is the legend for the FAA study-note tagging system. The tags can evolve as more chapters are added, but consistency is more useful than a huge taxonomy._
