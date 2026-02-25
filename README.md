# Lumina CF — Compliance Estratégico

Landing de revisión para cliente. Publicado con GitHub Pages.

## Cómo publicar en GitHub Pages

1. **Crea un repositorio nuevo en GitHub** (público):
   - Ve a [github.com/new](https://github.com/new)
   - Nombre sugerido: `lumina-cf`
   - No marques "Add a README" (ya tienes contenido local)
   - Clic en **Create repository**

2. **Conecta y sube el código** (sustituye `TU_USUARIO` por tu usuario de GitHub):

   ```bash
   cd /Users/edangelo/lumina/lumina-cf
   git remote add origin https://github.com/TU_USUARIO/lumina-cf.git
   git branch -M main
   git push -u origin main
   ```

3. **Activa GitHub Pages**:
   - En el repo: **Settings** → **Pages**
   - **Source**: Deploy from a branch
   - **Branch**: `main` / **Folder**: `/ (root)`
   - **Save**

4. En 1–2 minutos el sitio estará en:
   **https://TU_USUARIO.github.io/lumina-cf/**

Comparte ese enlace con tu cliente para la revisión.
