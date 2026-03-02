# 🔥 Forja Arcana 3D

**Artefactos dignos de partidas épicas**

Tienda online de accesorios impresos en 3D para juegos de mesa. Sitio estático desplegable en GitHub Pages.

![Forja Arcana 3D](logo.png)

## 🚀 Deploy en GitHub Pages

1. Crea un repositorio nuevo en GitHub (ej: `forja-arcana-3d`)
2. Sube estos archivos al repositorio:
   - `index.html`
   - `logo.png`
   - `README.md`
3. Ve a **Settings → Pages**
4. En "Source" selecciona **Deploy from a branch**
5. Selecciona la rama `main` y carpeta `/ (root)`
6. Haz click en **Save**
7. Tu sitio estará disponible en `https://tu-usuario.github.io/forja-arcana-3d/`

## ⚙️ Configuración

Edita el objeto `CONFIG` al inicio del `<script>` en `index.html`:

```javascript
const CONFIG = {
  whatsapp: '593XXXXXXXXX',    // ← Tu número de WhatsApp con código de país
  instagram: 'forjaarcana3d',   // ← Tu handle de Instagram
};
```

También actualiza los links en el footer del HTML que contienen estos mismos valores.

## 🎮 Juegos incluidos

- 🏝️ Catan (6 productos)
- 🏰 Carcassonne (5 productos)
- ⚙️ Brass (5 productos)
- 🪐 Terraforming Mars (6 productos)
- ⚔️ Scythe (6 productos)

## ✨ Características

- Catálogo con filtros por juego
- Carrito de compras funcional con cantidades ajustables
- Checkout vía WhatsApp e Instagram (el pedido se envía como mensaje formateado)
- Aviso de elaboración bajo pedido
- Formulario de contacto para pedidos especiales
- Diseño responsivo (mobile-first)
- Animaciones y partículas de fondo
- Tipografía medieval/fantástica (Cinzel Decorative)
- SEO básico con meta tags

## 📱 Flujo de compra

1. El cliente navega el catálogo y agrega productos al carrito
2. Al hacer checkout, se genera un mensaje con el detalle del pedido
3. El mensaje se abre en WhatsApp o Instagram Direct
4. Tú recibes el pedido y confirmas el tiempo de entrega

## 📝 Personalización

Para agregar productos, edita el array `PRODUCTS` en el JavaScript. Cada producto tiene:

```javascript
{
  id: 29,                          // ID único
  name: 'Nombre del Producto',
  game: 'catan',                   // ID del juego
  price: 10.00,
  icon: '🎯',                     // Emoji representativo
  desc: 'Descripción del producto',
  color: '#C9A84C'                 // Color de fondo de la tarjeta
}
```

---

Hecho con 🔥 por Forja Arcana 3D
