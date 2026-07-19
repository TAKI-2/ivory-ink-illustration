---
name: ivory-ink-illustration
description: Generate polished conceptual editorial illustrations from a theme using bold irregular black hand-drawn outlines, warm ivory forms, muted flat color blocks, simple visual metaphors, and generous negative space. Use for presentation covers and section dividers, article illustrations, report or document covers, posters, social graphics, or requests for minimal hand-drawn concept art with low-saturation colors.
---

# Ivory Ink Illustration

Generate the finished raster illustration with the built-in image-generation tool. Do not stop after writing a prompt unless the user explicitly asks for a prompt only.

Read [references/style-guide.md](references/style-guide.md) before generating. Apply its visual rules consistently without naming or copying any particular company, artist, or existing artwork.

## Workflow

1. Extract the theme, intended use, orientation, required objects, mood, and desired negative space.
2. If the user supplies only a theme, infer a single visual metaphor and use a 4:3 landscape editorial composition with moderate negative space.
3. If the use is stated, select the matching format:
   - Presentation: 16:9 landscape; place the subject off-center and reserve a clean title area.
   - Article or report illustration: 4:3 landscape; use a balanced central composition.
   - Portrait cover or poster: 3:4 portrait; keep the upper third relatively quiet for typography.
   - Social graphic: 1:1 square; use one strong central silhouette.
4. Reduce the idea to one main metaphor, one focal subject, and at most three supporting objects. Treat a simplified city or landscape as one grouped supporting element. Prefer conceptual clarity over literal completeness.
5. Set a detail budget before prompting: preserve broad silhouettes; omit repeated windows, leaves, icons, map lines, interface elements, and decorative marks unless they are essential to the metaphor.
6. Make conceptually different actors visually distinct. In particular, represent AI or another non-human system through an unmistakably non-human abstract structure, tool, or material behavior rather than a second generic person or a humanoid robot.
7. Compose a concise production prompt using the required style, composition, palette, texture, and exclusions from the style guide.
8. Call the built-in image-generation tool immediately. For multiple distinct illustrations, make one generation call per illustration.
9. Inspect the result for conceptual clarity, bold irregular linework, warm ivory forms, muted palette, usable negative space, and absence of unwanted text or branding. If a major criterion fails, regenerate once with one targeted correction.
10. Present the finished image. Briefly state the chosen metaphor and intended layout only when it helps the user evaluate the result.

## Interpretation Rules

- Preserve any explicit subject, composition, or color request from the user.
- Ask a question only when a missing requirement would materially change the result. Otherwise infer and proceed.
- Create a poetic but immediately readable metaphor. Avoid a collage of unrelated symbols.
- Keep the image legible at slide-thumbnail size.
- Leave title space empty. Do not render placeholder typography.
- If the user requests exact in-image text, preserve it verbatim and keep it minimal.
- Treat reference images as guidance unless the user explicitly identifies one as an edit target.

## Output Rules

- Generate a raster image rather than SVG, HTML, or a text-only prompt.
- Do not include logos, watermarks, signatures, or brand marks.
- Do not claim exact replication of a named brand or artist. Translate references into the general visual system defined in the style guide.
- When the output is intended for a project, save the selected image into the project before finishing.
