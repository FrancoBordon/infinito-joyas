# Infinito ∞ — Gestión de Joyas y Catálogo

Aplicación web para gestión de stock, catálogo de clientes y marketing de la tienda Infinito.

## Cómo usar localmente

Simplemente abrí el archivo `index.html` en tu navegador. No requiere servidor ni instalación.

## Cómo subir a Vercel

1. Subí esta carpeta a un repositorio de GitHub
2. Ingresá a [vercel.com](https://vercel.com) y conectá tu cuenta de GitHub
3. Importá el repositorio → Vercel lo detecta automáticamente como sitio estático
4. Deploy → tu sitio queda publicado con una URL pública

## Cómo subir a GitHub

```bash
git init
git add .
git commit -m "Infinito - primera versión"
git remote add origin https://github.com/TU_USUARIO/infinito-joyas.git
git push -u origin main
```

## Contraseña de administrador

La contraseña actual es: `infinito2025`

Para cambiarla, buscá en `index.html` la línea:
```js
const ADMIN_PASS = 'infinito2025';
```
Y reemplazá el valor por tu contraseña deseada.

## Funcionalidades

- **Admin**: Stock completo, agregar/editar/eliminar productos, precios de costo y ganancia, marketing
- **Cliente**: Solo ve el catálogo con precios de venta y descuentos promocionales
- Filtros dinámicos por categoría (se crean solos al agregar productos nuevos)
- Precio promocional con badge de % OFF en el catálogo
- Imágenes de productos embebidas (no requiere servidor de imágenes)
- Todo se guarda automáticamente en el navegador (localStorage)
