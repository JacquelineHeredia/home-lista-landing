# Home Lista · Landing de la sección Alacena

Landing con el catálogo de 111 productos de Home Lista. El cliente arma su pedido y lo envía por WhatsApp con página, medida, cantidad y total referencial.

## Archivos
- `index.html`: la página completa (diseño, catálogo y lógica del pedido).
- `img/`: fotos de productos (`p1.webp` … `p111.webp`, una por página del catálogo) e ícono de WhatsApp.

## Cambios frecuentes (dentro de `index.html`)
- **Número de WhatsApp:** busca `var WHATSAPP` y cambia el número (con 51 adelante, sin espacios).
- **Precios, nombres o medidas:** busca `var PRODUCTOS`. Cada línea es un producto:
  `[página, 'Nombre', 'Detalle', [['medida', precio]], cantidad pack, precio pack, 'zona']`
- **Foto de un producto:** reemplaza `img/p<página>.webp` por una nueva con el mismo nombre.
- **Zonas:** busca `var CATS`.

## Publicar
Settings → Pages → Deploy from a branch → `main` / `(root)` → Save.
