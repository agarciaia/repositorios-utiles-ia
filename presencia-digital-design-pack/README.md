# Pack de diseño para Presencia Digital Express

Este paquete reúne referencias de diseño verificadas para que ChatGPT Work/Codex las use al mejorar **Presencia Digital Express** sin rediseñar toda la aplicación ni mezclar proyectos.

## Objetivo

Usar archivos `DESIGN.md` como referencias visuales para mejorar componentes concretos de Presencia Digital Express: vista pública móvil, panel administrador, reservas, formularios, tarjetas, botones, navegación, estados y jerarquía visual.

**Regla principal:** las referencias son inspiración y guía técnica. No se debe copiar una marca completa ni reemplazar la identidad actual del producto. La estética aprobada de Presencia Digital Express sigue siendo la fuente principal.

## Fuentes seleccionadas

### 1. Airbnb DESIGN.md
Repositorio: `VoltAgent/awesome-design-md`
Ruta: `design-md/airbnb/DESIGN.md`
Uso recomendado: vista pública del negocio, tarjetas con fotografías, reseñas, acciones rápidas, galería, servicios y experiencia mobile-first.

### 2. Cal.com DESIGN.md
Repositorio: `VoltAgent/awesome-design-md`
Ruta: `design-md/cal/DESIGN.md`
Uso recomendado: módulo de reservas, selección de profesional, calendario, horarios, formularios de reserva, estados y confirmaciones.

### 3. Airtable DESIGN.md
Repositorio: `VoltAgent/awesome-design-md`
Ruta: `design-md/airtable/DESIGN.md`
Uso recomendado: panel administrador, tablas, formularios, edición de datos, filtros, controles y organización de contenido.

### 4. Linear DESIGN.md
Repositorio: `VoltAgent/awesome-design-md`
Ruta: `design-md/linear.app/DESIGN.md`
Uso recomendado: jerarquía, densidad y pulido del Superadministrador y pantallas de configuración. Usar solo patrones compatibles; no convertir toda la aplicación a modo oscuro.

## Instalación recomendada dentro del proyecto real

El sitio getdesign.md permite obtener cada referencia con:

```bash
npx getdesign@latest add <slug>
```

Como cada ejecución puede generar un `DESIGN.md`, Work debe descargarlas individualmente en un directorio temporal y conservarlas separadas en:

```text
design/
  inspirations/
    airbnb.md
    cal.md
    airtable.md
    linear.md
  DESIGN.md
```

El archivo `design/DESIGN.md` debe ser una síntesis propia para Presencia Digital Express, no una copia literal de una sola marca.

## Slugs

```bash
npx getdesign@latest add airbnb
npx getdesign@latest add cal
npx getdesign@latest add airtable
npx getdesign@latest add linear.app
```

## Reglas para Work

1. Inspeccionar primero la aplicación real y su stack.
2. No crear un proyecto nuevo.
3. No cambiar Supabase, `business_id`, RLS, autenticación, URLs, QR ni lógica funcional por una decisión estética.
4. No borrar componentes existentes que ya funcionen.
5. Mantener el diseño general aprobado y usar estas referencias para corregir consistencia, espaciado, jerarquía, botones, tarjetas, formularios, iconografía y experiencia móvil.
6. Para cada cambio visual, reutilizar los componentes existentes cuando sea posible.
7. No copiar logos, textos, imágenes ni activos propietarios de las marcas de referencia.
8. Priorizar accesibilidad, contraste, tamaños táctiles y responsive móvil de 360–450 px.
9. Conservar paletas configurables por negocio.
10. Antes de publicar, probar administrador, cliente, reservas y móvil.

## Fuente y licencia

Las referencias seleccionadas proceden de `VoltAgent/awesome-design-md`, colección publicada bajo licencia MIT. Los DESIGN.md son análisis independientes de patrones visuales y no kits oficiales de las marcas analizadas.
