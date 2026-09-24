# Skills y repositorios de diseño útiles para ChatGPT / Work / Codex

Revisión basada en el video 85722.mp4 y verificación de los repositorios originales.

## 1. Emil Kowalski — Skills for Designers and Engineers

Repositorio: `emilkowalski/skills`
Licencia: MIT
Uso recomendado: pulido de UI, microinteracciones, animaciones, estados, percepción de velocidad y revisión de componentes.

Skills relevantes:

- `emil-design-eng`: filosofía de Design Engineering, revisión de UI y detalle fino.
- `animate`: implementación de animaciones con propósito.
- `improve-animations`: auditoría y mejora de animaciones existentes.
- `find-animation-opportunities`: detecta dónde una animación puede aportar valor.
- `review-animations`: revisión específica de motion.

Para Gastr0App la prioridad es `emil-design-eng`; las de animación se usan solo si la interfaz realmente las necesita.

Instalación de una skill:

```bash
npx skills add https://github.com/emilkowalski/skills --skill emil-design-eng
```

## 2. Taste Skill

Repositorio: `Leonxlnx/taste-skill`
Sitio: `tasteskill.dev`
Licencia: MIT
Uso recomendado: evitar interfaces genéricas producidas por IA, auditar proyectos existentes y elevar el nivel visual del frontend.

Skills relevantes:

- `redesign-existing-projects`: audita primero y mejora después sin reescribir el proyecto ni romper funcionalidad. Es la más adecuada para Gastr0App.
- `design-taste-frontend`: skill general para frontend premium.
- `image-to-code`: flujo basado en referencias visuales.
- `gpt-taste`: variante agresiva para GPT/Codex; NO usar por defecto en Gastr0App porque fuerza GSAP, React/Tailwind y reglas creativas que no coinciden con su stack actual.

Instalación recomendada para proyectos existentes:

```bash
npx skills add https://github.com/Leonxlnx/taste-skill --skill "redesign-existing-projects"
```

## 3. Figma

Figma no es una skill de GitHub en este flujo. ChatGPT puede trabajar con la integración de Figma cuando esté conectada. Es útil para enviar pantallas, revisar diseños y convertir referencias en capas editables.

## 4. Playwright

Playwright no es una skill de ChatGPT; es una herramienta de automatización y pruebas de navegador. Sirve para pruebas end-to-end, validar rutas, botones, modales, responsive y flujos antes de publicar. No se debe agregar como dependencia a un proyecto solo por aparecer en un tutorial: se instala cuando el flujo de pruebas lo justifica.

## Reglas de uso

1. Inspeccionar el proyecto antes de aplicar una skill.
2. No migrar de framework solo para satisfacer una skill.
3. Mantener la lógica y los datos existentes.
4. No añadir librerías visuales innecesarias.
5. En proyectos existentes, usar primero `redesign-existing-projects` y luego `emil-design-eng` para el pulido final.
6. Usar animaciones solo cuando mejoren comprensión, feedback o percepción de calidad.
