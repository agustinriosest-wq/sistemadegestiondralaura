# Despliegue en Vercel

El panel es una página estática ubicada en la raíz del repositorio. No requiere compilación, instalación de dependencias ni variables de entorno.

1. Importa el repositorio en Vercel.
2. Deja vacíos **Build Command** y **Output Directory** para que Vercel publique `index.html` desde la raíz.
3. Pulsa **Deploy**. Los siguientes cambios en la rama de producción se desplegarán automáticamente.

`vercel.json` establece cabeceras de seguridad y marca el panel para que los buscadores no lo indexen.

## Alcance actual y datos

Esta versión es una demostración: los pacientes son ficticios, los cambios solo existen en memoria mientras la página está abierta y Google Calendar y WhatsApp no están conectados. No introduzcas datos personales, clínicos ni credenciales. Las cabeceras y la exclusión de buscadores no sustituyen la autenticación ni hacen privado un sitio publicado.

Antes de operar con pacientes, implementa un backend privado con autenticación y controles de acceso, almacenamiento seguro e integraciones autorizadas. Nunca incluyas credenciales o secretos en el HTML o JavaScript entregado al navegador.
