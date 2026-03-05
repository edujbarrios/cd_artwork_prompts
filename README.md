# CD Artwork Prompts

A curated collection of parametrized prompts for generating CD artwork using AI image generation tools.

## ⚠️ WARNING

**The intention of this repository is NOT to replace graphic designers' work.** Graphic designers are skilled professionals who create unique, tailored artwork that brings artistic vision and brand identity to life.

However, music producers sometimes need to send demos to record labels and require placeholder CD artwork for these submissions. This repository provides quick, temporary solutions for such scenarios until professional artwork can be commissioned.

**Make sure to support professional graphic designers for final, commercial releases.**

## Overview

This repository contains Jinja2-formatted prompt templates organized by visual style. Each style has its own folder containing both Spanish (`spanish.jinja2`) and English (`english.jinja2`) versions. Customize them with your specific song and artist details to generate various styles of CD artwork using AI image generation tools like DALL-E, Midjourney, Stable Diffusion, and others.

## Structure

```
cd_prompt/
├── minimalist-modern/
│   ├── spanish.jinja2
│   └── english.jinja2
├── neon-glowing/
│   ├── spanish.jinja2
│   └── english.jinja2
└── ... (one folder per style)
```

## Usage

Each folder contains prompt templates in both Spanish and English:

1. **Choose a visual style** that matches your desired aesthetic
2. **Select your language** - use `spanish.jinja2` or `english.jinja2`
3. **Replace the parameters** `{{ song_name }}` and `{{ artist_name }}` with your actual values
4. **Use the resulting prompt** with your preferred AI image generation tool

### Example

From `minimalist-modern/english.jinja2`:
```jinja2
A minimalist modern CD cover design for "{{ song_name }}" by {{ artist_name }}...
```

Replace with your details:
```
A minimalist modern CD cover design for "Midnight Dreams" by Alex Rivera...
```

## Available Templates

Each folder contains both Spanish and English versions (`spanish.jinja2` and `english.jinja2`):

### Contemporary Styles
- **minimalist-modern/** - Clean, contemporary minimalist designs
- **typography-focused/** - Text-centric, bold typography designs
- **gradient-colorful/** - Smooth color transitions and gradient blends

### Artistic Styles
- **abstract-artistic/** - Abstract art and experimental visuals
- **watercolor-painted/** - Soft watercolor painting aesthetic
- **surrealist-dreamlike/** - Surreal, dreamlike imagery
- **cartoon-illustrated/** - Playful cartoon and illustration style
- **collage-mixed-media/** - Mixed media and collage compositions

### Textured & Effects
- **grunge-textured/** - Rough, distressed, weathered textures
- **retro-vintage/** - 70s/80s inspired vintage aesthetics
- **glitch-digital/** - Digital corruption and glitch art effects

### 3D & Lighting
- **3d-rendered/** - High-quality 3D rendered graphics
- **neon-glowing/** - Luminous neon lights and glowing effects

### Photography
- **photography-based/** - Professional photographic imagery
- **nature-landscapes/** - Natural scenery and landscapes

### Geometric
- **geometric-patterns/** - Precise geometric shapes and patterns

## Contributing

Feel free to submit pull requests with new prompt templates or improvements to existing ones!

## Author

Eduardo J. Barrios  
eduardojbarriosgarcia@gmail.com  
GitHub: [@edujbarrios](https://github.com/edujbarrios)
