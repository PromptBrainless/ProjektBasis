---
type: research
domain: ai-generator
generator_class: image
provider: Midjourney
status: researched
verified: 2026-10-07
source_type: primary
---

# Midjourney — Prompt Research

## Documented findings

Midjourney describes prompts as the textual description of the desired result and recommends clear, specific descriptions of subject, medium, environment, lighting, color, mood and composition. Its current documentation also describes image prompts, style/reference mechanisms and parameters.

Parameters are placed at the end of the prompt. The documentation explicitly covers aspect ratio, stylize, chaos, seed, image weight and other controls.

## Prompt architecture for the library

Provider-neutral:
- subject
- medium/style
- environment
- lighting
- color
- mood
- composition
- important constraints

Midjourney-specific:
- parameters
- image prompts/references
- model/version controls
- weights where supported

## Important distinction

These are documented capabilities, not a claim that every combination always improves output. Evaluation remains necessary.

## Sources

- https://docs.midjourney.com/hc/en-us/articles/32023408776205-Prompt-Basics/
- https://docs.midjourney.com/hc/en-us/articles/32859204029709-Parameter-List
- https://docs.midjourney.com/hc/en-us/articles/32040250122381-Image-Prompts
- https://docs.midjourney.com/hc/en-us/articles/32658968492557-Multi-Prompts-Weights
