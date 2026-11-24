---
name: kid_papercraft_story_studio
version: 2.0
description: A creative AI skill that turns beloved animation heroes and original paper characters into magical origami stop-motion story videos for kids. Every activation creates a brand-new, never-repeated short or long story with a professional-quality script, REALISTIC TALKING characters (lip-synced dialogue, natural expressions and gestures), and a complete pro editing plan — ready-to-paste Gemini Omni Flash prompts included. Funny adventures, friendship tales, rescue missions, gentle mysteries and heartwarming lessons children aged 3-8 love.
---

# Kid Papercraft Story Studio — v2

## 0. What This Skill Does

When a user wants a kids' papercraft / origami stop-motion story video, activate this skill.

Kept from the original Kid Papercraft world:
- The same 5 animation heroes (Section 3) + support for original paper characters
- The same tactile origami paper look, warm lighting and stop-motion feel
- The same 10-second clip building blocks for Gemini Omni Flash

The purpose: **a fresh, high-quality story video every time — not birthday-only.**
Birthday is 1 theme out of 20+.

> **Golden Rule 1: Never repeat a story.** Change at least 3 Story Engine columns per video.
> **Golden Rule 2: Characters must TALK like real characters** — visible lip movement
> synced to their lines, natural expressions, gestures and reactions (Section 7).
> **Golden Rule 3: Two-pass writing.** Draft the script, score it against the
> Script Quality Rubric (Section 6), rewrite the weak parts, THEN deliver (Section 6.4).

## 1. Triggers

"Make a papercraft story video for kids" · "Make a short/long video with
SpongeBob / Peppa / Doraemon / Paw Patrol / Ultraman" · "Give me a new story
script for today" · "Surprise me" — in any language. Titles, descriptions and
dialogue default to simple English unless the user asks otherwise.

## 2. Collect Inputs (Fast — Do Not Over-Ask)

Defaults in brackets — use them silently when the user says "surprise me":
1. **Format** [Short 60s]: SHORT 30s/60s 9:16 · LONG 3/5/8 min 16:9
2. **Hero** [rotate, never same hero twice in a row]: one of Section 3, an
   original character set, or RANDOM
3. **Age group** [4-6]: 3-4 very simple · 4-6 simple adventure · 6-8 bigger adventure/mystery
4. **Theme** [RANDOM from Story Engine]
5. **Voices** [characters talk, native video audio]: see Section 7.4 for voice workflow

## 3. Heroes and Characters

| # | IP | Leads | Origami World | Voice & Talk Style (see docs/TALKING_CHARACTERS.md) |
|---|----|-------|---------------|------------------------------------------------------|
| 1 | SpongeBob SquarePants | SpongeBob & Patrick | Bikini Bottom, pineapple house | Fast, giggly, high energy / slow, sweet, simple |
| 2 | Peppa Pig | Peppa & George | Grassy hills, muddy puddles | Confident, cheerful / tiny voice, "dinosaur!" moments |
| 3 | Ultraman | Chibi hero & friendly monster | Mini origami city at sunset | Brave, warm, few words / cute roars + simple words |
| 4 | Paw Patrol | Chase & Marshall | Rescue town, lookout | Clear, leader-like / clumsy-funny, excited |
| 5 | Doraemon | Doraemon & Nobita | Cozy bedroom, gadget world | Kind, clever / worried → brave arc |
| ★ | Original characters | Creator's own paper heroes (e.g. Pipo the bird & Momo the rabbit) | Any paper world | Define a voice profile in the output (pitch, speed, catchphrase) |

**Character lock:** describe characters in every prompt as "beautifully textured
colored paper cutouts / origami paper characters" and repeat the SAME character
description sentence in every clip of a video.

## 4. Locked Visual Style (Every Prompt)

Start: `Charming stop-motion animation`
End, exactly: `Warm organic lighting, tactile paper textures, gentle camera pan, soft pastel color palette, whimsical and cozy atmosphere.`
Everything is paper. Transitions are paper transitions. No photorealism, no dark/horror, faces always cute and friendly.

## 5. The Story Engine — A Different Story Every Time

Combine ONE from each: **Type** (funny adventure, rescue, friendship, gentle
mystery, treasure hunt, new friend, gadget trouble, animals, cooking, weather,
space, under the sea, school, bedtime, festivals, sports, music, garden,
travel, birthday-occasionally) × **Setting** (16 paper places, docs/STORY_BANK.md)
× **Gentle Problem** (lost/stuck/mixed-up/shy/wobbly/rolling away…) ×
**Funny Moment** (silly dance, confetti sneeze, wrong-hat, backwards walk…) ×
**Lesson** (sharing, helping, patience, truth, trying again, kindness…) ×
**Happy Ending** (picnic, parade, dance under paper stars, cozy goodnight…).
State the mix in one line in the output; if it matches a previous video, re-roll.

## 5.5 THE KAHINI RULE — A Video Is a STORY, Not a Scene Collection (v2, highest priority)

A script with only nice scenes is a FAILED script. Every script must first pass
the **Kahini Test** — all 7 elements, written down in the output before the script:

1. **Hero's Want:** the hero clearly WANTS one specific thing (to give, to find,
   to fix, to reach, to surprise, to win kindly, to help someone specific).
2. **Why It Matters (the Heart):** one emotional reason the audience cares —
   friendship, a promise, someone sad, someone who believes in the hero.
3. **Obstacle 1:** the first attempt fails in a funny way.
4. **Obstacle 2 (worse):** a bigger problem — time running out, rain coming,
   a misunderstanding ("He forgot me…"), the plan breaks. Feelings rise.
5. **The Low Moment:** one quiet beat where the hero almost gives up (2-3 seconds
   in Shorts, a full scene in Long). This is what makes the ending FEEL good.
6. **The Climax Idea:** the hero solves it in a clever way that uses something
   shown earlier (a friend's talent, an object from scene 1, the lesson itself).
   No random rescues, no magic from nowhere.
7. **The Payoff + Change:** the hero gets (or gives up kindly) what they wanted,
   and someone has CHANGED — braver, kinder, friends again, proud.

**One-sentence kahini formula (state it in the output):**
`{Hero} wants {want} because {heart}, but {obstacle 1} and {obstacle 2} stop them,
until {climax idea} — and in the end {change}.`

If any element is missing, DO NOT write clips. Fix the kahini first.
Suspense for kids = one open question kept alive until the climax:
"What is in the box?" / "Will they reach home before dark?" / "Why is Momo hiding?"
Every scene must either move toward the answer or make the question bigger.

## 6. SCRIPT QUALITY SYSTEM (v2 — the heart of better stories)

Full guide: `docs/SCRIPT_WRITING.md`. Non-negotiable rules:

### 6.1 The First 2 Seconds Decide Everything
Open IN motion, mid-action, with ONE of these hook types:
- **Question hook:** "Oh no! Where did the kite go?!"
- **Surprise hook:** a pop, a sneeze, something falling/rolling/flying in frame 1
- **Promise hook:** "Today we find the Rainbow Shell!"
Never open with "Once upon a time", a slow landscape, or an introduction.

### 6.2 Story Beats (every story, any length)
Hook → Promise (what fun thing they want) → Problem → Try 1 fails funny →
Try 2 with a friend's idea → It works (payoff mirrors the opening) →
Lesson line (one warm sentence) → Goodbye + next-time tease (series) or
loop-back ending (Shorts: last frame echoes first frame).

### 6.3 Dialogue Rules
- One speaker at a time. **Max words per line:** age 3-4 → 5 words · 4-6 → 8 words · 6-8 → 12 words.
- Every line must DO something: move the story, get a laugh, or teach by showing.
  Delete any line that only explains what we can already see.
- Each character has a **catchphrase** used twice (opening + payoff).
- **Call and response** at least once per video: "Can you help us? Say YES!" + 2s pause.
- Repetition with a twist: repeat the key phrase 3 times across the video,
  changing one word or the emotion each time.
- Write dialogue in the script table AND inside the video prompts (Section 7).

### 6.4 Two-Pass Writing + Rubric (score before delivering)
Draft → score each 0-5 → rewrite anything under 4 → deliver the improved version:
Kahini completeness (all 7 elements of §5.5) · Hook strength · Clarity for a
4-year-old · Funny moments (min 2) · Dialogue naturalness · Lesson
shown-not-lectured · Ending satisfaction · Talkability (lines short enough to
lip-sync). Mention the final score line in the output: `Script score: 37/40`.
A script scoring under 5 on Kahini completeness must never be delivered.

## 7. REALISTIC TALKING CHARACTERS (v2 — characters must really talk)

Full guide: `docs/TALKING_CHARACTERS.md`. Core system:

### 7.1 The Talking Prompt Formula (use in EVERY dialogue clip)
Add this block to the clip prompt, filled in:
```text
{TALKING CHARACTER} faces {the other character / the camera} and speaks with
clear, natural lip movement synced to the words, saying in a {voice profile}:
"{THE EXACT LINE}". While speaking: natural blinking, small head nods on the
important words, eyebrows moving with the emotion ({happy / surprised / worried / proud}),
and a small hand/wing/paw gesture. {LISTENING CHARACTER} listens with mouth
closed, nodding and smiling, then reacts with {reaction: giggle / gasp / clap}.
```
Rules that make it look real:
- **One speaker per clip.** Two characters never speak in the same clip.
- The speaker's **face must be visible and unobstructed** (no talking with back
  turned, no object covering the mouth).
- **Line length:** max ~12 words per 10s clip — slow, clear, kid pace. Split longer lines across clips.
- Put the line in the prompt **in quotes, exactly as scripted** — the video model
  uses it for both the voice and the lip movement.
- End every dialogue clip with a 0.5s natural pause (mouth closes, smile) so
  editing can cut cleanly between speakers.

### 7.2 Shot Language for Conversations
- **Two-shot** to establish who is talking to whom → **close-up** for the
  important line → **reaction shot** of the listener. Rotate these; never film
  a whole conversation in one wide shot.
- Note the shot type in every row of the script table.

### 7.3 Expression & Gesture Vocabulary (pick per line, write it in the prompt)
Happy: eyebrows up, cheek puff smile, little hop · Surprised: mouth "O", wings/paws
up, step back · Worried: eyebrows together, ears down, hands together ·
Thinking: head tilt, one eyebrow up, tap chin · Proud: chest out, chin up ·
Sorry: head down, then looks up kindly · Giggling: shoulders shake, hands on belly.

### 7.4 Voice Workflow (choose one, state it in the output)
- **A. Native video audio (default):** the line is inside the prompt (7.1);
  Gemini Omni Flash generates voice + lip-sync together. Regenerate a clip if
  the words come out wrong — never accept mispronounced hero names.
- **B. AI voice / TTS dub:** generate the voice lines first (one file per line),
  measure each line's seconds, generate the video clips to match those lengths,
  lay the voices on the editing timeline (docs/EDITING_GUIDE.md §4).
- **C. Human recording:** for a parent/teacher's own voice — same timing method as B.
Keep ONE voice per character for the whole series (same profile text every time).

## 8. PRO EDITING SYSTEM (v2)

Full guide: `docs/EDITING_GUIDE.md`. Every output must include an **Editing Plan**:
- **Timeline map:** clip order, trims (cut first/last 0.3s of each generated clip),
  J-cuts/L-cuts so dialogue flows across cuts, punch-in zoom on the funniest moment.
- **Transitions:** paper fold wipe / page turn between scenes; hard cuts inside a scene.
- **Sound design:** paper rustle under movements, pop on appearances, boing on
  funny falls, sparkle on magic, giggles on laughs; cheerful music (ukulele/marimba
  style) ducked under voices.
- **Subtitles:** every spoken line, 2-4 words per chunk, big rounded bold font,
  the important word highlighted in yellow, gentle bounce-in — placed in the
  Shorts safe zone (not under the platform UI).
- **Pacing:** a visual change every 2-3 seconds in Shorts; every 60-90s a new
  place/song/funny beat in Long videos.
- **Export settings:** Shorts 1080×1920 · Long 1920×1080 · 30fps · H.264 ·
  loudness ≈ -14 LUFS, voices always clear above music.

## 9. Output Format (Always Deliver ALL of This)

```markdown
# {Hero} — "{Story Title}" ({Short 30s/60s | Long 3/5/8 min} · {9:16 / 16:9})
**Story Mix:** ... · **Age:** ... · **Moral:** ... · **Script score:** {n}/35

## Story Summary (3-5 lines)
## Full Script (table: Time · Shot · Who · Line · Expression/Gesture · SFX · Subtitle)
## Video Prompts (one per clip, WITH the Talking Prompt Formula for dialogue clips)
## Editing Plan (timeline, transitions, sound, subtitles, export — per Section 8)
## Publishing Pack (title, thumbnail text, description, chapters for Long, hashtags)
## Voice Notes (which workflow A/B/C, each character's voice profile)
```

## 10. Kid-Safety (Non-Negotiable)
Ages 3-8 · simple words · gentle conflict only (lost/stuck/shy/mixed-up) ·
no violence, weapons, horror, bullying, dangerous stunts or sad endings ·
monsters are friends · every story ends happy and calm · full checklist:
`docs/KID_SAFETY.md`.

## 11. Series Mode
Log every episode: `Episode # · Hero · Story Mix · Moral · Script score`.
Rotate hero, setting, lesson daily. End each video with a next-episode tease line.

## 12. Copyright Note
Unofficial fan-made prompt skill for personal/family/educational creative use.
All named characters/IPs belong to their respective owners; original characters
belong to their creator. See README disclaimer before publishing/monetizing.
