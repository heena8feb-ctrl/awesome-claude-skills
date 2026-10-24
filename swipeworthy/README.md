# Swipeworthy

**Turn any long blog post into an 8–10 slide LinkedIn or Instagram carousel people actually swipe, save and share.**

Swipeworthy is a Claude skill. It doesn't summarize your blog. It mines the post for its sharpest ideas and rebuilds them as a carousel, with a hook built to stop the scroll and a reason to swipe on every slide.

## Why it works

- **Scored hooks.** It writes 10 hooks across proven formulas, scores each on specificity, tension, relevance, honesty and brevity, and gives you the top 3 to A/B test.
- **Slide-2 re-hook.** Instagram often re-serves carousels from slide 2, so slide 2 is written to hook on its own.
- **Swipe tension on every slide.** Cliffhangers, open loops and progress cues keep people moving.
- **Pattern interrupt.** A twist slide around 60% through, where attention usually drops.
- **Save slide.** A cheat sheet near the end that is worth bookmarking.
- **Callback ending.** The CTA slide echoes the hook so the story feels complete.
- **10 narrative arcs.** Myth → Truth, Mistakes countdown, Framework reveal, Teardown, Self-diagnosis and more.
- **No fabrication.** It never invents stats; it flags gaps with `[ADD DATA?]`.
- **Built-in quality gate.** It scores itself on 8 checks and revises weak spots before you see the output.

## What you get

- 3 hook options (scored)
- 8–10 slides, each with a headline, body, emphasis word, visual direction and swipe trigger
- Caption, first comment, hashtags and alt text
- Quality-gate scores
- One remix suggestion (a different arc, audience or tone)

## Example

**Prompt**

```
Turn this into a LinkedIn carousel: [1,500-word blog on why company AI pilots stall after the demo]
```

**Output (excerpt)**

```
BLOG → CAROUSEL
Platform: LinkedIn | Audience: business leaders | Goal: saves | Arc: Myth → Truth | Slides: 9

HOOK OPTIONS
A) Your AI pilot didn't fail. Your rollout did. (23/25) ← used
B) The demo worked. So why is nobody using it? (21/25)
C) 3 reasons AI pilots die after the applause (20/25)

SLIDE 1 — HOOK
Headline: Your AI pilot didn't fail. Your rollout did.
Subline: What happens after the demo decides everything
Visual: Bold headline on plain background, arrow bottom-right
Swipe trigger: "Here's what really breaks →"

SLIDE 2 — RE-HOOK
Headline: The demo is the easy part
Body: Most pilots impress in the meeting, then stall in week 2.
Nobody owns the workflow, and the old process never gets switched off.
Swipe trigger: "Fix #1 costs nothing →"
...
```

The full example is in [SKILL.md](./SKILL.md).

## Install

**Claude.ai / Claude app:** zip the `swipeworthy` folder, then upload it under Settings → Capabilities → Skills.

**Claude Code:** copy the folder into `~/.claude/skills/swipeworthy/` (personal) or `.claude/skills/swipeworthy/` (project).

**API:** upload the folder as a custom skill, or include SKILL.md in your system prompt.

## Use

Basic:

```
Turn this blog into a carousel: [paste blog or URL]
```

Advanced:

```
Turn this blog into a 9-slide Instagram carousel for first-time founders.
Goal: saves. Voice: friendly but direct. Use the Mistakes countdown arc.
[paste blog or URL]
```

Without platform, audience or goal, it uses sensible defaults and tells you which.

## Compatibility and safety

- Works on Claude.ai, Claude Code and the API, with no extra tools required.
- Read-only: it writes copy and never posts, schedules or edits your accounts.
- Every carousel includes alt text for accessibility.

## Files

```
swipeworthy/
├── SKILL.md   # the skill
└── README.md  # this file
```

## Author

Built by [Heena](https://github.com/heena8feb-ctrl) from her workflow for repurposing long-form AI posts into LinkedIn and Instagram carousels. Feedback and pull requests are welcome.

## License

MIT
