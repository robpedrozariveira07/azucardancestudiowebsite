# Azúcar Dance Studio

Sitio web de Azúcar Dance Studio para las sedes Portales y Coyoacán, CDMX.

## Qué incluye

- Video principal y logo oficial.
- Sección Nosotros.
- Cursos desde cero con horarios, preventa y enlaces de pago de Stripe.
- Nuestras clases y horarios por sucursal.
- Clases particulares y coreografías especiales.
- Ubicaciones, mapas y enlaces de contacto por WhatsApp.
- Diseño adaptable para computadora, tablet y celular.

## Requisitos

- Node.js 22.13 o posterior.
- npm.

## Abrir el proyecto en tu computadora

```bash
npm install
npm run dev
```

Después abre la dirección local que aparezca en la terminal.

## Comprobar el proyecto

```bash
npm test
```

## Archivos principales

- `public/preview/index.html`: contenido, diseño e interacciones del sitio.
- `public/preview/assets/`: video, logo e imágenes del proyecto.
- `app/page.tsx`: página que presenta el sitio.
- `app/globals.css`: estructura exterior de la vista.
- `package.json`: dependencias y comandos disponibles.

## Subir a GitHub desde el navegador

1. Crea un repositorio nuevo en GitHub.
2. Elige **Add file → Upload files**.
3. Descomprime el paquete del proyecto.
4. Arrastra todas las carpetas y archivos descomprimidos, no el archivo ZIP.
5. Escribe un mensaje como `Primera versión del sitio`.
6. Presiona **Commit changes**.

El paquete no incluye `node_modules`, compilaciones ni archivos temporales; se generan de nuevo al ejecutar `npm install` y `npm run build`.

## Nota sobre publicación

Guardar el proyecto en GitHub no publica el sitio automáticamente. Para usar un dominio público debe conectarse el repositorio con un servicio de alojamiento compatible o mantenerse la publicación actual de Sites.

© 2026 Azúcar Dance Studio
