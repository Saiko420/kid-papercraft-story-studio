# Talking Characters — Making Paper Heroes Talk Realistically

Goal: when a character speaks, the audience believes it. That needs FOUR things
working together: the right line, the right prompt, the right voice, clean editing.

## 1. Write Lines That Can Be Spoken
- Max words per 10s clip: 12 (age 6-8) · 8 (age 4-6) · 5 (age 3-4). Slower is cuter and clearer.
- One idea per line. Split speeches across clips with a reaction shot between speakers.
- End lines on an emotion (a question, a giggle, a gasp) — flat statements look dead on screen.

## 2. The Talking Prompt Formula (paste into every dialogue clip prompt)
```text
{SPEAKER} faces {listener/camera} and speaks with clear, natural lip movement
synced to the words, saying in a {VOICE PROFILE}: "{EXACT LINE}".
While speaking: natural blinking, small head nods on the important words,
eyebrows {raised / together / one up} with {emotion}, and a small
{hand / wing / paw} gesture on the word "{KEYWORD}".
{LISTENER} listens with mouth closed, nodding, then reacts: {giggle / gasp / clap / smile}.
The speaker finishes, mouth closes into a warm smile, short natural pause.
```
Why each piece matters: quotes give the model the exact words for voice + lips ·
face visible = lips can sync · gesture on a keyword = body agrees with voice ·
listener reacting = conversation feels alive · closing pause = clean edit point.

## 3. Camera for Talking
- Important line → **close-up**. Decision/laugh → **two-shot**. Listener's feeling → **reaction shot**.
- Never: talking while facing away, running, jumping, mouth covered, two speakers in one clip,
  or a wide shot for a whole conversation.

## 4. Voice Profiles (keep identical across the whole series)
| Character | Pitch | Speed | Texture | Catchphrase |
|-----------|-------|-------|---------|-------------|
| SpongeBob-type hero | High | Fast | Giggly, bubbly | (hero-specific) |
| Patrick-type friend | Low-medium | Slow | Sweet, simple | — |
| Peppa-type lead | Medium-high | Bouncy | Confident, cheerful | — |
| Chase-type leader | Medium | Clear, steady | Brave, kind | "Let's go!" style |
| Marshall-type comic | Medium | Excited bursts | Clumsy-funny | "I'm okay!" style |
| Doraemon-type helper | Warm medium | Gentle | Clever, caring | — |
| Pipo (original bird) | High, small | Quick, shy→brave | Repeats last word when scared | "Let's try!" |
| Momo (original rabbit) | Soft medium-high | Calm | Sweet, hums when thinking | "Oh my ears!" |
For named IPs, describe the voice in words (as above) — never ask the model to
imitate a real actor's voice.

## 5. Voice Production Workflows
- **A. Native (default):** line inside the prompt → model generates voice + lip-sync.
  Regenerate if any word is wrong or the hero's name is mispronounced. Max 2 regenerations
  per clip, then shorten the line and try once more.
- **B. TTS/AI-voice dub:** record/generate one audio file per line → note each line's
  seconds → generate clips of matching length with the mouth-movement prompt
  (line in quotes, "speaking silently" is NOT used — keep the line so lips match) →
  mute the clip's own audio in editing and lay your voice files on the dialogue track.
- **C. Human voice:** same as B; record in a quiet room, smile while recording — it shows in the voice.

## 6. Lip-Sync Rescue in Editing (when sync is slightly off)
- Shift the voice track ±2-6 frames until the biggest mouth-open matches the loudest vowel.
- Cut to the listener's reaction shot over the worst 0.5s (audiences never notice).
- Add the subtitle exactly on the first frame of speech — eyes forgive what ears + text confirm.
- If a clip's mouth moves with no line, cover with music/SFX or trim that part out.

## 7. Talking Checklist (per clip, before accepting a generation)
☐ One speaker only ☐ Face visible, mouth unobstructed ☐ Words exactly as scripted
☐ Blinking + one gesture + listener reaction present ☐ Ends with mouth-closed pause
☐ Voice matches the character's profile ☐ Subtitle text = spoken text, word for word
