<svg width="900" height="160" xmlns="http://www.w3.org/2000/svg">
  <defs>
    <linearGradient id="bg" x1="0%" y1="0%" x2="100%" y2="100%">
      <stop offset="0%" style="stop-color:#0d1117"/>
      <stop offset="100%" style="stop-color:#161b22"/>
    </linearGradient>
    <linearGradient id="line" x1="0%" y1="0%" x2="100%" y2="0%">
      <stop offset="0%" style="stop-color:#00d4ff;stop-opacity:0"/>
      <stop offset="30%" style="stop-color:#00d4ff;stop-opacity:1"/>
      <stop offset="70%" style="stop-color:#7c3aed;stop-opacity:1"/>
      <stop offset="100%" style="stop-color:#7c3aed;stop-opacity:0"/>
    </linearGradient>
    <filter id="glow">
      <feGaussianBlur stdDeviation="3" result="coloredBlur"/>
      <feMerge>
        <feMergeNode in="coloredBlur"/>
        <feMergeNode in="SourceGraphic"/>
      </feMerge>
    </filter>
  </defs>

  <!-- Background -->
  <rect width="900" height="160" fill="url(#bg)" rx="10"/>

  <!-- Grid lines -->
  <line x1="0" y1="40" x2="900" y2="40" stroke="#21262d" stroke-width="1"/>
  <line x1="0" y1="80" x2="900" y2="80" stroke="#21262d" stroke-width="1"/>
  <line x1="0" y1="120" x2="900" y2="120" stroke="#21262d" stroke-width="1"/>
  <line x1="180" y1="0" x2="180" y2="160" stroke="#21262d" stroke-width="1"/>
  <line x1="360" y1="0" x2="360" y2="160" stroke="#21262d" stroke-width="1"/>
  <line x1="540" y1="0" x2="540" y2="160" stroke="#21262d" stroke-width="1"/>
  <line x1="720" y1="0" x2="720" y2="160" stroke="#21262d" stroke-width="1"/>

  <!-- Accent dots -->
  <circle cx="180" cy="80" r="3" fill="#00d4ff" opacity="0.4"/>
  <circle cx="360" cy="80" r="3" fill="#7c3aed" opacity="0.4"/>
  <circle cx="540" cy="80" r="3" fill="#00d4ff" opacity="0.4"/>
  <circle cx="720" cy="80" r="3" fill="#7c3aed" opacity="0.4"/>

  <!-- Top accent line -->
  <rect x="0" y="0" width="900" height="3" fill="url(#line)" rx="2"/>

  <!-- Icon -->
  <text x="60" y="95" font-size="42" text-anchor="middle">🌐</text>

  <!-- Title -->
  <text x="450" y="65" font-family="'Courier New', monospace" font-size="32" font-weight="bold"
        fill="#ffffff" text-anchor="middle" filter="url(#glow)">WEB REMOTE WORK</text>

  <!-- Subtitle -->
  <text x="450" y="100" font-family="'Courier New', monospace" font-size="13"
        fill="#8b949e" text-anchor="middle" letter-spacing="3">HTML · CSS · JAVASCRIPT · LANDING PAGE</text>

  <!-- Bottom tag -->
  <rect x="370" y="118" width="160" height="22" rx="4" fill="#21262d" stroke="#30363d" stroke-width="1"/>
  <text x="450" y="133" font-family="'Courier New', monospace" font-size="11"
        fill="#00d4ff" text-anchor="middle" letter-spacing="2">PROYECTO ESCOLAR</text>

  <!-- Bottom accent line -->
  <rect x="0" y="157" width="900" height="3" fill="url(#line)" rx="2"/>
</svg>

> Página web estática sobre el trabajo en remoto, sus ventajas, herramientas y cultura laboral moderna — desarrollada como proyecto escolar.

---

### ⚙️ Stack

| Tecnología   | Uso |
|--------------|-----|
| `HTML5`      | Estructura y maquetación semántica |
| `CSS3`       | Estilos, diseño y responsive |
| `JavaScript` | Interactividad y manipulación del DOM |

---

### 📂 Estructura del proyecto

```
RemoteWork/
├── index.html
├── css/
│   └── styles.css
├── js/
│   └── main.js
├── assets/
│   └── img/
└── README.md
```

---

### 📋 Sobre el proyecto

Este repositorio contiene una **landing page** sobre el tema del **trabajo en remoto**, desarrollada como parte de un proyecto escolar de desarrollo web. La página incluye:

- Introducción al trabajo remoto y sus ventajas
- Herramientas y plataformas clave para equipos remotos
- Consejos y buenas prácticas para trabajar desde casa
- Cultura laboral moderna y conciliación personal

---

### ▶️ Cómo ejecutarlo

```bash
# 1. Clona el repositorio
git clone https://github.com/tu-usuario/RemoteWork.git

# 2. Entra en la carpeta del proyecto
cd RemoteWork

# 3. Abre en el navegador
open index.html
```

> O simplemente haz doble clic en `index.html` para abrirlo en tu navegador.

---

```
[ dev ]  tu-usuario  ·  Desarrollo Web  ·  HTML + CSS + JS
```
