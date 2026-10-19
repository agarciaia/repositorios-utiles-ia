# Registro de selección y actualizaciones

## Revisión del 19 de octubre de 2026

### Resultado
- Se verificaron los 24 proyectos incluidos: todos continúan activos, no archivados y con utilidad vigente para las categorías del catálogo.
- Se sincronizó el `README.md` con cifras aproximadas de estrellas consultadas el 19 de octubre de 2026.
- Se incorporaron al catálogo principal advertencias específicas sobre licencias y componentes Enterprise.
- Se corrigió la discrepancia de la revisión anterior: el registro indicaba que las cifras estaban publicadas, pero el `README.md` todavía conservaba los valores del 13 de septiembre.
- FlowiseAI/Flowise continúa excluido: permanece archivado y su último push reportado sigue siendo el 13 de agosto de 2026.
- No se añadieron ni retiraron proyectos; no surgió una alternativa que justificara reemplazar alguno de los 24 proyectos activos.

### Estrellas aproximadas actualizadas
- Automatización: n8n 208k; Huginn 50,1k; Kestra 29,9k; Activepieces 25,1k.
- IA: Dify 158,9k; Open WebUI 156,1k; GPT Researcher 30,2k.
- Poco código: ToolJet 41,1k; Appsmith 41,1k; Budibase 28,3k.
- Web y backend: Next.js 143,1k; shadcn/ui 125,9k; Supabase 111,8k; Vite 83,4k; PocketBase 61,5k; Appwrite 57,7k.
- E-books y documentos: Typst 56,7k; Pandoc 46,6k; Calibre 26,2k; mdBook 22,2k; Sigil 7k; Quarto CLI 6,1k.
- CMS: Strapi 73,3k; Payload 45,3k.

## Revisión del 12 de octubre de 2026

### Resultado
- Se consultaron metadatos de GitHub para los 24 proyectos incluidos: estrellas, estado archivado, última fecha de push y licencia declarada.
- Los 24 aparecen no archivados. Las últimas fechas de push consultadas van del 8 al 12 de octubre de 2026.
- Se preparó la actualización de estrellas del 12 de octubre, pero el catálogo principal no pudo publicarse en esa ejecución; la discrepancia quedó corregida el 19 de octubre de 2026.
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
