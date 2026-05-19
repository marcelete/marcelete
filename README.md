# marcelete.github.io

**Marcelo (Chelo) Bellizia** — Analista de Datos, Automatización y Especialista en IA.
Buenos Aires, Argentina.

🌐 **[marcelete.github.io](https://marcelete.github.io)**

---

## Sobre el proyecto

CV interactivo construido como una experiencia web completa: sin frameworks, sin dependencias externas más allá de Google Fonts. Todo el código vive en un único `index.html` (HTML + CSS + JS inline).

El diseño gira alrededor de una estética de terminal oscura con acentos en azul eléctrico y verde terminal, mostrando creatividad y habilidad técnica al mismo tiempo.

---

## Secciones

| Sección | Descripción |
|---|---|
| **Hero — Terminal** | Animación typewriter que escribe comandos reales: `whoami`, `cat perfil.txt`, `ls skills/` |
| **Sobre mí** | Card con foto pixel art en ventana de terminal y bio técnica |
| **Proyectos** | Carrusel 3D rotativo (CSS `preserve-3d`) con 7 tarjetas flip frente/reverso |
| **Habilidades** | Radar chart SVG animado + tag cloud con tamaño proporcional al nivel |
| **Experiencia** | Timeline alternada izq/der con animación de entrada por scroll |
| **Contacto** | Links a GitHub, LinkedIn y email |

---

## Stack técnico

- HTML5 · CSS3 (`transform-style: preserve-3d`, `IntersectionObserver`, custom properties)
- JavaScript vanilla (ES2020+)
- SVG puro para el radar chart
- Google Fonts: JetBrains Mono + Inter
- Deploy: GitHub Pages (rama `main`)

---

## Correr localmente

No requiere build ni dependencias. Simplemente abrí `index.html` en el navegador, o usá cualquier servidor estático:

```bash
# con Python
python3 -m http.server 8080

# con Node
npx serve .
```

---

## Contacto

- ✉️ marcebellizia@gmail.com
- 💼 [linkedin.com/in/mbellizia](https://linkedin.com/in/mbellizia/)
- 🐙 [github.com/marcelete](https://github.com/marcelete)
