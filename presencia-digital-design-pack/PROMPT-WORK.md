# Prompt para ChatGPT Work — Presencia Digital Express

Trabaja directamente sobre mi aplicación REAL **Presencia Digital Express**. No crees otra aplicación, otro proyecto Supabase ni otro repositorio.

Antes de modificar, identifica el repositorio correcto de Presencia Digital Express y confirma que corresponde al proyecto real. NO tocar BellaMujer, Gastr0App ni otros proyectos.

## Referencias de diseño

En mi repositorio `agarciaia/repositorios-utiles-ia` existe el archivo:

`presencia-digital-design-pack/README.md`

Léelo completo y usa las referencias indicadas de `VoltAgent/awesome-design-md`:

- `design-md/airbnb/DESIGN.md`
- `design-md/cal/DESIGN.md`
- `design-md/airtable/DESIGN.md`
- `design-md/linear.app/DESIGN.md`

Si tienes terminal en el repositorio real, descarga las versiones actuales con `npx getdesign@latest add <slug>` usando los slugs `airbnb`, `cal`, `airtable` y `linear.app`. Hazlo en directorios temporales para que una descarga no sobrescriba a la anterior. Guarda las referencias separadas dentro de `design/inspirations/` y crea o actualiza `design/DESIGN.md` como síntesis propia de Presencia Digital Express.

## Cómo usarlas

- Airbnb: vista pública móvil, fotografías, tarjetas, servicios, reseñas, galería y acciones rápidas.
- Cal.com: reservas, profesionales, calendario, horarios, selección de bloques y confirmaciones.
- Airtable: panel administrador, formularios, tablas, filtros, edición y organización de datos.
- Linear: jerarquía, densidad y pulido del Superadministrador/configuración, sin convertir toda la aplicación a modo oscuro.

## Restricciones obligatorias

- NO rediseñar toda la aplicación.
- Mantener la estética general actual que ya está aprobada.
- Mantener arquitectura multinegocio mediante `business_id`.
- NO eliminar negocios, usuarios, reservas, imágenes ni datos existentes.
- NO cambiar URLs públicas, slugs ni QR estables.
- NO romper Supabase Auth, RLS, Storage, Edge Functions ni permisos.
- Mantener paletas y personalización por negocio.
- No copiar logos, textos, imágenes ni activos propietarios de las marcas de referencia.
- Usar las referencias solo para mejorar coherencia visual, espaciado, tipografía, componentes, estados, iconografía, accesibilidad y responsive.
- Prioridad mobile-first para 360–450 px.

## Trabajo solicitado

1. Inspecciona primero el frontend real, Superadministrador, panel administrador y vista cliente.
2. Identifica inconsistencias visuales y componentes reutilizables.
3. Descarga/lee las cuatro referencias y define qué patrón usarás en cada zona.
4. Crea una guía `design/DESIGN.md` propia de Presencia Digital Express.
5. Implementa mejoras por componentes, sin alterar la lógica funcional innecesariamente.
6. Verifica en móvil botones, inputs, tarjetas, navegación, estados, contraste y objetivos táctiles.
7. Prueba que administrador, cliente, reservas, QR y rutas sigan funcionando.
8. Publica solo cuando las pruebas sean correctas.
9. Al final entrégame: archivos modificados, referencias usadas, mejoras realizadas, pruebas ejecutadas y cualquier riesgo pendiente.
