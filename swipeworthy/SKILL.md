---
name: swipeworthy
description: Turn a long blog post or article into an 8–10 slide LinkedIn/Instagram carousel with a scroll-stopping hook, swipe tension on every slide, and a caption.
---

# Swipeworthy

Turns a long blog post or article into 8–10 slides of LinkedIn or Instagram carousel copy built for engagement. It doesn't summarize the post: it mines the best ideas, picks a narrative arc, engineers a scored hook, and gives every slide a reason to swipe. The output includes a caption, first comment, hashtags and alt text.

## When to Use This Skill

- You've published a blog, newsletter or article and want to repurpose it for LinkedIn or Instagram
- You need a carousel that stops the scroll, not a bullet-point summary
- You want hook options to A/B test before posting
- You want consistent, on-voice carousel copy without starting from a blank page

## What This Skill Does

1. **Mines the source**: Pulls out the one-sentence promise, the load-bearing points, the best numbers and stories, the tension and the twist. It never invents stats; gaps are flagged with `[ADD DATA?]`.
2. **Picks a narrative arc**: Chooses one of 10 arcs (Myth → Truth, Mistakes countdown, Framework reveal, Teardown, Self-diagnosis and more).
3. **Engineers the hook**: Writes 10 hooks across proven formulas, scores each on specificity, tension, relevance, truthfulness and brevity, and shows the top 3.
4. **Builds swipe tension**: Gives slide 2 a standalone re-hook, ends every slide with a swipe trigger, places a pattern-interrupt slide around 60% through, adds a save-worthy cheat-sheet slide, and closes with a CTA that calls back to the hook.
5. **Writes the extras**: Caption, first comment, hashtags, alt text and design direction for every slide.
6. **Checks itself**: Runs an 8-point quality gate and revises weak spots before delivering.

## How to Use

### Basic Usage

```
Turn this blog into a carousel: [paste blog or URL]
```

### Advanced Usage

```
Turn this blog into a 9-slide Instagram carousel for first-time founders.
Goal: saves. Voice: friendly but direct. Use the Mistakes countdown arc.
[paste blog or URL]
```

## Example

**User**: "Turn this into a LinkedIn carousel" + a 1,500-word blog post about why most company AI pilots stall after the demo.

**Output** (excerpt):
```
BLOG → CAROUSEL
Platform: LinkedIn | Audience: business leaders | Goal: saves | Arc: Myth → Truth | Slides: 9
Promise: Why AI pilots stall after the demo, and the 3 fixes that get them to production.

HOOK OPTIONS
A) Your AI pilot didn't fail. Your rollout did. (23/25) ← used
B) The demo worked. So why is nobody using it? (21/25)
C) 3 reasons AI pilots die after the applause (20/25)

SLIDE 1 — HOOK
Headline: Your AI pilot didn't fail. Your rollout did.
Subline: What happens after the demo decides everything
Emphasis: rollout
Visual: Bold headline on plain background, arrow bottom-right
Swipe trigger: Arrow + "Here's what really breaks →"

SLIDE 2 — RE-HOOK
Headline: The demo is the easy part
Body: Most pilots impress in the meeting, then stall in week 2. Nobody owns the workflow, and the old process never gets switched off.
Emphasis: week 2
Visual: Split layout: "Demo day" vs "Week 2"
Swipe trigger: "Fix #1 costs nothing →"

...

SLIDE 9 — CTA + CALLBACK
Headline: Don't fix the AI. Fix the rollout.
Body: Save this for your next pilot kickoff.
CTA: Comment "ROLLOUT" for the 1-page checklist.

QUALITY GATE: Hook 5 · Slide-2 5 · Swipe 4 · One-idea 5 · Payoff 4 · Save 5 · Fidelity 5 · Voice 4
```

**Inspired by:** [Heena](https://github.com/heena8feb-ctrl)'s workflow for repurposing long-form AI posts into LinkedIn and Instagram carousels

## Tips

- Give the goal (saves, comments, follows or clicks); it changes the CTA and the save slide
- Pick hook B or C from the options if A doesn't sound like you, and ask it to rebuild slide 1
- Ask for a remix: most blogs hold 2–3 carousels with different arcs
- Paste the slides into Canva, Adobe Express or Claude Design using the visual notes

## Compatibility and Safety

- **Works on:** Claude.ai, Claude Code and the API. It needs no tools; when given a URL, it uses web fetch if available, otherwise it asks for the pasted text.
- **Read-only:** It only writes copy. It never posts, schedules or edits anything on your accounts.
- **Accessible output:** Every carousel includes alt text for each slide.
- **No fabrication:** Claims, numbers and quotes come only from your source; missing data is flagged, never invented.

## Common Use Cases

- Repurposing company blog posts into LinkedIn carousels
- Turning newsletters into Instagram educational carousels
- Converting case studies into teardown carousels
- Turning long threads or talks into save-worthy cheat sheets

---

# Instructions

Convert a long-form post into 8–10 slides of carousel copy engineered for stops, swipes, saves, comments and shares. A carousel is not a summary of the blog. It is a new piece built from the blog's best raw material, with one idea, one arc and one reason to keep swiping.

## 0. Inputs

Get the source first: pasted text, an attached file, or a URL (fetch it). Then settle these. If the person gave them, use them; if not, use the defaults and state them in one line at the top of the output rather than asking.

| Input | Default |
|---|---|
| Platform | LinkedIn (also flag Instagram tweaks) |
| Audience | The reader the blog was written for |
| Primary goal | Saves (alternatives: comments, follows, profile/link clicks, DMs) |
| Voice | Match the blog's voice, tightened |
| Slide count | 8–10; pick the number the material earns, never pad |
| Brand handle / CTA | Ask only if the CTA depends on it; otherwise leave a placeholder like @handle |

Only ask a question up front if the source is missing.

## 1. Mine the blog (don't summarize it)

Read the whole post and pull out, in a private working list:

- **The one-sentence promise**: what will the reader be able to do, avoid or understand after swiping? If you can't write this in under 15 words, the carousel has no spine yet.
- **Load-bearing points**: the 3–7 ideas the argument actually depends on. Drop everything else, however good.
- **Gold**: specific numbers, named examples, before/after contrasts, a story moment, a surprising claim, a quotable line, a mistake most people make, a step list, a framework.
- **Tension**: what does the reader currently believe or do that the blog says is wrong, slow or costly? This is your hook fuel.
- **The twist**: the least obvious insight in the post. It becomes the pattern-interrupt slide.

Never invent statistics, quotes or results that aren't in the source. Where a number would strengthen a slide but the blog has none, mark it `[ADD DATA?]` for the author.

## 2. Choose the narrative arc

Pick ONE arc that fits the material. Name it in the output.

1. **Myth → Truth**: common belief, why it fails, what actually works.
2. **Mistakes countdown**: "7 mistakes…" ending on the costliest.
3. **Framework reveal**: a named model (e.g. "The 3R method"), one slide per component.
4. **Before / After / Bridge**: painful status quo, desired state, the steps between.
5. **Teardown**: dissect one example, case or failure.
6. **Open-loop mystery**: pose a puzzle on slide 1, deliver the answer late.
7. **Data story**: one striking number, then what's behind it and what to do.
8. **Playbook**: ordered steps the reader can copy today.
9. **Contrarian take**: an unpopular opinion defended with evidence.
10. **Self-diagnosis**: "Which one are you?" with types or levels the reader places themselves in.

If two arcs fit equally, pick the one that creates more tension on slide 1.

## 3. Engineer the hook (slide 1)

Slide 1 is the ad for the whole carousel. Write **10 candidate hooks** across these formulas, then score them.

- **Specific promise**: "How we cut onboarding from 6 weeks to 9 days"
- **Contrarian**: "Stop writing prompts. Write briefs."
- **Costly mistake**: "The reporting habit quietly costing you 5 hours a week"
- **Curiosity gap**: "The one slide every CHRO skips (and shouldn't)"
- **Identity call-out**: "If you manage a team of 5–15, read this"
- **Number + outcome**: "9 AI workflows that pay back in a week"
- **Before/after**: "From 200 tickets a day to 40"
- **Confession / story**: "I wasted 3 months on the wrong dashboard"
- **Question that stings**: "Why does your best analyst spend Fridays in Excel?"
- **Bold claim + proof promise**: "Most AI pilots fail in week 2. Here's the fix."

Score each 1–5 on: **Specificity**, **Tension** (does it challenge or threaten something?), **Relevance** to the stated audience, **Truthfulness** to the blog (no clickbait the slides can't pay off), **Brevity** (≤ 10 words headline). Pick the highest total; show the top 3 in the output as A/B options.

Slide 1 rules:
- Headline ≤ 10 words. Optional subline ≤ 12 words that adds stakes or credibility.
- Must make a promise the final slides keep.
- Include a visual swipe cue (→, "swipe", or a cut-off element) in the design note.

## 4. Build the slide roles

Default structure for 10 slides (compress for 8–9 by merging payload slides, never by cutting the re-hook, twist or CTA):

| # | Role | Job |
|---|---|---|
| 1 | **Hook** | Stop the scroll, make a promise |
| 2 | **Re-hook / stakes** | Second chance to grab people. Instagram often re-serves a carousel starting at slide 2 to people who didn't swipe, so slide 2 must work as a standalone hook too. State the cost of the problem or the stakes. |
| 3 | **Setup** | The myth, the status quo, or the framework's name. Earn credibility in one line (from the blog). |
| 4–7 | **Payload** | One idea per slide, each concrete and usable on its own |
| 6 or 7 | **Pattern interrupt** | Around 60% through, break rhythm: the twist, a surprising number, a "most people stop here" line, a flipped layout, or a one-line slide. This is where attention dips. |
| 8 | **Payoff** | The big result or the costliest mistake; the moment the promise lands |
| 9 | **Save slide** | A cheat sheet, checklist or 1-screen recap of the whole carousel — the slide people save for later |
| 10 | **CTA + callback** | Echo slide 1's hook, then one low-friction action |

## 5. Swipe mechanics (apply to every slide)

- **End every slide 1–9 with a swipe trigger**: an incomplete list ("3 of 5…"), a cliffhanger ("…but that's not the real problem"), a promise ("The fix is on the next slide"), or a progress marker ("Step 2/5"). Write it explicitly in the output.
- **Open loops**: open at least one question early (slides 1–3) and close it late (slides 8–10).
- **Progress cues**: number steps or show "3/7" so the end feels reachable.
- **Micro-wins**: every payload slide gives something usable even if the reader stops there.
- **Callback ending**: the last slide reuses a phrase or image from slide 1, so the piece feels complete.

## 6. Engagement design

Plan these deliberately, matched to the primary goal:

- **Saves**: a real cheat-sheet slide (slide 9), templates, checklists, "steal this" prompts or scripts.
- **Comments**: a low-effort prompt. Prefer one-word or pick-one replies ("Which one are you: A, B or C?", "Comment 'TEMPLATE' and I'll send it") over open essays ("What do you think?"). For keyword-to-DM prompts, only use them if the author can actually deliver.
- **Shares/sends**: an identity line ("Send this to the person who still…") or a slide that makes the sharer look smart.
- **Follows**: one line of positioning on the CTA slide ("I post one AI workflow every Tuesday").
- **Self-diagnosis**: where it fits, add a "score yourself" or "which type are you" element; people engage with content about themselves.

Use at most ONE primary CTA on the last slide. Secondary actions go in the caption.

## 7. Copy rules

- One idea per slide. If a slide needs "and also", split or cut.
- **Headline ≤ 8 words** (slide 1: ≤ 10). **Body ≤ 30 words** per slide; payload slides ideally 15–25. The save slide may go to 45 words if formatted as a list.
- Write at a grade 6–8 reading level. Short words. Active voice. No hedging ("might", "perhaps", "in some cases") unless accuracy needs it.
- Concrete beats abstract: numbers, names, timeframes, before/after.
- Lead with the verb or the outcome on payload slides ("Cut the status meeting", not "Status meetings can be reduced").
- Mark **one emphasis word or phrase** per slide for bold/colour.
- No jargon the audience wouldn't use. No emoji walls; at most one meaningful emoji per slide, and none if the brand is formal.
- Every slide must make sense if screenshotted alone.
- Kill these phrases: "In today's fast-paced world", "Let's dive in", "game-changer", "unlock the power of", "it's important to note", "in conclusion".

## 8. Design direction (copy-adjacent)

For each slide give a one-line visual note the designer (or Canva / Adobe Express / Claude Design) can follow: layout (big number, split before/after, checklist, quote card, single line on blank), the emphasis word, and any icon or image idea. Keep one consistent template across slides and break it only on the pattern-interrupt slide. Default size: 1080×1350 (4:5) for both LinkedIn and Instagram.

## 9. Caption and extras

Write:
- **Caption**: first line is a different hook from slide 1 (it shows before "…more"); 3–6 short lines of context or the story behind the post; a soft CTA; for LinkedIn, no external link in the post body (suggest it for the first comment instead).
- **First comment**: link to the full blog, or a bonus tip that rewards people who open comments.
- **Hashtags**: LinkedIn 3–5, Instagram 5–10, mixing broad and niche. Skip if the author doesn't use them.
- **Alt text**: one sentence per slide for accessibility (Instagram).

## 10. Quality gate (run before output)

Score the draft 1–5 on each; revise any item below 4.

1. **Hook stop power**: would the target reader stop scrolling?
2. **Slide-2 standalone**: does slide 2 hook someone who skipped slide 1?
3. **Swipe tension**: does every slide 1–9 end with a reason to swipe?
4. **One idea per slide** and within word limits?
5. **Payoff honesty**: do the slides fully deliver what slide 1 promised?
6. **Save value**: is slide 9 genuinely worth saving?
7. **Fidelity**: is every claim, number and quote traceable to the blog? (`[ADD DATA?]` flags are fine.)
8. **Voice**: does it sound like the author, not like an AI?

Show the final scores in one compact line.

## 11. Output format

Deliver in the reply (or as a doc if the person asks to keep or share it):

```
BLOG → CAROUSEL
Platform: … | Audience: … | Goal: … | Arc: … | Slides: N
Promise: <one sentence>

HOOK OPTIONS (pick one)
A) … (score x/25)  ← used below
B) …
C) …

SLIDE 1 — HOOK
Headline: …
Subline: …
Emphasis: …
Visual: …
Swipe trigger: …

SLIDE 2 — RE-HOOK
Headline: …
Body: …
Emphasis: …
Visual: …
Swipe trigger: …

…(through the last slide; last slide has CTA instead of swipe trigger)

CAPTION
…

FIRST COMMENT
…

HASHTAGS
…

ALT TEXT
1. … 2. …

QUALITY GATE: Hook 5 · Slide-2 4 · Swipe 5 · One-idea 5 · Payoff 5 · Save 4 · Fidelity 5 · Voice 4
```

## 12. Remix options (offer one line at the end)

After delivering, offer one of: a second carousel from the same blog using a different arc (the blog usually holds 2–3), a punchier contrarian version, a version for a different audience, or the slides built visually in Canva/Claude Design.

## Edge cases

- **Thin source** (under ~500 words or one idea): make 8 slides max and say so; suggest what the author could add.
- **Very long source** (5,000+ words): pick the single strongest thread; list the 2 other carousels it could become.
- **Listicle blog with 15+ items**: pick the best 5–6, name the selection logic on slide 3 ("the 5 that actually moved the numbers").
- **Technical/enterprise audience**: keep the swipe mechanics, raise the precision; replace hype with specifics and proof.
- **Personal story post**: use Before/After/Bridge or Confession arc; keep the lesson explicit by slide 8.
