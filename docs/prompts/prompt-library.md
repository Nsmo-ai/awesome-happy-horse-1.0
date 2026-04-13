# Prompt Library

Last checked: `2026-04-13`

This page collects a small, source-aware set of prompts and prompt patterns related to Happy Horse. The goal is usable curation, not prompt spam.

## Curated Prompt 1: Cave Flashlight Cinematic

- **Prompt**

```text
A flashlight beam exploring a cave system, illuminating wet limestone formations. The light catches crystalline calcite deposits that glitter and flash. Where the beam passes through shallow standing water, it creates bright caustic patterns on the submerged floor. Stalactites cast long, swinging shadows as the flashlight moves. Audio: Dripping water echoing, footsteps on wet rock, breathing in enclosed space.
```

- **Intended effect:** Atmosphere, moving light, textured surfaces, and audio-visual immersion.
- **Observation:** Strong for cinematic environment testing because it stresses lighting, motion, and scene texture at the same time.
- **Source:** Derived cinematic evaluation case aligned with current [Artificial Analysis Text to Video leaderboard](https://artificialanalysis.ai/video/leaderboard/text-to-video)
- **Last checked:** `2026-04-13`

## Curated Prompt 2: Graduation Banner Chaos

- **Prompt**

```text
A massive "CONGRATULATIONS GRADUATES" banner being unfurled across a university building by maintenance workers on the roof. The wind catches it mid-unfurl, turning it into a sail that nearly lifts one worker off their feet. Coworkers grab him, everyone laughs, and the banner finally drops into place. Below, students start taking selfies immediately. Audio: Wind gusting, workers shouting and laughing, distant cheering.
```

- **Intended effect:** Multi-subject coordination, motion comedy, readable action sequence, and integrated audio cues.
- **Observation:** Useful for evaluating whether narrative action remains coherent across several moments in one short sequence.
- **Source:** Derived multi-beat continuity case aligned with current public comparison chatter on [Angry Tom comparison post on X](https://x.com/AngryTomtweets/status/2041837603100471308)
- **Last checked:** `2026-04-13`

## Derived Template 3: High-Converting Product Visual Sequence

- **Prompt**

```text
A premium product hero sequence for a modern SaaS landing page: crisp lighting, high contrast, clean background, slow cinematic reveal, subtle camera movement, strong composition, polished materials, emotionally resonant visual tone, optimized for conversion-focused web design.
```

- **Intended effect:** Translate the strongest public product-positioning language into a reusable prompt skeleton.
- **Observation:** Useful when you want a reusable commercial prompt without drifting into generic AI aesthetic language.
- **Source:** Derived from the current public product-facing wording and benchmark-facing aesthetic discussion.
- **Last checked:** `2026-04-13`

## Derived Template 4: Mirrorless Kitchen Product Reveal

- **Prompt**

```text
A premium espresso machine on a stone countertop in a sunlit modern kitchen. The camera starts close on brushed metal details, then slowly pulls back as steam rises from a fresh shot. Soft natural reflections move across the polished surfaces. Audio: Low ambient kitchen hum, ceramic cup placement, espresso extraction, subtle steam.
```

- **Intended effect:** Product realism, reflective materials, restrained camera movement, and premium lifestyle framing.
- **Observation:** Valuable for testing whether the model preserves product geometry while still feeling cinematic.
- **Source:** Derived from the public product-facing narrative around polished output and high-conversion visuals.
- **Last checked:** `2026-04-13`

## Derived Template 5: Multilingual Spokesperson Delivery

- **Prompt**

```text
A confident spokesperson in a bright studio delivers a short launch announcement directly to camera. Natural lip movement, calm hand gestures, soft background depth, subtle camera drift, clean wardrobe, and polished lighting. Audio: Clear spoken delivery, light room tone, no background music.
```

- **Intended effect:** Evaluate direct-to-camera presence, lip-sync expectations, and clean marketing communication.
- **Observation:** High-value test for any model discussed in audio-enabled leaderboard contexts because it exposes awkward mouth motion and timing errors quickly.
- **Source:** Derived from the audio-enabled benchmark framing in [Artificial Analysis Text to Video leaderboard](https://artificialanalysis.ai/video/leaderboard/text-to-video)
- **Last checked:** `2026-04-13`

## Derived Template 6: Storefront-to-Checkout Storybeat

- **Prompt**

```text
A customer notices a beautifully arranged storefront display, walks inside, picks up a featured product, and reaches the checkout counter in one fluid sequence. Warm lighting, natural crowd motion in the background, stable subject continuity, and believable retail pacing. Audio: Door chime, soft foot traffic, quiet register sounds, low conversation bed.
```

- **Intended effect:** Test multi-beat narrative continuity, subject persistence, and commercial storytelling.
- **Observation:** Useful when a single hero shot is too easy and you need to see whether the model can hold a simple story together.
- **Source:** Derived from the commercial storytelling angle in the current public product-facing narrative plus multi-shot public comparison discussion.
- **Last checked:** `2026-04-13`

## Derived Template 7: Image-to-Video Character Hold

- **Prompt**

```text
Animate a still portrait of a traveler standing at a train platform. Keep facial identity stable while adding natural blinking, subtle wind movement in hair and clothing, shifting platform light, and a train arriving softly in the background. Audio: Platform ambience, distant announcement, rail movement, light wind.
```

- **Intended effect:** Evaluate identity retention and controlled animation in an image-to-video setup.
- **Observation:** Valuable because it isolates a common failure mode: strong motion at the cost of subject identity drift.
- **Source:** Derived from the current image-to-video benchmark relevance in [Artificial Analysis Image to Video leaderboard](https://artificialanalysis.ai/video/leaderboard/image-to-video)
- **Last checked:** `2026-04-13`
