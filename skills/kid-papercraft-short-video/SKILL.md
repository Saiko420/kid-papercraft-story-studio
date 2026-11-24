---
name: kid_papercraft_short_video
version: 2.0
description: Create a brand-new 30s or 60s origami stop-motion SHORT story video for kids (Shorts, TikTok, Reels) with realistic talking characters, a rubric-scored script and a pro editing plan. A different funny, heartwarming story every time — never birthday-only, never repeated. Outputs the full script plus ready-to-paste Gemini Omni Flash prompts with lip-synced dialogue.
---

# Kid Papercraft — Short Video Skill v2 (30s / 60s)

Master Skill rules apply (Story Engine, Script Quality System §6, Talking
Characters §7, Editing System §8, Kid-Safety). This file adds short-form specifics.

## 1. Length & Format
- **30s = 3 clips × 10s** (one idea, one lesson) · **60s = 6 clips × 10s** (DEFAULT, fuller story)
- **9:16 vertical.** Set 9:16 in Gemini Omni Flash before generating.
- Design a **loop ending**: the last frame echoes the first frame, so the Short replays seamlessly.

## 2. Structures

### 30s
| Clip | Job | Talk |
|------|-----|------|
| 1 (0-10s) | HOOK in motion + story question | Hero's hook line (max 8 words) |
| 2 (10-20s) | PROBLEM + funny failed try | Friend's line + giggle reaction |
| 3 (20-30s) | PAYOFF + lesson line + wave | Lesson line, catchphrase repeat |

### 60s
| Clip | Job |
|------|-----|
| 1 | HOOK — funny entrance + today's adventure announced (speaking close-up) |
| 2 | MEET THE PROBLEM — reaction shot of friend |
| 3 | FIRST TRY FAILS — funniest moment, punch-in zoom in editing |
| 4 | CLEVER IDEA — call-and-response with the audience ("Say YES!" + pause) |
| 5 | IT WORKS! — celebration, confetti, group line (one speaker only) |
| 6 | LESSON + goodbye + next-time tease, loop-back frame |

## 3. Short-Form Script Rules (on top of Master §6)
- Hook line must be speakable in under 3 seconds.
- ONE idea only. If a second subplot appears in drafting, cut it.
- A laugh or a surprise at least every 15 seconds.
- Subtitle every line; plan the highlighted keyword per line in the script table.
- Score with the Master Rubric; do not deliver under 32/40 — rewrite instead.

## 4. Talking in Shorts
- Use the Talking Prompt Formula (Master §7.1) in every dialogue clip.
- Close-up or medium shot for every spoken line — faces sell Shorts.
- Speaker order alternates (hero → friend → hero…) so both characters feel alive.
- Keep mouths visible; no line is delivered while running, jumping or facing away.

## 5. Editing Plan for Shorts (always include, per Master §8)
- Trim 0.3s heads/tails; hard cuts inside scenes, paper-wipe between scenes.
- Punch-in (scale 100%→115%) on the funniest frame; freeze-frame 0.4s + "boing" on the funny fall.
- SFX list per clip (paper rustle, pop, boing, sparkle, giggle).
- Music: cheerful loop, ducked -18dB under voices; final "sparkle + pop" on the lesson word.
- Subtitles in the safe zone (upper-middle), never under the bottom platform UI.
- Export: 1080×1920, 30fps, H.264, ≈ -14 LUFS.

## 6. Prompt Template (with talking block)
```text
Charming stop-motion animation in {SETTING}. Beautifully textured colored
paper cutouts of {CHARACTERS}. {ACTION}. {SPEAKER} faces {listener/camera}
and speaks with clear, natural lip movement synced to the words, saying in a
{VOICE PROFILE}: "{LINE}". While speaking: {EXPRESSION + GESTURE}, natural
blinking. {LISTENER} listens with mouth closed, {REACTION}. Warm organic
lighting, tactile paper textures, gentle camera pan, soft pastel color
palette, whimsical and cozy atmosphere.
```

## 7. Worked Example (v2 standard — talking, scored)
**Pipo & Momo — "The Lost Paper Kite" · 60s · Script score target 36/40**
Original characters: Pipo, a tiny round blue origami bird (voice: bright, quick,
catchphrase "Let's try!") · Momo, a small pink origami rabbit (voice: soft,
sweet, catchphrase "Oh my ears!")
- C1 Hook (close-up Pipo): kite flying, big sneeze — "Oh no! Our kite flew away!"
- C2 Problem (two-shot): kite stuck in the paper tree. Momo: "It's too high, Pipo!"
- C3 Funny fail: stone stack wobbles, leaf-pile tumble. Pipo (giggling): "Let's try… again!"
- C4 Idea (close-up Momo): "Gogo can jump! Can you call him? Say GO-GO!" (audience pause)
- C5 Payoff: frog friend frees the kite, confetti stars. Pipo: "We did it — together!"
- C6 Lesson (both, Pipo speaks): "Helping each other makes everything better!" + wave + loop frame.
Expand every clip with the Section 6 template before delivery — never deliver scene notes as final prompts.
