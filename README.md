# CD Artwork Prompts

A curated collection of parametrized prompts for generating CD artwork using AI image generation tools.

## ⚠️ WARNING

**The intention of this repository is NOT to replace graphic designers' work.** Graphic designers are skilled professionals who create unique, tailored artwork that brings artistic vision and brand identity to life.

However, music producers sometimes need to send demos to record labels and require placeholder CD artwork for these submissions. This repository provides quick, temporary solutions for such scenarios until professional artwork can be commissioned.

**I strongly encourage supporting professional graphic designers for final, commercial releases.**

## Overview

This repository contains Jinja2-formatted prompt templates that can be customized with your specific song and artist details to generate various styles of CD artwork using AI image generation tools like DALL-E, Midjourney, Stable Diffusion, and others.

## Usage

Each `.jinja2` file contains a parametrized prompt template. To use them:

1. Choose a template that matches your desired style
2. Replace the parameters `{{ song_name }}` and `{{ artist_name }}` with your actual values
3. Use the resulting prompt with your preferred AI image generation tool

### Example

If you're using the `minimalist-modern.jinja2` template:
```jinja2
A minimalist CD cover for "{{ song_name }}" by {{ artist_name }}...
```

Replace with your details:
```
A minimalist CD cover for "Midnight Dreams" by Alex Rivera...
```

## Available Templates

### Contemporary Styles
- **minimalist-modern.jinja2** - Clean, contemporary minimalist designs
- **typography-focused.jinja2** - Text-centric, bold typography designs
- **gradient-colorful.jinja2** - Smooth color transitions and gradient blends

### Artistic Styles
- **abstract-artistic.jinja2** - Abstract art and experimental visuals
- **watercolor-painted.jinja2** - Soft watercolor painting aesthetic
- **surrealist-dreamlike.jinja2** - Surreal, dreamlike imagery
- **cartoon-illustrated.jinja2** - Playful cartoon and illustration style
- **collage-mixed-media.jinja2** - Mixed media and collage compositions

### Textured & Effects
- **grunge-textured.jinja2** - Rough, distressed, weathered textures
- **retro-vintage.jinja2** - 70s/80s inspired vintage aesthetics
- **glitch-digital.jinja2** - Digital corruption and glitch art effects

### 3D & Lighting
- **3d-rendered.jinja2** - High-quality 3D rendered graphics
- **neon-glowing.jinja2** - Luminous neon lights and glowing effects

### Photography
- **photography-based.jinja2** - Professional photographic imagery
- **nature-landscapes.jinja2** - Natural scenery and landscapes

### Geometric
- **geometric-patterns.jinja2** - Precise geometric shapes and patterns

## Contributing

Feel free to submit pull requests with new prompt templates or improvements to existing ones!

## License

MIT License - See [LICENSE](LICENSE) file for details

## Author

Eduardo J. Barrios  
eduardojbarriosgarcia@gmail.com  
GitHub: [@edujbarrios](https://github.com/edujbarrios)
