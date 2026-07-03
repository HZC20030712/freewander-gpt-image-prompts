# FreeWander GPT Image Prompts

> A curated collection of GPT Image prompts, example outputs, and structured
> metadata for product photography, poster design, cinematic scenes, and more.

[View on FreeWander](https://freewander.com/gallery?utm_source=github&utm_medium=repo&utm_campaign=gpt-image-prompts)

## Data Overview

| Metric | Value |
|---|---|
| Repository Stage | Phase 1 |
| Asset Scope | External public assets only |
| Model | GPT Image |
| Schema Version | v1.0 |
| Last Updated | 2026-07-03 |

## 🔥 Featured Prompts

> ⭐ Hand-picked prompts from our collection

### No. 1: product-photography

<img src="https://images.meigen.ai/tweets/2017420332458774791/0.jpg" width="600" alt="Featured Image 1">

#### 📝 Prompt

```text
{
  "master_prompt": {
    "global_settings": {
      "resolution": "8K ultra-high-definition",
      "aspect_ratio": "3:4 vertical",
      "style": "hyper-realistic AI-edited commercial product photography",
      "sharpness": "extreme clarity, micro-detail visibility",
      "lighting_quality": "cinematic studio lighting with controlled highlights and shadows",
      "motion_freeze": "high-speed capture, frozen splashes and particles",
      "noise": "none",
      "artifacts": "none"
    },

"module_1_image_1_style": {
      "subject": {
        "type": "plastic protein drink bottle",
        "color": "deep matte blue",
        "surface_details": "condensation droplets across entire bottle",
        "label_text_visible": [
          "milk & yogurt",
          "mock up",
          "protein",
          "SEPARATED SHADOWS"
        ]
      },
      "pose_and_orientation": {
        "position": "slightly tilted to the right",
        "angle": "three-quarter view",
        "motion_feel": "dynamic, leaning into splash"
      },
      "liquid_and_motion": {
        "liquid_color": "white and light beige milk mixture",
        "texture": "smooth, creamy, fluid",
        "motion": "swirling splash rising around bottle base and sides"
      },
      "floating_elements": {
        "blueberries": "whole and halved blueberries at different depths",
        "mint_leaves": "small green leaves with visible veins",
        "droplets": "milk droplets and spheres suspended mid-air"
      },
      "background": {
        "color_gradient": "dark blue to warm amber",
        "bokeh": "soft circular light particles scattered throughout"
      },
      "surface_and_reflection": {
        "base": "matte ground with light liquid pooling",
        "shadow_style": "soft separated shadow under bottle"
      }
    },
"module_2_image_2_style": {
      "subject": {
        "type": "metal coffee can",
        "color": "warm gold",
        "surface_details": "heavy condensation with visible droplets",
        "branding_text_visible": [
          "NESCAFÉ",
          "Latte",
          "NEW LOOK",
          "ICED COFFEE WITH MILK",
          "SUGAR AND SWEETENER OPTIONAL"
        ]
      },
      "pose_and_orientation": {
        "position": "upright, centered",
        "angle": "front-facing",
        "presence": "hero product stance"
      },
      "liquid_and_motion": {
        "liquid_color": "coffee and milk blend",
        "motion": "splash erupting from base",
        "droplet_behavior": "fine droplets scattered outward"
      },
      "floating_elements": {
        "coffee_beans": "whole roasted beans floating around can",
        "steam": "thick swirling steam rising upward",
        "embers": "tiny glowing particles in background"
      },
      "background": {
        "color_palette": "deep brown, amber, gold",
        "atmosphere": "warm, smoky, intense"
      },
      "surface_and_reflection": {
        "base": "wet surface with liquid splash crown",
        "reflection_quality": "subtle reflective highlights"
      }
    }
```

---

### No. 2: product-photography

<img src="https://images.meigen.ai/tweets/2048748266293190833/0.jpg" width="600" alt="Featured Image 2">

#### 📝 Prompt

```text
Low-angle fashion campaign photograph of a confident model holding a large [product name] very close to the camera, exaggerated perspective with the hand and product dominating the foreground, full-body pose visible in the background, wide stance, dynamic posture, clean pure white studio background, high-key lighting, sharp focus on product, slight depth of field on the model, bold colorful outfit with strong contrast tones, modern beauty advertising aesthetic, ultra-clean composition, commercial studio photography, glossy packaging detail visible, crisp shadows
```

---

### No. 3: product-photography

<img src="https://images.meigen.ai/tweets/2046682439985082441/0.jpg" width="600" alt="Featured Image 3">

#### 📝 Prompt

```text
Create a polished multi-page (multiple images) brand kit for a company called [YOYOYO]. The brand should feel playful, futuristic, vibrant, and design-forward, blending the energy of a toy-inspired product with the sophistication of a premium creative tech brand. Use a bold, experimental visual identity with bright color, clean geometry, modern typography, dynamic motion cues, and slightly surreal imagery. The overall mood should feel inventive, youthful, rhythmic, tactile, and high-concept, with a balance of fun consumer product culture, fashionlike presentation, and contemporary digital design.

Include a sense of product obsession, visual experimentation, packaging exploration, editorial photography, immersive retail, and cross-platform brand application. Make it feel like a confident, contemporary brand world that is both accessible and art-directed, with strong graphic cohesion and a premium creative-studio aesthetic.
```

---

## Quick Start

1. Browse the manifest in `data/index.json`
2. Open category files under `data/gpt-image/`
3. Copy prompts into FreeWander or your own workflow

```bash
git clone https://github.com/HZC20030712/freewander-gpt-image-prompts.git
cd freewander-gpt-image-prompts
```

## Repository Structure

```text
.
├── ATTRIBUTION.md
├── CHANGELOG.md
├── LICENSE
└── data/
    ├── index.json
    └── gpt-image/
```

## How to Use

### Method 1: Browse JSON

Read structured prompt entries from `data/index.json` and category files.

### Method 2: Continue on FreeWander

Use the same prompt flow on FreeWander:

- [Browse gallery](https://freewander.com/gallery?utm_source=github&utm_medium=readme&utm_campaign=gpt-image-prompts)
- [Generate images](https://freewander.com/generate?utm_source=github&utm_medium=repo&utm_campaign=gpt-image-prompts)

## License & Attribution

- This repository is intended to ship under the MIT License.
- Phase 1 only accepts externally sourced public assets with compatible low-risk
  licenses.
- Full source and attribution rules are tracked in `ATTRIBUTION.md`.

## Current Status

This staging copy is the local initialization pack prepared before GitHub push.
The public repository should only be created after:

1. GitHub authentication is restored
2. Source repositories are license-verified
3. Initial prompt files are synced into `data/gpt-image/`

## Continue on FreeWander

FreeWander is the downstream experience for browsing, filtering, and generating
with these prompts.

- [Gallery](https://freewander.com/gallery?utm_source=github&utm_medium=readme&utm_campaign=gpt-image-prompts)
- [Generate](https://freewander.com/generate?utm_source=github&utm_medium=repo&utm_campaign=gpt-image-prompts)
