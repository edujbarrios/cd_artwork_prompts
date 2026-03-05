# Instrucciones para subir el repositorio a GitHub

## Pasos:

1. **Crea un nuevo repositorio en GitHub:**
   - Ve a https://github.com/new
   - Nombre del repositorio: `cd-artwork-prompts` (o el nombre que prefieras)
   - Descripción: "Curated collection of AI prompts for generating CD artwork - organized by visual style, with Spanish & English versions"
   - Selecciona: **Public** (para que otros puedan verlo)
   - **NO** marques "Initialize this repository with a README" (ya tienes archivos locales)
   - Click en "Create repository"

2. **Conecta tu repositorio local con GitHub:**
   Ejecuta estos comandos en la terminal (reemplaza `edujbarrios` con tu username si es diferente):

   ```powershell
   git remote add origin https://github.com/edujbarrios/cd-artwork-prompts.git
   git branch -M main
   git push -u origin main
   ```

3. **¡Listo!** Tu repositorio estará disponible en:
   `https://github.com/edujbarrios/cd-artwork-prompts`

---

## Si prefieres usar SSH en lugar de HTTPS:

```powershell
git remote add origin git@github.com:edujbarrios/cd-artwork-prompts.git
git branch -M main
git push -u origin main
```

---

## Opcional: Añadir topics/tags al repositorio

Una vez creado el repositorio en GitHub, puedes añadir estos tags para mejor descubrimiento:

- `ai-prompts`
- `cd-artwork`
- `album-cover`
- `music-production`
- `midjourney`
- `dall-e`
- `stable-diffusion`
- `jinja2`
- `ai-art`
- `generative-art`
- `bilingual`
- `spanish`
- `english`

Para añadirlos:
1. Ve a tu repositorio en GitHub
2. Click en el ⚙️ (settings icon) junto a "About"
3. Añade los topics en "Topics"
4. Click "Save changes"

---

## Estructura del Repositorio

La estructura actual del repositorio es:

```
cd_prompt/
├── README.md
├── LICENSE
├── EXAMPLES.md
├── GITHUB_INSTRUCTIONS.md
├── .gitignore
├── 3d-rendered/
│   ├── spanish.jinja2
│   └── english.jinja2
├── abstract-artistic/
│   ├── spanish.jinja2
│   └── english.jinja2
├── cartoon-illustrated/
│   ├── spanish.jinja2
│   └── english.jinja2
└── ... (16 folders in total, each with spanish & english versions)
```

Cada estilo visual tiene su propia carpeta con dos archivos:
- `spanish.jinja2` - Prompt en español
- `english.jinja2` - Prompt in English
