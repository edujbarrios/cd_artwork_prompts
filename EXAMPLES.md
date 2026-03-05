# Ejemplos de Uso / Usage Examples

## Español

### Cómo usar los templates

1. Elige un estilo visual del repositorio
2. Abre la carpeta del estilo elegido
3. Usa `spanish.jinja2` para prompts en español o `english.jinja2` para inglés
4. Reemplaza `{{ song_name }}` y `{{ artist_name }}` con tu información
5. Usa el prompt resultante en tu herramienta de IA favorita (DALL-E, Midjourney, Stable Diffusion, etc.)

### Ejemplo con neon-glowing/spanish.jinja2

**Template original:**
```
Una portada de CD con neón brillante para "{{ song_name }}" de {{ artist_name }}...
```

**Prompt personalizado:**
```
Una portada de CD con neón brillante para "Sueños de Medianoche" de Alex Rivera. Efecto de luces de neón luminosas con bordes brillantes, colores eléctricos (rosa fuerte, cian, púrpura, azul eléctrico). Fondo oscuro para realzar el brillo, rastros de luz, estética LED. Inspiración de letreros de neón cyberpunk, colores fluorescentes vibrantes, energía urbana nocturna. Arte digital moderno con intensa saturación de color y efectos de bloom. Formato cuadrado de portada de álbum.
```

### Ejemplo con cartoon-illustrated/spanish.jinja2

**Template original:**
```
Una portada de CD estilo cartoon para "{{ song_name }}" de {{ artist_name }}...
```

**Prompt personalizado:**
```
Una portada de CD estilo cartoon para "Ritmo Tropical" de Los Soneros. Diseño ilustrado con personajes divertidos, contornos audaces, colores vibrantes. Estética de cómic o animación con arte expresivo. Calidad dibujada a mano con pulido digital, elementos ilustrados divertidos y enérgicos. Estilo de ilustración moderna con acabado profesional, diseño de personajes creativos o escenas caprichosas. Arte de álbum en formato cuadrado, llamativo y colorido.
```

---

## English

### How to use the templates

1. Choose a visual style from the repository
2. Open the folder of your chosen style
3. Use `spanish.jinja2` for Spanish prompts or `english.jinja2` for English
4. Replace `{{ song_name }}` and `{{ artist_name }}` with your information
5. Use the resulting prompt in your favorite AI tool (DALL-E, Midjourney, Stable Diffusion, etc.)

### Example with watercolor-painted/english.jinja2

**Original template:**
```
A watercolor-painted CD cover for "{{ song_name }}" by {{ artist_name }}...
```

**Customized prompt:**
```
A watercolor-painted CD cover for "Summer Breeze" by Emma Lane. Soft watercolor painting style with flowing colors, organic bleeds, delicate brush strokes. Artistic hand-painted aesthetic with subtle texture and transparency. Ethereal dreamy quality with gentle color transitions. Traditional art meets digital refinement, elegant and sophisticated. Beautiful artistic interpretation with professional watercolor technique. Square format album artwork with fine art gallery quality.
```

### Example with geometric-patterns/english.jinja2

**Original template:**
```
A geometric-patterns CD cover for "{{ song_name }}" by {{ artist_name }}...
```

**Customized prompt:**
```
A geometric-patterns CD cover for "Pulse" by Digital Echoes. Precise geometric shapes, repeating patterns, mathematical composition. Sacred geometry, tessellations, symmetrical designs, or dynamic angular arrangements. Clean lines with perfect precision, contemporary graphic design. Bauhaus or constructivist influences, modern pattern design with optical interest. Professional geometric art with striking visual rhythm. Square format album artwork.
```

---

## Tips / Consejos

### Español
- Cada carpeta contiene versiones en español e inglés del mismo estilo
- Ajusta el prompt agregando detalles específicos sobre colores o elementos que quieres ver
- Puedes combinar elementos de diferentes estilos en un solo prompt
- Experimenta con diferentes herramientas de IA para obtener resultados variados
- Especifica "4K", "alta resolución" o "ultra detallado" para mejor calidad
- Añade detalles sobre ambiente: "nostálgico", "futurista", "sombrío", etc.

### English  
- Each folder contains Spanish and English versions of the same style
- Adjust the prompt by adding specific details about colors or elements you want to see
- You can combine elements from different styles in a single prompt
- Experiment with different AI tools to get varied results
- Specify "4K", "high resolution" or "ultra detailed" for better quality
- Add details about mood: "nostalgic", "futuristic", "moody", etc.

---

## Folder Structure / Estructura de Carpetas

```
├── 3d-rendered/
├── abstract-artistic/
├── cartoon-illustrated/
├── collage-mixed-media/
├── geometric-patterns/
├── glitch-digital/
├── gradient-colorful/
├── grunge-textured/
├── minimalist-modern/
├── nature-landscapes/
├── neon-glowing/
├── photography-based/
├── retro-vintage/
├── surrealist-dreamlike/
├── typography-focused/
└── watercolor-painted/
```

Each folder contains:
- `spanish.jinja2` - Versión en español
- `english.jinja2` - English version
