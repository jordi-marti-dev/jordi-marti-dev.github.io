# jordimarti.dev — Developer Portfolio

Personal portfolio of **Jordi Martí**, Industrial Engineer, inventor and Python developer.  
Hosted on GitHub Pages · [jordi-marti-dev.github.io](https://jordi-marti-dev.github.io)

---

## About

Static portfolio built with plain HTML and CSS — no frameworks, no build step.  
Features a dedicated project page for the **Projecte Cangur**, a biomimetic medical device for premature infants registered as a Utility Model (ES 1260772 Y, OEPM 2021).

## File structure

```
/
├── index.html              ← Main portfolio page
├── style.css               ← Shared design system (variables, components)
├── img/
│   ├── cangur-prototip.jpg ← Physical prototype photo
│   └── cangur-render.jpg   ← 3D render (full system)
└── projecte_cangur/
    └── index.html          ← Dedicated Cangur Project page
```

## Technologies

- HTML5 · CSS3 (custom properties, grid, flexbox)
- IBM Plex Mono + IBM Plex Sans (Google Fonts)
- Vanilla JavaScript — bilingual system (CA / EN) via `data-i18n` attributes
- GitHub Pages (static hosting, no build required)

## Bilingual system

Language preference (Catalan default, English available) is stored in `localStorage`.  
All translatable elements use `data-i18n` or `data-i18n-html` attributes.  
Switching language updates the page without reload.

## Run locally

```bash
# Option A — Python
python -m http.server 8000
# then open http://localhost:8000

# Option B — VS Code Live Server extension
# Right-click index.html → Open with Live Server
```

> Opening via `file://` directly will block YouTube embeds (error 153) and absolute-path assets.  
> Always use a local server for full functionality.

---

---

# jordimarti.dev — Portfolio de desenvolupador

Portfolio personal de **Jordi Martí**, Enginyer Industrial, inventor i developer Python.  
Allotjat a GitHub Pages · [jordi-marti-dev.github.io](https://jordi-marti-dev.github.io)

---

## Sobre el projecte

Portfolio estàtic construït amb HTML i CSS purs, sense frameworks ni pas de compilació.  
Inclou una pàgina dedicada al **Projecte Cangur**, dispositiu mèdic biomimètic per a nadons prematurs registrat com a Model d'Utilitat (ES 1260772 Y, OEPM 2021).

## Estructura de fitxers

```
/
├── index.html              ← Pàgina principal del portfolio
├── style.css               ← Sistema de disseny compartit (variables, components)
├── img/
│   ├── cangur-prototip.jpg ← Foto del prototip físic
│   └── cangur-render.jpg   ← Render 3D (sistema complet)
└── projecte_cangur/
    └── index.html          ← Pàgina dedicada del Projecte Cangur
```

## Tecnologies

- HTML5 · CSS3 (custom properties, grid, flexbox)
- IBM Plex Mono + IBM Plex Sans (Google Fonts)
- JavaScript vanilla — sistema bilingüe (CA / EN) via atributs `data-i18n`
- GitHub Pages (allotjament estàtic, sense compilació)

## Sistema bilingüe

La preferència d'idioma (català per defecte, anglès disponible) es desa al `localStorage`.  
Tots els elements traduïbles usen atributs `data-i18n` o `data-i18n-html`.  
El canvi d'idioma actualitza la pàgina sense recarregar.

## Execució en local

```bash
# Opció A — Python
python -m http.server 8000
# obrir http://localhost:8000

# Opció B — extensió VS Code Live Server
# Botó dret sobre index.html → Open with Live Server
```

> Obrir via `file://` directament bloqueja els vídeos de YouTube (error 153) i els recursos amb path absolut.  
> Sempre cal usar un servidor local per a la funcionalitat completa.
