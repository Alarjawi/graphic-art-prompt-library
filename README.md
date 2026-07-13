# Graphic Art Prompt Library

Organized reference for creating stronger AI image prompts based on graphic art movements, verified visual language, and reusable prompt structures.

## Purpose

This repository helps turn vague style requests into precise prompts. It combines:

- historical art and design movements
- verified visual traits
- prompt templates for common graphic design outputs
- negative prompt guidance
- source notes for checking accuracy

## How To Use

1. Pick a movement from `movements/`.
2. Copy its prompt formula.
3. Add your subject, format, audience, and constraints.
4. Use a template from `templates/` when the output type matters.
5. Check `sources.md` before adding new style claims.

## Prompt Formula

```text
[subject]
+ [graphic art movement]
+ [composition system]
+ [line/shape language]
+ [color palette]
+ [typography or layout cues]
+ [print/material texture]
+ [lighting/rendering limits]
+ [negative prompt]
```

## Quality Rule

A prompt is good when it gives the model visual instructions, not just a famous style name.

Weak:

```text
poster in Bauhaus style
```

Stronger:

```text
editorial poster for a design conference, Bauhaus-inspired geometric composition, primary red yellow blue with black accents, flat circles and rectangles, functional sans-serif typography, asymmetrical but balanced layout, screenprint texture, no photorealism, no decorative flourishes
```

## Repository Map

- `prompt-system.md`: the core method for building better prompts
- `sources.md`: trusted and community sources
- `movements/`: movement-specific prompt notes
- `templates/`: reusable prompt templates by design task
- `examples/`: tested prompt patterns and comparisons
