# CV web de Samuel Cevada Salinas

Sitio estático y responsive preparado para GitHub Pages. No requiere Node.js, instalación de dependencias ni proceso de compilación.

## Publicar en GitHub Pages

1. Crea un repositorio nuevo en GitHub.
2. Sube todos los archivos de esta carpeta a la raíz del repositorio, incluida la carpeta `.github`.
3. Usa `main` como rama principal.
4. En GitHub, abre **Settings > Pages** y selecciona **GitHub Actions** como fuente.
5. Si el flujo no se ejecutó automáticamente, abre **Actions > Desplegar en GitHub Pages** y selecciona **Run workflow**.

El sitio quedará disponible normalmente en `https://USUARIO.github.io/REPOSITORIO/`.

## Editar el contenido

- Información y textos: `index.html`
- Colores, tipografía y distribución: `styles.css`
- Icono de la pestaña: `favicon.svg`
- Despliegue automático: `.github/workflows/deploy.yml`

Todas las rutas son relativas, por lo que el sitio funciona tanto en un repositorio llamado `USUARIO.github.io` como en una ruta de proyecto.
