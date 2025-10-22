markdown
# 🐟 LA CHOZA NAUTICA - Restaurante Marino

Sistema completo de pedidos online con código QR para restaurante de mariscos.

## 🚀 Características

- **Menú Digital Interactivo**: Catálogo completo de platillos con imágenes y precios
- **Sistema de Carrito**: Añade, elimina y gestiona pedidos
- **Formulario de Pedidos**: Información completa del cliente y entrega
- **Registro de Usuarios**: Sistema de registro para delivery
- **Código QR Personalizable**: Genera QR para acceso rápido al menú
- **Diseño Responsive**: Adaptable a móviles, tablets y desktop
- **Animaciones Suaves**: Experiencia visual atractiva

## 📁 Estructura del Proyecto

```
la-choza-nautica/
├── index.html          # Página principal
├── styles.css          # Estilos CSS
├── script.js           # Funcionalidad JavaScript
├── qr-generator.html   # Generador de código QR
└── README.md           # Este archivo
```

## 🛠️ Instalación

### Opción 1: Servidor Local
1. Descarga todos los archivos
2. Coloca los archivos en la misma carpeta
3. Abre `index.html` con un navegador web

### Opción 2: GitHub Pages (Recomendado)
1. Crea un repositorio en GitHub
2. Sube los archivos: `index.html`, `styles.css`, `script.js`
3. Ve a Settings → Pages
4. Selecciona la rama `main` como fuente
5. Guarda y espera unos minutos
6. Tu sitio estará en: `https://tu-usuario.github.io/nombre-repo`

### Opción 3: Netlify
1. Arrastra la carpeta completa a [Netlify Drop](https://app.netlify.com/drop)
2. Obtén tu URL instantáneamente

## 📱 Generar Código QR

1. Abre `qr-generator.html` en tu navegador
2. Ingresa la URL donde alojaste tu sitio
3. Personaliza tamaño y colores
4. Haz clic en "Generar QR"
5. Descarga o imprime el código

## 🎨 Personalización

### Cambiar Colores
Edita en `styles.css`:
```css
/* Color principal */
color: #2c5aa0;

/* Gradiente de fondo */
background: linear-gradient(135deg, #667eea 0%, #764ba2 100%);
```

### Modificar Menú
Edita en `script.js`:
```javascript
const menuItems = [
    {
        id: 1,
        name: "Tu Platillo",
        description: "Descripción",
        price: 25.00,
        emoji: "🍤"
    },
    // Agrega más items...
];
```

## 💡 Uso del Sistema

### Para Clientes:
1. Escanea el código QR en el restaurante
2. Navega por el menú
3. Añade platillos al carrito
4. Completa el formulario de pedido
5. Confirma tu orden

### Para Administradores:
1. Actualiza el menú en `script.js`
2. Modifica precios según necesidad
3. Personaliza colores y diseño
4. Genera nuevos códigos QR

## 🔧 Tecnologías Utilizadas

- **HTML5**: Estructura del sitio
- **CSS3**: Estilos y animaciones
- **JavaScript**: Funcionalidad interactiva
- **QRCode.js**: Generación de códigos QR

## 📞 Soporte

Para preguntas o soporte:
- Email: contacto@lachozanautica.com
- Teléfono: +51 999 888 777

## 📄 Licencia

© 2025 La Choza Nautica. Todos los derechos reservados.

---

## 🎯 Próximas Mejoras

- [ ] Integración con WhatsApp
- [ ] Sistema de pagos online
- [ ] Panel de administración
- [ ] Notificaciones push
- [ ] Sistema de puntos de fidelidad
- [ ] Chat en vivo
- [ ] Múltiples idiomas