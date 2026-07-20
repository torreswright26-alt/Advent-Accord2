# Prompt Architecture

## Goal

Use concise, modular prompts preserving render language, identity, and scene intent without accumulating contradictory corrections.

## Load order

Master System Deck → Visual Constitution → relevant canon → approved reference → scene brief → task gates. Do not load unrelated history.

## Layers

- **Global foundation:** render language, anatomy, materials, clarity, prohibitions.
- **Entity identity:** anchors, medium behavior, architecture/materials, palette relationships, reference identity.
- **Scene performance:** action, expression, clothing, environment, camera, lighting, mood, narrative beat.
- **Negative controls:** modular negatives appropriate to the task, not an indiscriminate wall.

Template: `[Character/entity] [Action] [Environment] [Camera] [Mood] [Optional detail]`

For datasets and ComfyUI, specify subject count/type, pose/action, gaze when relevant, framing, visible anatomy, environment, and trigger words.

## Reference discipline

Use one strong canonical identity reference by default. Treat render references as style anchors and character references as identity anchors. Do not let manifestation effects overwrite the environment reference.

## Dedicated prompt output

When raw ComfyUI prompts are requested, return exactly two Markdown code blocks: `COMFYUI POSITIVE PROMPT` and `COMFYUI NEGATIVE PROMPT`, without filler unless explanation is requested.

## Supersession note

An earlier exploratory deck used clean digital line art and vibrant cell shading. Later Advent Accord-specific canon establishes premium semi-realistic painted manhwa / illustrative realism with painterly weathered materials and rejects anime/cartoony drift. The later constitution controls unless explicitly changed.
