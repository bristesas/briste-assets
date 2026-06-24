# Briste · Biblioteca de assets

Repositorio **central de imágenes y contenido gráfico** de Briste, para usar en
cualquier proyecto (plataforma del clon, landing, futuros proyectos) y en cualquier
momento. Subís una imagen **una sola vez** acá y la referenciás por URL desde donde
quieras.

## Cómo subir imágenes (sin programar)

1. Entrá a este repo en GitHub.
2. Abrí la carpeta donde va el archivo (`branding/` para logos/marca, `img/` para fotos y banners).
3. **Add file → Upload files** → arrastrá tus imágenes.
4. **Commit changes**.

> Usá nombres simples, en minúscula y sin espacios: `logo-briste.png`, `banner-campo.jpg`.

## Cómo usar una imagen (URL por CDN jsDelivr)

Cada archivo queda disponible en una URL estable con este patrón:

```
https://cdn.jsdelivr.net/gh/bristesas/briste-assets@main/<carpeta>/<archivo>
```

Ejemplos:

```
https://cdn.jsdelivr.net/gh/bristesas/briste-assets@main/branding/briste-logo.svg
https://cdn.jsdelivr.net/gh/bristesas/briste-assets@main/img/banner-campo.jpg
```

Esa URL se puede pegar en cualquier web/proyecto (`<img src="...">`), en la plataforma,
en la landing, etc.

> Nota: jsDelivr cachea por unas horas. Si reemplazás una imagen con el **mismo nombre**,
> puede tardar en actualizarse. Para forzar la versión nueva, cambiá el nombre del archivo
> (ej. `logo-v2.png`) o usá el hash del commit en lugar de `@main`.

## Estructura

- `branding/` — logos, isotipos, marca.
- `img/` — fotos, banners, ilustraciones.
