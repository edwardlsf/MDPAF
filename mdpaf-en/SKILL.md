---
name: mdpaf-en
description: MDPAF (Multi-dimensional Project Assessment Framework) B6 — a complete methodology for deciding whether a product / project / feature / idea is worth doing. Use this skill when the user asks to evaluate or assess a project, product, idea, or feature (e.g., "analyze this project", "is it worth doing", "should we continue with this", "competitor analysis", "pain point analysis", "multi-dimensional analysis"), or mentions MDPAF / 多维分析法 in an English conversation. This is the English edition; use the mdpaf skill for Chinese conversations.
agent_created: true
---

# MDPAF B6 (English Edition)

## Overview

This skill carries the complete B6 thought of MDPAF — the Multi-dimensional Project Assessment Framework created by esf — for executing a full, hallucination-resistant assessment of any object whose question is "should this be done, is it being done right, should it continue." The core model is the **Behavior Chain**: place the idea back into the long chain of the user's world, and mount value judgments onto their proper scopes.

**Before executing this skill, read `references/mdpaf-methodology.md` in full** (the B6 authoritative English text, ~6,000 words). The methodology is not repeated here — this file carries only workflow and discipline.

**Subordination**: this edition is a translation of the Chinese B6 snapshot in this repository (`mdpaf/`); where the two differ, the Chinese text prevails.

## Workflow

### Step 1: Stand by and inventory

1. Confirm the object of analysis. If the user has not yet provided project material: stand by — do not analyze early, and do not guess project content from its name or description.
2. Once material arrives, inventory first: what exists (project description, user data, competitor information, payment evidence), what is missing. **Flag gaps honestly as "to be supplemented" and ask the user direct factual questions** (who pays, how much has been paid, how often the pain hits, how they cope now) — ask about events, not opinions.
3. Label the source of every key fact: user-provided / public search / inference / to be supplemented.

### Step 2: Execute the full B6 process (no step skipped)

Execute in the order defined by `references/mdpaf-methodology.md`; no shortcuts, no layer-skipping:

1. **Coarse Gate**: has anyone paid a price for the claimed pain? Not real → terminate on the spot and report honestly that it died at the Coarse Gate.
2. **Map**: place the object into the user's complete long chain; draw before, after, and sideways (draw only, no judging); stop at the nearest user-task closed loop.
3. **Re-slice**: settle which blocks are actually covered under the long chain; run the **Side-by-Side Reveal** (claimed coverage vs actual coverage — if they differ, the analysis turns to the new blocks); record the **Coverage Correction**.
4. **Fine Gate**: run the full Seven Pain Questions over the covered blocks (real / scale / solution / will / degree / coping) + the Timing Question "Why now?". Coarse-Gate evidence belonging to old blocks is not inherited automatically.
5. **Measure**: mount judgments per scope — the long chain gets ceiling magnitude and drift signals; the block group gets entry value, broken links, the Payment Triangle; core blocks get Incumbents (with the Folk Workaround, the user's will, Weight of Concession, Bonus Hard Constraint), satisfaction and switching cost, Payment Trigger, the Opportunity Formula (block-level), and shelf life.
6. **Refine**: close into evidenced conclusions + ranked, priced actions; **conclusions may not introduce new evidence**; "the best refinement is not refining" is a permitted answer.
7. **Extend**: four-direction growth candidates (upstream / downstream / parallel / morph), each passing the three gates (Re-forge / Adjacency / Priority).

### Step 3: Deliver (seven-section structure, in conversation)

1. **Final verdict**: one of the seven, in the original words — Double Down / Continue / Complete / Repair / Retire / Kill / Hold — with a one-line reason; if the Fine Gate failed, state **which question it died on**.
2. **Gatekeeping results**: pass/fail and evidence summary for the Coarse Gate and the Fine Gate.
3. **Chain map and Reveal**: the mapped long chain (text chain or diagram), claimed vs actual coverage side by side, Coverage Correction.
4. **Block-by-block judgments**: Incumbents, weight, satisfaction and switching, Weight of Concession, Opportunity Formula conclusions — per block, never blanket statements.
5. **Refinement**: a ranked, priced action list where every line answers "which first, what cost, what counts as done."
6. **Extension candidates**: the candidate list and three-gate screening results.
7. **To-be-supplemented list**: material gaps, each phrased as a direct factual question.

When the user wants the short form, deliver the **Five-Question Quick View** instead: Is it worth doing? / Who are the competitors (including the Folk Workaround)? / What do they lack? / What do we have that they don't? / What to refine, extend, delete — plus Timing (why now).

## Hard Disciplines

1. **No fabrication**: competitors, user behaviors, and payment evidence absent from the material are flagged "to be supplemented," never invented; "nobody has done it" is not evidence of "no solution exists."
2. **No technical-capability judgments from memory**: any judgment touching "where current technical capability stands, or whether solutions have strengthened recently" must be verified by a live web search; when search is impossible, explicitly label it "based on my knowledge cutoff of [date]; human review required." The criterion is the natural extension of existing technology — no science-fiction leaps.
3. **Every opportunity judgment must carry a shelf life**: the remaining space must be labeled "how long it holds under current technical capability, and when to re-check" — an opportunity judgment without a re-verification date is unfinished.
4. **No new evidence in conclusions**; actions must be ranked and priced — "strengthen" and "optimize" are banned.
5. **Unfavorable conclusions are delivered in full**: this method measures how well you know, not how good the news is; verdicts use only the seven original words.
6. **Order is not swappable**: answers obtained by skipping order or skipping layers are deemed foundationless and must be walked back.

## Version

B6 snapshot, packaged 2026-11-05. Authoritative text = `references/mdpaf-methodology.md`, which contains the version timeline and derivation rules (including attribution). This English edition is subordinate to the Chinese snapshot.
