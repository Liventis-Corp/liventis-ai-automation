# LIVENTIS AI & AUTOMATION — Proyecto limpio

Contiene **solo cuatro archivos**, todos para la raíz del repositorio:
- `index.html` — página corporativa, formulario HubSpot, test de 5 preguntas y resultados por respuestas.
- `logo-liventis.jpg` — logotipo original facilitado por la empresa.
- `vercel.json` — configuración estática de Vercel.
- `README.md` — estas instrucciones.

## Publicación sin perder la URL
1. No eliminar el proyecto de Vercel ni el repositorio GitHub.
2. En la rama de producción (`principal` / `main`), reemplazar `index.html`, `vercel.json` y `README.md`; añadir `logo-liventis.jpg`. Asegurarse de que están **en la raíz**.
3. Eliminar de esa rama otros archivos sobrantes solo si corresponden al proyecto viejo. No subir las carpetas de otros diagnósticos.
4. Eliminar la rama de prueba `actualizacion-hubspot` desde la lista de ramas de GitHub, solo después de comprobar la versión final de producción; no es necesario vaciarla archivo por archivo.
5. Al confirmar el commit en la rama de producción, Vercel publica la actualización en el dominio existente.

## Comprobaciones obligatorias
- El formulario debe estar publicado en HubSpot (portal 149636353, id b316210e-b4a0-4010-8b43-85a51797460b) y permitir envíos desde el dominio donde se despliega.
- El evento `hs-form-event:on-submission:success` del editor nuevo de HubSpot desbloquea el test. **Probar con un contacto de prueba**: verificar contacto creado y apertura del test.
- Comprobar los cinco pasos, las opciones y los resultados; comprobar el botón de Calendly (`https://calendly.com/aranzazurodriguez`).
- En HubSpot, confirmar que los campos ocultos `Landing de origen` y `Servicio de interés` se completan como se espera. **La presente versión no asigna sus valores de forma verificada**; no asumir que ya se registran correctamente.
- Los resultados del test se calculan localmente: **no se envían todavía al CRM**. Para guardar historiales es necesaria una integración posterior.
- El bloqueo del test es una barrera de interfaz, no autenticación de servidor. No usarlo para proteger contenidos de pago o confidenciales.
- La web pública puede requerir información legal adicional y configuración de seguimiento/consentimiento de cookies.

## Para WordPress
Este despliegue se mantiene independiente en Vercel. Al integrarlo en `liventiscorp.com/automatizar-negocio/` habrá que decidir si se utiliza redirección, proxy o integración en bloques. No pegar este documento HTML completo dentro de un bloque de WordPress.
