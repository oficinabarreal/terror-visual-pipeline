# 🎃 Terror Visual Pipeline

**Generación procedural de contenido audiovisual de terror** — WebGL shaders, Three.js 3D, SVG, Canvas y audio reactivo. Diseñado para [Rancho Raíz](https://ranchoraiz.barreal.com).

[![GitHub Pages](https://img.shields.io/badge/DEMO-LIVE-brightgreen)](https://oficinabarreal.github.io/terror-visual-pipeline/)

---

## ✨ Qué es

Un pipeline completo de generación de contenido visual de terror que corre 100% en el navegador. Sin servidores, sin costos, sin dependencias externas. Solo HTML + WebGL + audio.

**20 demos interactivas**, **10 shaders custom**, **9 presets 3D**, **8 sonidos procedurales**.

## 🎬 Demos

| # | Demo | Tecnología |
|---|------|-----------|
| 16 | Esfera Flotante 3D | Three.js + GLSL |
| 17 | Monolito Corrupto | Three.js + Shader |
| 18 | Lovecraft Total | WebGL + Procedural |
| 19 | Toro Siniestro | Three.js 3D |
| 20 | Colapso Total | Multi-effect |

Abrí `index.html` en tu navegador para ver el showcase completo con previews embebidos.

## 🏗️ Arquitectura

```
┌─ CAPA DE RENDER ─────────────────────────────┐
│  WebGL Shaders (GLSL) │ Three.js 3D         │
│  Canvas 2D │ SVG Patterns │ CSS Effects      │
├─ CAPA DE AUDIO ──────────────────────────────┤
│  Web Audio API │ Audio Reactivo │ Procedural │
├─ CAPA DE CONTENIDO ──────────────────────────┤
│  Demos Interactivas │ Presets │ Efectos      │
├─ CAPA DE DISTRIBUCIÓN ───────────────────────┤
│  GitHub Pages │ Estático │ $0 hosting        │
└──────────────────────────────────────────────┘
```

## 🛠️ Stack

| Tecnología | Uso |
|-----------|-----|
| **WebGL / GLSL** | Shaders custom (glitch, aberration, scanlines, etc.) |
| **Three.js** | Modelos 3D, escenas, iluminación |
| **Canvas API** | Efectos 2D, partículas, noise |
| **SVG** | Patrones vectoriales, máscaras |
| **Web Audio API** | Audio reactivo, generación procedural |
| **HTML5** | Estructura, zero dependencias JS externas |

## 🚀 Uso

```bash
# Local
python3 -m http.server 8000
# Abrir http://localhost:8000

# O simplemente abrir index.html en tu navegador
```

**Requisitos:** Cualquier navegador moderno con soporte WebGL (Chrome, Firefox, Safari, Edge).

## 📁 Estructura

```
terror-visual-pipeline/
├── index.html              # Showcase principal con todos los demos
├── demos/
│   ├── 16_esfera_flotante_3d/
│   │   └── index.html
│   ├── 17_monolito_corrupto/
│   │   └── index.html
│   ├── 18_lovecraft_total/
│   │   └── index.html
│   ├── 19_toro_siniestro/
│   │   └── index.html
│   └── 20_colapso_total/
│       └── index.html
├── sonidos/                # Audio procedural
│   ├── dark_ambient.wav
│   ├── heartbeat.wav
│   ├── whispers.wav
│   └── ...
└── logo_rancho_raiz.jpg
```

## 🎯 Casos de uso

- **Contenido para redes sociales** de Rancho Raíz (Instagram, TikTok)
- **Experiencias inmersivas** para huéspedes
- **Assets visuales** para horror storytelling
- **Experimentos de creative coding** con audio reactivo

## 👨‍💻 Autor

**Diego Aguirre** — [@oficinabarreal](https://github.com/oficinabarreal)

Todo corre en un teléfono Android con costo $0. Si se puede hacer en Termux, se puede hacer en cualquier lado.

## 📄 Licencia

MIT — usá, modificá, compartí.
