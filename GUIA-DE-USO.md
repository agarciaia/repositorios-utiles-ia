# Guía de uso e instalación

## Qué significa usar un repositorio

Un repositorio contiene código y documentación. No se incorpora automáticamente a ChatGPT por estar en esta lista. Puedes utilizarlo como servicio en la nube, aplicación de escritorio, sistema autoalojado con Docker o base de desarrollo que se adapta dentro de un proyecto propio.

## Antes de instalar

Pídele a ChatGPT que revise compatibilidad con Windows 11, RAM, almacenamiento, puertos, licencia, versión estable, variables de entorno, servicios pagados, riesgos e instrucciones oficiales.

## Ruta con poca programación

- **Automatizaciones:** n8n o Activepieces.
- **Aplicaciones internas:** Appsmith, ToolJet o Budibase.
- **Aplicaciones con IA:** Dify.
- **E-books:** Calibre para organizar y convertir; Sigil para editar EPUB; Pandoc para automatizar conversiones; Quarto o mdBook para libros mantenibles; Typst para PDF profesional.

## Ruta para desarrollar aplicaciones

Combinación habitual:

- Next.js: aplicación.
- shadcn/ui: interfaz.
- Supabase: datos, usuarios y archivos.
- Vercel u otro proveedor: despliegue.

Para un prototipo pequeño y local, PocketBase puede reemplazar temporalmente a Supabase.

## Cómo usarlo desde ChatGPT

1. Abre Configuración → Apps/Conectores → GitHub.
2. Autoriza únicamente los repositorios necesarios.
3. Pega en el chat el enlace exacto del proyecto.
4. Indica objetivo, sistema operativo, presupuesto y nivel técnico.
5. Para cambios, especifica tu repositorio de destino. No pidas modificar el proyecto original.

Ejemplo:

> Analiza https://github.com/n8n-io/n8n y diseña una instalación segura para Windows 11 usando Docker. No ejecutes cambios todavía. Entrégame requisitos, costos, riesgos y pasos de prueba.

## Orden seguro

1. Analizar el original.
2. Elegir versión estable.
3. Diseñar instalación.
4. Crear una copia o proyecto de prueba.
5. Configurar secretos fuera del código.
6. Probar localmente.
7. Revisar seguridad.
8. Desplegar.
9. Respaldar y documentar.

## Licencias

Las estrellas no conceden permiso ilimitado. Algunos proyectos usan MIT, Apache, GPL, AGPL o licencias fair-code. Antes de vender una app, ofrecerla como servicio o modificarla para clientes, pide una revisión de la licencia actual.
