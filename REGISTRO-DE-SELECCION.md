# Registro de selección y actualizaciones

## Revisión del 12 de octubre de 2026

### Resultado
- Se consultaron metadatos de GitHub para los 24 proyectos incluidos: estrellas, estado archivado, última fecha de push y licencia declarada.
- Los 24 aparecen no archivados. Las últimas fechas de push consultadas van del 8 al 12 de octubre de 2026.
- Se actualizaron las estrellas aproximadas del catálogo a la fotografía del 12 de octubre de 2026.
- Se revisaron manualmente las licencias que GitHub devuelve como `NOASSERTION`, pues varios proyectos tienen condiciones propias o licencias distintas por componente.
- No se copió código de terceros; se enlazan los repositorios originales.

### Cambios materiales
1. **Popularidad:** se actualizaron las estrellas aproximadas de los 24 proyectos. Son valores cambiantes, no una garantía de calidad.
2. **Licencias:** se añadieron advertencias específicas:
   - n8n: Sustainable Use License; archivos Enterprise con licencia separada.
   - Activepieces: MIT en el núcleo; áreas Enterprise separadas.
   - Dify: Apache-2.0 modificada con condiciones adicionales, incluida una restricción para ciertos despliegues multiusuario.
   - Open WebUI: licencia propia con condiciones de marca y redistribución.
   - Budibase: GPL-3.0 en conjunto, con licencias por paquete y BSL para determinadas funciones de pago.
   - Strapi: MIT en Community Edition; componentes Enterprise con licencia separada.
   - Quarto CLI: la API no detecta un SPDX, pero el repositorio contiene `COPYING.md` con MIT.
3. **Flowise sigue excluido:** GitHub confirma que FlowiseAI/Flowise está archivado y reporta como último push el 13 de agosto de 2026. Alternativas ya incluidas: Dify o Activepieces para flujos visuales de IA y n8n para automatización general.
4. **No se retiraron proyectos activos:** no se detectó un proyecto incluido archivado ni una señal clara de abandono reciente según su última fecha de push.

## Selección incluida

- **Automatización:** n8n-io/n8n, activepieces/activepieces, huginn/huginn, kestra-io/kestra.
- **IA:** langgenius/dify, open-webui/open-webui, assafelovic/gpt-researcher.
- **Poco código:** appsmithorg/appsmith, Budibase/budibase, ToolJet/ToolJet.
- **Web y backend:** vercel/next.js, vitejs/vite, shadcn-ui/ui, supabase/supabase, appwrite/appwrite, pocketbase/pocketbase.
- **E-books y documentos:** jgm/pandoc, kovidgoyal/calibre, Sigil-Ebook/Sigil, quarto-dev/quarto-cli, rust-lang/mdBook, typst/typst.
- **CMS:** strapi/strapi, payloadcms/payload.

## Criterios de selección

1. Utilidad concreta para crear productos, automatizar trabajo o publicar contenido.
2. Comunidad significativa; las estrellas son un indicador secundario.
3. Repositorio no archivado y actividad reciente.
4. Documentación y posibilidad razonable de instalación o reutilización.
5. Cobertura de distintos niveles técnicos.
6. Licencia identificada o advertencia explícita cuando sea especial.
7. Evitar duplicados sin una diferencia práctica clara.

## Límites de la revisión

- Estrellas, fechas y estados pueden cambiar.
- La fecha de push no sustituye revisar releases, incidencias, seguridad y compatibilidad.
- Las notas de licencia son orientativas, no asesoría legal. Antes de vender, redistribuir o alojar un producto, lee la licencia vigente y la de sus dependencias.
- Un repositorio público puede incluir funciones Enterprise, marcas registradas, servicios externos o costos de infraestructura.

## Próxima revisión

Volver a comprobar estrellas, archivo, fecha de push, licencia y alternativas. Modificar el catálogo solo cuando haya cambios materiales; si todo sigue igual, dejar los archivos sin cambios.
