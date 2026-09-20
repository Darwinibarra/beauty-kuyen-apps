# Beauty Kuyen — Apps para celular

Dos paneles instalables como app en el celular (PWA), publicados con GitHub Pages.

**Importante: este repositorio nunca contiene datos reales del negocio.** Los Excel se
suben desde el navegador en cada visita y se procesan solo en memoria; nada se sube a
GitHub ni a ningún servidor.

## Publicar por primera vez

1. Crea un repositorio nuevo en GitHub (público o privado, ambos sirven para GitHub Pages
   en cuentas Pro; en cuentas gratuitas Pages solo funciona con repos públicos).
   No marques "Add a README" — este repo ya trae uno.
2. En esta carpeta, conecta el repo remoto y sube todo:
   ```
   git remote add origin https://github.com/TU-USUARIO/TU-REPO.git
   git branch -M main
   git push -u origin main
   ```
3. En GitHub: **Settings → Pages → Source → Deploy from a branch → main → / (root) → Save**.
4. Espera 1–2 minutos. Tu sitio queda en `https://TU-USUARIO.github.io/TU-REPO/`.

## Instalar en el celular

1. Abre `https://TU-USUARIO.github.io/TU-REPO/` desde el navegador del celular.
2. Elige el panel (Centro de Mando o Panel Cecilia).
3. Menú del navegador → **"Agregar a pantalla de inicio"** (Android/Chrome) o
   **"Compartir → Agregar a inicio"** (iPhone/Safari).
4. Queda como ícono de app normal. Al abrirlo, sube el Excel del día para ver los datos.

## Actualizar después de un cambio

Desde esta carpeta:
```
git add -A
git commit -m "actualizar app"
git push
```
GitHub Pages se actualiza solo en 1–2 minutos.
