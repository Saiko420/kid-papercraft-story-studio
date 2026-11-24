---
name: kid_papercraft_story_studio
description: A creative AI skill that turns beloved animation heroes into magical origami stop-motion story videos for kids. NOT a birthday-only generator. Every activation creates a brand-new, never-repeated short or long story — funny adventures, friendship tales, rescue missions, gentle mysteries and heartwarming life lessons — with ready-to-paste Gemini Omni Flash video prompts and simple English voiceover/dialogue scripts children aged 3-8 love.
---

# Kid Papercraft Story Studio

## 0. What This Skill Does

When a user wants a kids' papercraft / origami stop-motion story video, activate this skill.

It keeps everything people loved about the original Kid Papercraft world:
- The same 5 animation heroes (see Section 3)
- The same tactile origami paper look, warm lighting and stop-motion feel
- The same 10-second clip building blocks for Gemini Omni Flash

It changes ONE big thing: **the story is no longer only about birthdays.**
Birthday is now just 1 theme out of 30+. Every run must invent a **fresh story** —
a new plot, a new place, a new problem, a new funny moment and a new gentle lesson —
so a creator can publish a different video every single day.

> **Golden Rule: Never repeat a story.**
> If a story idea, title, setting + problem combination, or ending has been used
> before in this conversation, pick a different combination from the Story Engine
> (Section 5) before writing anything.

## 1. Triggers

Activate when the user says anything like:
- "Make a papercraft story video for kids"
- "Make a short video with SpongeBob / Peppa / Doraemon / Paw Patrol / Ultraman"
- "Make a long story video for my kids channel"
- "Give me a new story script for today"
- "Surprise me with a kids story video"
- In any language — reply and write titles/descriptions in English, unless the
  user explicitly asks for another language for the dialogue.

## 2. Collect Inputs (Fast — Do Not Over-Ask)

Ask at most these, and use smart defaults when the user says "surprise me",
"you choose", or gives no answer:

1. **Format** (default: Short)
   - `SHORT` — 30s (3 clips) or 60s (6 clips), vertical 9:16, for Shorts / Reels / TikTok
   - `LONG` — 3, 5 or 8 minutes, horizontal 16:9 (or 9:16 if asked), for YouTube / TV / tablet
2. **Hero / IP** (default: rotate — never use the same hero twice in a row if avoidable)
   - One of the 5 heroes in Section 3, or `RANDOM`
3. **Age group** (default: 4-6)
   - 3-4 (very simple words, repetition, colours/shapes/animals)
   - 4-6 (simple adventure, friendship, helping, funny trouble)
   - 6-8 (bigger adventure, gentle mystery, teamwork problem-solving)
4. **Theme** (default: RANDOM from the Story Engine)
   - Or a user theme: rain, space, cooking, animals, school, bedtime, sea, snow, etc.
5. **Dialogue language** (default: Simple English)
   - Keep dialogue short, warm and easy to dub. Offer subtitles text for every line.

If the user says only "make a video", do NOT ask 10 questions.
Pick: Short 60s, a rotated hero, a random theme — and create it.

## 3. The 5 Heroes — Characters and Worlds (Unchanged)

| # | IP | Lead Characters | Origami World | Personality / Comedy Engine |
|---|----|-----------------|---------------|------------------------------|
| 1 | SpongeBob SquarePants | SpongeBob & Patrick Star | Origami Bikini Bottom, pineapple house, paper coral reef | Silly dance, bubbles, innocent confusion, big laughter |
| 2 | Peppa Pig | Peppa & George | Origami grassy hills, muddy paper puddles, picnic garden | Giggling, jumping in puddles, family warmth, "oink" humour |
| 3 | Ultraman | Chibi red-and-silver hero & a friendly small monster | Miniature origami city at sunset | Heroic pose, gentle rescue, the "monster" is a friend, never a scary enemy |
| 4 | Paw Patrol | Chase & Marshall | Origami rescue town, lookout, paper kennels | Teamwork rescue, Marshall's clumsy-but-brave comedy, "no job is too big" energy |
| 5 | Doraemon | Doraemon & Nobita | Cozy origami bedroom, desk drawer, paper gadget world | A magical paper gadget causes funny trouble, then solves it kindly |

**Character lock:** In every prompt, describe the characters as
"beautifully textured colored paper cutouts / origami paper characters"
so the video model keeps the papercraft look instead of normal 3D cartoon.

## 4. The Locked Visual Style (Use in EVERY Video Prompt)

Every single clip prompt MUST end with this exact style anchor:

```text
Warm organic lighting, tactile paper textures, gentle camera pan, soft pastel color palette, whimsical and cozy atmosphere.
```

And MUST start with:

```text
Charming stop-motion animation
```

Rules:
- Everything is made of paper: paper houses, paper sea, paper stars, paper food.
- Transitions are paper transitions: paper fold wipe, page turn, paper pop-up.
- No photorealism, no CGI look, no dark/horror lighting, ever.
- Faces stay cute and friendly. Conflict is gentle: lost, stuck, mixed-up,
  wobbly, rainy, too big, too small — never violent or frightening.

## 5. THE STORY ENGINE — A Different Story Every Time

This is the heart of the skill. Build each story by combining ONE item from
each column. If the user asks again, change at least 3 columns.

### 5A. Story Type (pick 1)
1. Funny Adventure  2. Rescue Mission  3. Friendship Story  4. Gentle Mystery
5. Treasure Hunt  6. Helping a New Friend  7. Silly Invention / Gadget Trouble
8. Nature & Animals  9. Food & Cooking Fun  10. Weather Adventure (rain/snow/wind/sun)
11. Space & Moon Trip  12. Under the Sea  13. School & Learning Fun
14. Bedtime & Dreams  15. Seasons & Festivals  16. Sports & Games Day
17. Music & Dance Party  18. Garden & Growing  19. Travel & Vehicles
20. Birthday (occasional only — NOT the default)

### 5B. Setting (pick 1, must fit the hero's world)
Paper beach, paper forest, paper market, paper school, paper farm, paper zoo,
paper train, paper boat, paper rocket, paper castle, paper bakery, paper library,
paper snow hill, paper rainbow bridge, paper treehouse, paper lighthouse.

### 5C. The Gentle Problem (pick 1)
Something is lost / stuck / upside-down / too heavy / rolling away / mixed up /
hidden by rain / blown away by wind / too shy to join / forgotten / broken (paper, fixable).

### 5D. The Funny Moment (pick 1 — every story needs at least one laugh)
A silly dance, a bubble/puddle splash, a gadget that does the wrong funny thing,
a hat that lands on the wrong head, a sneeze of paper confetti, a tiny character
carrying a giant paper object, everyone walking backwards by accident.

### 5E. The Heart (pick 1 gentle lesson — shown, not lectured)
Sharing, saying sorry, helping, patience, telling the truth, trying again,
being kind to animals, brushing teeth / eating well / sleeping on time,
washing hands, tidying up, taking turns, believing in yourself, making a new friend.

### 5F. The Happy Ending (pick 1)
A paper picnic, a group hug, a tiny paper parade, a dance under paper stars,
everyone laughing on a paper hill at sunset, a cozy goodnight under a paper moon.

**Uniqueness check before output:** State the combination in one line, e.g.
`Story Mix: Doraemon + Gadget Trouble + Paper Market + Lost Kite + Confetti Sneeze + Sharing + Paper Parade`
If it matches a previous video in the chat, re-roll.

## 6. Story Structure

### SHORT video — use `skills/kid-papercraft-short-video/SKILL.md`
- 30s = 3 clips x 10s: Hook & Hello -> Problem & Funny Try -> Happy Ending & Lesson
- 60s = 6 clips x 10s: Hook -> Meet the Problem -> First Try Fails (funny) ->
  Clever Idea -> It Works! -> Happy Ending & Lesson

### LONG video — use `skills/kid-papercraft-long-video/SKILL.md`
- 3 min = 18 clips, 5 min = 30 clips, 8 min = 48 clips (grouped into scenes)
- Structure: Opening Hook -> Hello Song Moment -> The Problem -> Journey (3 stops) ->
  Funny Setback -> Teamwork Plan -> Big Happy Payoff -> Gentle Lesson -> Cozy Goodbye
- Every 60-90 seconds: a new place, a song/repetition moment, or a funny beat,
  so young viewers stay watching.

## 7. Output Format (Always Deliver ALL of This)

```markdown
# {Hero} — "{Story Title}" ({Short 30s/60s | Long 3/5/8 min} · {9:16 / 16:9})

**Story Mix:** {Hero + Type + Setting + Problem + Funny Moment + Lesson + Ending}
**Age:** {age group} · **Dialogue:** Simple English · **Moral:** {one kind sentence}

## Story Summary (3-5 lines, for the creator)
...

## Full Script & Dialogue (simple, dub-ready, with subtitles)
| Time | Who | Line |
...

## Video Prompts — Paste into Gemini Omni Flash one by one
### Clip 1 (0-10s) — {scene name}
> Dialogue: "..."
```text
{full prompt with locked style anchor}
```
... (repeat for every clip)

## Thumbnail / Title / Description (for YouTube & Shorts)
- **Video title:** ...
- **Thumbnail text (2-4 words, big):** ...
- **Description:** ...
- **Hashtags:** #kidsstories #papercraft #stopmotion ...

## Editing Notes
- Order of clips, where to add music, sound effects (paper rustle, pop, giggle),
  and the exact moment for the lesson line.
```

## 8. Kid-Safety Rules (Non-Negotiable)

- Age 3-8 only. Simple words. Short sentences. Repeat key phrases 2-3 times.
- No violence, weapons, horror, bullying as "fun", dangerous stunts, or sad endings.
- Ultraman's monster is always a friend who needs help. Paw Patrol rescues are
  always safe and gentle. Gadgets never harm anyone.
- Adults appear only as kind helpers. Strangers are never a plot device.
- Every story ends happy, calm and kind. Bedtime stories end extra calm and slow.
- See `docs/KID_SAFETY.md` for the full checklist.

## 9. Series Mode (For Daily Channels)

When the user runs a kids channel, keep a simple series log in the reply:
`Episode # · Hero · Story Mix · Moral` — and rotate hero, setting and moral
on the next episode. Suggest the next episode idea at the end, but do not
repeat a used Story Mix.

## 10. Copyright Note

This is an unofficial, fan-made prompt skill for personal / family creative use.
All characters and IPs belong to their respective owners. See README disclaimer.
Do not present generated videos as official productions of any studio.
