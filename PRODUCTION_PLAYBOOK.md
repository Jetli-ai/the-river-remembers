# Feature Production Playbook

A feature-length rewrite of the source Realistic Mini Dramas workflow. Keep its useful discipline—an immediate hook, legible action, consistent characters, motivated cuts, and original writing—while replacing its short-form production assumptions.

## 1. Locked production target

- Runtime: **47:21** total, with sequence timings in FILM_BLUEPRINT.md.
- Canvas: **landscape 16:9**, native **3840 × 2160 UHD**.
- Frame rate: **24 fps** throughout generation and edit where the chosen tool permits.
- Visual approach: photorealistic cinematic AI-assisted drama; natural skin texture, expressive but restrained performances, cinematic motivated light, readable geography, and continuity in fictional Aroko.
- Sound: clear dialogue, restrained original score, river and market ambience, focused effects, stereo edit master and 5.1 deliverable only if production tools support it.
- Titles: add in the editor, not inside generated frames. No generated subtitles, watermarks, logos, or legible accidental text.
- Delivery: high-bitrate 4K master plus a review copy. Preserve a separate project file and source assets.

The reference player showed an actual duration of 47:21. Its visible quality setting was Auto (480p), which does not establish its maximum upload resolution. UHD is this production’s requested target.

## 2. Feature-scale workflow

The source playbook targets 45-second vertical shorts, uses about 15 shots, generates 4- or 5-second clips, and exports Full HD. Do not stretch that recipe into hundreds of isolated clips. Build each sequence from an editorial plan with establishing, two-shot, close-up, and reaction coverage. Use longer generated clips for dialogue scenes when the chosen tool supports them; otherwise capture clean coverage and assemble pauses, eyelines, and reaction shots in the edit.

1. **Lock the screenplay.** Use the sequence map and story guardrails. Before generation, write each scene’s purpose, emotional turn, location, time of day, characters, and continuity dependencies.
2. **Create a visual bible.** Fix faces, wardrobe, jewelry, props, architecture, palette, weather, and river level. Make neutral character reference images for every adult character. Reuse the exact descriptions and approved references.
3. **Storyboard before generating.** Board all scenes in 16:9 with shot sizes and screen direction. Keep a map of the market, palace, riverbank, archive, and old gate so edits preserve geography.
4. **Generate in scene batches.** Finish reference images and footage for one location/continuity block at a time. Track scene and shot identifiers. Do not rely on an AI model to remember a face or prop across prompts.
5. **Review footage as editorial coverage.** Regenerate only material that breaks character identity, geography, action, or emotional continuity. Save alternate takes under distinct names. Never treat a rendered clip as final without inspection.
6. **Edit to the timed sequence map.** Use dialogue and action to hit the 47:21 target. A timing adjustment may move a sequence boundary by a few seconds, but the total master remains 47:21.
7. **Build original sound.** Keep speech intelligible, use location-specific ambience, and score emotional changes without telling the audience what to feel. Use only music, voices, and effects with production rights.
8. **Finish and inspect the master.** Export 3840 × 2160 at 24 fps if supported by source generation and the editor. Check the rendered file’s frame size, frame rate, audio sync, clipping, title-safe area, black frames, and final duration. If source footage is lower resolution, label any upscale accurately; do not describe it as native 4K.

## 3. Pacing and scene craft

- **Opening:** start inside the floodgate emergency. The audience should understand the immediate danger before it knows the history.
- **Scene turn:** each scene changes a decision, a relationship, or the audience’s understanding. Remove repeated explanations.
- **Dialogue:** let people finish thoughts. Use reaction shots and purposeful pauses; do not impose short-form 8-word lines or rapid cuts on every exchange.
- **Coverage:** establish where people stand before cutting to close-ups. Keep eyelines, screen direction, hand positions, water level, and prop placement consistent.
- **Performance:** natural gestures, small changes in breath and gaze, emotionally readable faces. No shouting in every scene.
- **Transitions:** use hard cuts for pressure, quiet visual matches for memory and repair. Avoid repetitive zooms, whip pans, and artificial slow motion.
- **Ending:** close on a changed relationship to the river and to public responsibility. No sequel bait or abrupt cliffhanger.

## 4. Character continuity bible

Use these descriptions as stable anchors. Add a wardrobe/state tag for each scene, never alter core appearance for convenience.

- **NIA ADEYEMI:** 30, deep brown skin, oval face, dark brown eyes, natural coiled hair tied in a low puff, a small scar through the left eyebrow; practical indigo work shirt, charcoal trousers, worn leather field satchel, brass measuring caliper. Calm, clear voice with warmth beneath precision.
- **CROWN PRINCE TAYO ADEREMI:** 32, dark skin, long face, close-cropped hair, neat short beard, thoughtful eyes; understated cream tunic with a narrow embroidered collar for public scenes, rolled-sleeve white shirt and dark trousers for field work, signet ring. Measured baritone that becomes more direct as he learns.
- **QUEEN MOTHER SERA:** 59, deep umber skin, high cheekbones, silver-threaded braids pinned at the nape, dark eyes; elegant rust and gold woven garments, one carved wooden pendant. Quiet, controlled contralto with a slight rasp.
- **BABA KUNLE:** 67, weathered dark skin, broad nose, salt-and-pepper close beard, gray hair beneath a simple cap; faded green work jacket and a brass gate key on a cord. Soft, grounded voice, precise with practical details.
- **CHIEF MINISTER BAKO:** 54, medium-dark skin, square jaw, shaved head, discreet mustache; charcoal formal coat with a green woven pocket square, plain black watch. Polished formal tenor with clipped phrasing.
- **MARA:** 28, dark brown skin, round face, natural shoulder-length twists, bright observant eyes; rust-red wrap top, patterned skirt or market apron, chalk tally pencil behind her ear. Warm, quick voice, dry humor.

## 5. Image prompt template

Use as a production prompt, adapting the shot rather than copying the example literally:

> Photorealistic cinematic live-action drama, natural skin texture, expressive restrained performance, motivated practical lighting, consistent fictional Aroko production design. Landscape 16:9, 3840 × 2160 composition, cinematic 24 fps project. [Shot size and lens feel]. [Exact character bible text for each visible person] in [wardrobe state]. [One clear action at the start of the frame]. [Precise location, time, weather, and river level]. [Screen positions, eyelines, and key props]. [Palette and light direction]. Keep hands and faces natural, architecture and costume consistent, grounded human proportions. No text, subtitles, logos, watermarks, or additional characters.

## 6. Video prompt template

> FEATURE / SCENE [##] / SHOT [##] — [short cue]. Photorealistic cinematic live-action drama, landscape 16:9, target UHD 3840 × 2160, 24 fps project. [Duration appropriate to the scene and tool]. Preserve the approved character references, exact wardrobe, props, screen direction, weather, and location. [Camera movement only if motivated]. [One principal action with a clear beginning, change, and end]. [Dialogue verbatim if needed; only the named speaker moves their mouth; others listen]. Natural performance, grounded motion, realistic water behavior, controlled exposure and focus. Sound: [specific ambience/effects; dialogue intelligible]. No generated text, captions, music unless explicitly directed, logos, or watermarks.

Do not ask a generator to produce the entire 47-minute film in one prompt. Use shot and scene prompts with continuity references and assemble them in an editor.

## 7. Sample prompts — opening scene

**S01 / image:** Photorealistic cinematic live-action drama. Landscape 16:9 composition, target 3840 × 2160. Wide view of the old floodgate at first light in fictional Aroko; dark river water pushes against a timber brace, three adult workers wait behind the safety line, one palace courier holds a sealed order. Low mist, slate-blue dawn, warm oil lanterns on wet stone, grounded West African-inspired masonry and woodwork. The workers are tense but composed; keep the gate, rope, and seal clearly readable as shapes without legible text. No titles or logos.

**S01 / video:** FEATURE / SCENE 01 / SHOT 01 — The order before the opening. Photorealistic cinematic live-action drama, landscape 16:9, target UHD 3840 × 2160, 24 fps project. Begin on the gate’s vibrating brace; a worker catches the rope as a palace courier presents the sealed order. Slow, deliberate push toward the undecipherable seal, then cut on the gatekeeper’s hand reaching for the lever. Natural water and wood sounds, one bell. No dialogue, generated text, captions, music, logos, or watermarks.

**S02 / image:** Photorealistic cinematic live-action drama, landscape 16:9, UHD composition. NIA ADEYEMI, 30, deep brown skin, oval face, dark brown eyes, natural coiled hair tied in a low puff, a small scar through the left eyebrow; practical indigo work shirt, charcoal trousers, worn leather field satchel, brass measuring caliper. At the dry edge of the river, she kneels to press a thumb into cracked silt beside the funeral cloth carried by two adult relatives. Warm late-afternoon light, restrained grief, market roofs soft in the background. No text or logos.

**S03 / video:** FEATURE / SCENE 03 / SHOT 04 — The map meets the market. Photorealistic cinematic live-action drama, 16:9, target UHD. In a council chamber, Crown Prince Tayo unrolls a canal route; Nia sets down her measured bank cross-section beside it. Begin on the paper, then move to a clean over-the-shoulder two-shot with clear screen direction. Tayo says evenly, “The route protects the reservoir.” Nia replies, “And puts the market in the flood.” Let the council react before cutting. Natural room tone; no other speakers, captions, or generated text.

## 8. Quality control and delivery

Before generation, confirm every sequence has a purpose and every scene has a consistent location, wardrobe, river state, and character reference. During editing, confirm dialogue is understandable, no character identity drifts within a scene, and cuts preserve physical geography.

Before final delivery, verify:
- total runtime: **47:21**;
- frame: **16:9 landscape**;
- encoded frame size: **3840 × 2160**;
- frame rate: **24 fps** (or an explicitly documented project-wide choice);
- audio sync, intelligibility, headroom, and clean start/end;
- no accidental text, watermarks, image glitches, black flashes, or mismatched props;
- an archive of the project file, generated sources, and rights/attribution notes.

If the chosen service cannot generate native 4K or clips long enough for a feature, use a production toolchain that can; do not promise that a short-form generator can export a feature. Any upscaling must be disclosed.

## 9. Adaptation map

| Short-form source rule | Feature rewrite |
|---|---|
| Vertical 9:16 | Landscape 16:9 |
| 45 seconds, about 15 shots | 47:21, 12 timed sequences and scene-level editorial coverage |
| 4–5 second generated clips | Scene-appropriate coverage; duration depends on the generation tool |
| Hook, escalation, twist, payoff in every short | One opening crisis, three-act character arc, earned disclosure and public resolution |
| At most 8 words per line | Natural dialogue with room for listening and response |
| Fast cuts and all dead air removed | Deliberate pacing; retain meaningful pauses and remove only repetition |
| Full HD export | Native 3840 × 2160 UHD delivery target, verified after rendering |
| Upload one mini drama | Assemble, mix, quality-check, and archive a single feature master |
