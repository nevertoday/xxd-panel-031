# XXD Panel 031 | Meaning-Led Geometric Folk-Rubbing Production Prompt

## Runtime complete-canvas contract — highest priority

- `TOP_BOTTOM` and `LEFT_RIGHT` default to one complete finished generation using the current source as a high-fidelity edit/reference input. Do not pre-split the job into photographic and design halves.
- Top-bottom keeps the faithful source in approximately the upper 50% and performs this style transformation below; left-right uses the faithful source in approximately the left 50% and the transformation on the right. Unify both regions through colour, light, rhythm, typography, and meaning.
- `DESIGN_ONLY` and `WALLPAPER_PACK` use the complete canvas while the source remains an invisible identity/content reference. Recompose every wallpaper separately for its device.
- `FINAL CANVAS` means the ratio/pixels of the whole finished artwork and must be explicitly resolved before generation; never apply source dimensions silently. `DESIGN FRAME` is used only if a failed complete-canvas retry triggers deterministic composition fallback.
- Retry a failed complete canvas once against the failed constraint only. Scripted composition is allowed only after that retry still fails, when pixel-identical source preservation is explicitly required, when the active route cannot realise the canvas, or for lossless pixel calibration.

### Model priority and credentials

- **Prefer GPT Image 2.** When GPT Image 2 is available through the current built-in image tool or a configured compatible route, use it first for the high-fidelity reference/edit and complete-canvas generation required by this prompt.
- Also support Seedance 5.0 Pro, Nano Banana Pro (Gemini Image Pro), Nano Banana 2 (Gemini Image Flash), or another compatible bitmap model only when the actual route can preserve the source, realise the whole finished canvas, render the target-language text, and accept the multiple references needed by a linked wallpaper pack.
- An alternative model changes only the generation route. It must not change this prompt's modes, canvas, source visibility, copy, locale, wallpaper relationship, or complete-canvas-first / composition-fallback-only logic. Do not silently downgrade a hard requirement.
- If no suitable route is available, ask the user to enable an image-generation tool or provide an API key. User-provided credentials may be used for the current task, but never echo, display, log, or expose their value in chat, prompts, or diagnostics. Do not persist them or modify global route configuration unless explicitly requested.
- Judge availability by actual image capability, not by a provider name or one missing environment variable.

Process only the one source photograph explicitly supplied for this current task. Lock the principal subject or inseparable relation, core proportion, contour flow, pose, action, function, relational distance, colour character, and any supported cultural property. Preserve at least three source-specific recognition cues. Never borrow symbols, geometry, folklore motifs, ink palettes, copy, or composition from old outputs, samples, or another input.

## Meaning first, one motif only

Understand what the photograph means before translating what it contains. Determine one supported core meaning, cultural attribute, or emotional relation, then retain one principal visual motif and only the few supporting forms genuinely necessary to carry that narrative. Do not translate every photographed element or add generic “traditional” decoration.

Use silhouette, negative space, local enlargement, form merging, symbolic reduction, and selective crop so the motif stays recognisable while expressing what lies behind it. Every visible form must have a traceable source, semantic meaning, and structural duty. Delete anything that does not strengthen understanding.

## One source-derived geometric parent

Derive one geometric parent from the subject's own structure: a circle, square, triangle, arc, axis, or repeated proportion. Bind motif, helpers, typography, and whitespace to that parent through alignment, tangency, common axis, nesting, mirroring, proportional progression, or boundary crop.

The layout may be eccentric, asymmetric, cropped, distributed, or boundary-crossing, but it must share one structural logic and one clear centre of gravity. From afar, geometry and hierarchy read immediately; up close, print wear and meaningful detail appear. Reject random scatter, equal-weight placement, unrelated geometry, decorative accumulation, and multiple competing systems.

## Rough print matter inside crisp order

Mix woodblock rubbing, dry-brush screenprint, and old catalogue printing. Broken ink, abrasion, exposed paper, uneven density, and restrained registration shift belong mainly inside the graphic forms. Essential silhouette, geometric boundary, axis, tangent, and layout remain crisp and exact.

Use bright light paper, one deep ink for the visual skeleton, and one or two theme inks derived from the current source's most recognisable and spirited colours. Build hierarchy through area ratio, value, selective overprint, and negative space. Reject fixed red-black-beige folklore palettes, decorative multicolour, muddy faux ageing, dissolving contours, random grunge, literal material collage, realistic modelling, vector sterility, and 3D.

## Copy follows the same geometry

Obey the resolved automatic, exact-user, or text-free copy mode and target language or locale. Preserve exact user wording verbatim. Automatic copy distils one concise title from the source's supported theme, meaning, cultural property, emotional relation, or symbolic action. Add zero to two micro-notes only when they carry real information. Never fabricate heritage, idioms, provenance, dates, numbers, or locations.

Typography is a subordinate information layer inside the same geometric system. Align, nest, interweave, or crop it along an axis, tangent, negative shape, or motif boundary. Use native crisp editorial type with restrained catalogue-print wear. Reject decorative ethnic fonts, faux seals, giant headlines, detached captions, UI labels, and pseudo-foreign writing. In text-free mode render no text or pseudo-text.

## Mode and acceptance


Hard gate: at least three source cues; one supported meaning; one core motif and only narratively necessary helpers; one source-derived geometric parent visibly governing motif, type, and whitespace; crisp silhouette and negative space; bright paper, one deep structural ink, and one or two source theme inks; internal woodblock-rubbing and dry-screenprint wear with precise outer geometry; native subordinate copy when requested; no literal scene translation, generic folklore motif, random ornament, equal-weight layout, fixed folklore palette, material collage, realistic illustration, dirty filter, 3D, photo fragment, or pseudo-text.

If any hard condition fails, correct the generated asset. Never fake the artwork with programmatic drawing, SVG, HTML, Canvas, or a post-composited type overlay.
