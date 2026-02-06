# 🎨FrontendChallenges

Repositorio dedicado a completar y exhibir desafíos de Frontend Mentor, con el objetivo de mejorar habilidades de desarrollo frontend mediante práctica constante.

## 🌐 Demo en Vivo

**[Ver todos los desafíos →](https://erickcraft1.github.io/FrontendChallenges/)**

## 📋 Tabla de Contenidos

- [Sobre el Proyecto](#sobre-el-proyecto)
- [Desafíos Completados](#desafíos-completados)
- [Tecnologías Utilizadas](#tecnologías-utilizadas)
- [Estructura del Proyecto](#estructura-del-proyecto)
- [Instalación y Uso](#instalación-y-uso)
- [Contribuir](#contribuir)
- [Licencia](#licencia)
- [Contacto](#contacto)

## 🎯 Sobre el Proyecto

Este repositorio contiene mis soluciones a diversos desafíos de Frontend Mentor. Cada desafío está diseñado para mejorar habilidades específicas en desarrollo frontend, desde componentes básicos hasta layouts complejos y características interactivas.

### Objetivos

- ✅ Practicar HTML semántico y accesible
- ✅ Mejorar habilidades en CSS y diseño responsivo
- ✅ Implementar JavaScript vanilla para interactividad
- ✅ Explorar frameworks modernos (Astro, Tailwind CSS)
- ✅ Mantener código limpio y bien organizado

## 🏆 Desafíos Completados

| #   | Desafío                      | Nivel  | Demo                                                                                           | Código                                            |
| --- | ---------------------------- | ------ | ---------------------------------------------------------------------------------------------- | ------------------------------------------------- |
| 01  | QR Code Component            | Newbie | [Demo](https://erickcraft1.github.io/FrontendChallenges/qr-code-component-main/)               | [Código](./qr-code-component-main/)               |
| 02  | Product Preview Card         | Newbie | [Demo](https://erickcraft1.github.io/FrontendChallenges/product-preview-card-component-main/)  | [Código](./product-preview-card-component-main/)  |
| 03  | Results Summary Component    | Newbie | [Demo](https://erickcraft1.github.io/FrontendChallenges/results-summary-component-main/)       | [Código](./results-summary-component-main/)       |
| 04  | NFT Preview Card             | Newbie | [Demo](https://erickcraft1.github.io/FrontendChallenges/nft-preview-card-component-main/)      | [Código](./nft-preview-card-component-main/)      |
| 05  | Order Summary Component      | Newbie | [Demo](https://erickcraft1.github.io/FrontendChallenges/order-summary-component-main/)         | [Código](./order-summary-component-main/)         |
| 06  | Stats Preview Card           | Newbie | [Demo](https://erickcraft1.github.io/FrontendChallenges/stats-preview-card-component-main/)    | [Código](./stats-preview-card-component-main/)    |
| 07  | 3 Column Preview Card        | Newbie | [Demo](https://erickcraft1.github.io/FrontendChallenges/3-column-preview-card-component-main/) | [Código](./3-column-preview-card-component-main/) |
| 08  | Profile Card Component       | Newbie | [Demo](https://erickcraft1.github.io/FrontendChallenges/profile-card-component-main/)          | [Código](./profile-card-component-main/)          |
| 09  | Social Proof Section         | Newbie | [Demo](https://erickcraft1.github.io/FrontendChallenges/social-proof-section-main/)            | [Código](./social-proof-section-main/)            |
| 10  | Four Card Feature Section    | Newbie | [Demo](https://erickcraft1.github.io/FrontendChallenges/four-card-feature-section-main/)       | [Código](./four-card-feature-section-main/)       |
| 11  | Article Preview Component    | Junior | [Demo](https://erickcraft1.github.io/FrontendChallenges/article-preview-component-main/)       | [Código](./article-preview-component-main/)       |
| 12  | Interactive Rating Component | Junior | [Demo](https://erickcraft1.github.io/FrontendChallenges/interactive-rating-component-main/)    | [Código](./interactive-rating-component-main/)    |

**Total: 12 desafíos completados** 🎉

## 🛠️ Tecnologías Utilizadas

### Frontend Base

- **HTML5** - Estructura semántica
- **CSS3** - Estilos y diseño responsivo
- **JavaScript** - Interactividad y lógica
- **React 18.3.1** - Componentes interactivos

### Frameworks y Herramientas

- **[Astro 4.11.5](https://astro.build/)** - Framework principal para la galería
- **[Tailwind CSS 3.4.4](https://tailwindcss.com/)** - Utilidades CSS
- **Node.js 22.21.0** - Entorno de ejecución
- **pnpm 9.4.0** - Gestor de paquetes
- **Git & GitHub** - Control de versiones
- **GitHub Pages** - Despliegue automático

### Dependencias Principales

```json
{
  "@astrojs/react": "3.6.0",
  "@astrojs/tailwind": "5.1.0",
  "@types/react": "18.3.3",
  "@types/react-dom": "18.3.0",
  "astro": "4.11.5",
  "pnpm": "9.4.0",
  "react": "18.3.1",
  "react-dom": "18.3.1",
  "tailwindcss": "3.4.4"
}
```

## 🚀 Instalación y Uso

### Requisitos Previos

- **Node.js** versión 22.21.0 (recomendado)
- **pnpm** versión 9.4.0 o superior (gestor de paquetes)

#### Verificar versión de Node.js

```bash
node --version
# Debe mostrar: v22.21.0 o superior
```

Si no tienes Node.js instalado o necesitas actualizar:

- Descarga desde [nodejs.org](https://nodejs.org/)
- O usa [nvm](https://github.com/nvm-sh/nvm) para gestionar versiones:
  ```bash
  nvm install 22.21.0
  nvm use 22.21.0
  ```

#### Instalar pnpm

```bash
npm install -g pnpm@9.4.0
```

### Instalación del Proyecto

1. Clona el repositorio y selecciona la rama principal:

```bash
git clone https://github.com/ErickCraft1/FrontendChallenges.git
cd FrontendChallenges
git checkout main
```

2. Instala las dependencias con pnpm:

```bash
pnpm install
```

Esto instalará automáticamente:

- ✅ Astro 4.11.5
- ✅ Tailwind CSS 3.4.4
- ✅ React 18.3.1
- ✅ Todas las demás dependencias necesarias

### Comandos Disponibles

```bash
# Desarrollo - inicia servidor local en http://localhost:4321
pnpm run dev

# Build - genera archivos para producción
pnpm run build

# Preview - previsualiza el build de producción
pnpm run preview

# Limpiar cache y reinstalar dependencias
pnpm install --force
```

### Configuración de Astro y Tailwind

El proyecto ya viene configurado, pero si necesitas entender la configuración:

#### Astro (`astro.config.mjs`)

```javascript
import { defineConfig } from "astro/config";
import react from "@astrojs/react";
import tailwind from "@astrojs/tailwind";

export default defineConfig({
  integrations: [react(), tailwind()],
});
```

#### Tailwind CSS (`tailwind.config.mjs`)

```javascript
export default {
  content: ["./src/**/*.{astro,html,js,jsx,md,mdx,svelte,ts,tsx,vue}"],
  theme: {
    extend: {},
  },
  plugins: [],
};
```

### Ver un Desafío Individual

Cada desafío puede ejecutarse independientemente abriendo su archivo `index.html` en el navegador, o a través del servidor de desarrollo de Astro.

### Solución de Problemas Comunes

**Error: "command not found: pnpm"**

```bash
npm install -g pnpm
```

**Error al instalar dependencias**

```bash
# Limpia el cache y reinstala
rm -rf node_modules pnpm-lock.yaml
pnpm install
```

**Puerto 4321 ocupado**

```bash
# Usa un puerto diferente
pnpm run dev -- --port 3000
```
