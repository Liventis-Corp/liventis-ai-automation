# LIVENTIS AI & AUTOMATION — Landing definitiva

Landing estática, responsive, sin framework ni dependencias, preparada para publicar en Vercel (plan apto para uso comercial) o en un alojamiento web con HTML estático.

## Archivos
- `index.html`: landing completa, estilos y evaluación interactiva local.
- `vercel.json`: cabeceras básicas de seguridad.

## Despliegue en Vercel
1. Crear un repositorio privado `liventis-ai-automation` en GitHub.
2. Subir **los archivos de esta carpeta directamente a la raíz** del repositorio, no una carpeta exterior ni el ZIP.
3. Vercel > Add New > Project > Import Git Repository.
4. Framework Preset: `Other`. Root Directory: `./`. Build Command: vacío (sin compilación). Output Directory: sin especificar.
5. Deploy. En Settings > Domains, añadir `automatizaciones.liventiscorp.com`.
6. Configurar en el proveedor DNS el registro indicado específicamente por Vercel; no alterar los registros de la web principal.

## Funcionalidades
- Secciones comerciales de automatización e IA, áreas de servicio, metodología y preguntas frecuentes.
- Test rápido de selección de tareas: muestra orientaciones **solo en el navegador**, no almacena ni transmite datos.
- Reserva externa: https://calendly.com/aranzazurodriguez/30min

## Antes de comercializar
- Comprobar el enlace real de Calendly, derechos de marca y enlaces de la empresa.
- Añadir información legal y de privacidad aplicable, y comprobar si las integraciones futuras requieren consentimiento.
- Esta versión no tiene CRM, backend ni envío de formularios.
- Vercel Hobby no admite uso comercial: revisar condiciones del plan vigente o utilizar hosting web apto para empresa.
