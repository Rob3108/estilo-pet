# Estilo Pet – tienda para mascotas

Sitio estático (HTML + CSS + JavaScript). No necesita instalar nada ni compilar.

## Estructura
```
index.html
css/styles.css
js/app.js  js/productos.js  js/extras.js
img/            <- NO viene en este paquete: copia aquí tu carpeta img
  logo.png  hero.png
  marcas/       (logos de marcas)
  productos/    (fotos, según lista-fotos.csv)
```

## Subir a GitHub
1. En github.com: **New repository** → nombre `estilo-pet` → Create.
2. **Add file → Upload files** y arrastra `index.html`, `.gitignore`, `README.md` y las carpetas `css`, `js` e `img`
   (la web admite hasta 100 archivos por subida; si tienes más fotos, súbelas en tandas o usa GitHub Desktop).
3. **Commit changes**.

## Publicar en Vercel (dominio gratis)
1. Entra a vercel.com → **Sign up with GitHub**.
2. **Add New… → Project** → importa `estilo-pet`.
3. Framework Preset: **Other**. No pongas Build Command ni Output Directory. → **Deploy**.
4. Te da una dirección como `estilo-pet.vercel.app` (puedes cambiar el nombre en Settings → Domains).
5. Cada cambio que subas a GitHub se publica solo.

## Ojo con mayúsculas
Vercel distingue mayúsculas de minúsculas: `Logo.png` y `logo.png` son archivos distintos.
Revisa que los nombres de `img/` coincidan exactamente con los que usa la página.
