# Facturas

Generador de facturas con registro y descarga directa en PDF. Funciona en el navegador, sin servidor.

Los datos (emisor, clientes, facturas) se guardan solo en el navegador de cada dispositivo. Este repositorio no contiene datos personales.

## Publicar en GitHub Pages
1. Crea un repositorio nuevo en GitHub (público, es lo que permite Pages en el plan gratuito).
2. Sube los 5 archivos de esta carpeta a la raíz: `index.html`, `manifest.webmanifest`, `sw.js`, `icon-192.png`, `icon-512.png`.
3. En el repositorio: Settings → Pages → Source: "Deploy from a branch" → Branch: `main` y carpeta `/ (root)` → Save.
4. En un minuto la app estará en `https://TU-USUARIO.github.io/NOMBRE-DEL-REPO/`.

## Instalar en el móvil
- iPhone (Safari): Compartir → "Añadir a pantalla de inicio".
- Android (Chrome): menú ⋮ → "Instalar aplicación".

## Primer uso
Entra en **Mis datos** y rellena nombre, NIF, dirección e IBAN. Después crea las facturas desde el menú.

## Copias de seguridad
Registro → **Exportar copia** descarga un archivo con las facturas. En un dispositivo nuevo, **Importar copia** las recupera (y también los datos del emisor si todavía están vacíos). Conviene exportar una copia cada mes.

## Actualizar la app
Sustituye `index.html` en el repositorio. Si la app instalada no se actualiza, ciérrala y ábrela de nuevo.
