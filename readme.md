# ☕ Café Aroma - Landing Page

Una landing page moderna y completamente funcional para una cafetería, con integración de WhatsApp y formulario de contacto via Formspree.

## 🚀 Características

- **Diseño Responsivo**: Optimizado para móviles, tablets y desktop
- **WhatsApp Integrado**: Botón flotante para contacto directo
- **Formulario de Contacto**: Conectado con Formspree para recibir mensajes
- **Animaciones Suaves**: Efectos visuales atractivos
- **SEO Optimizado**: Estructura HTML semántica
- **GitHub Pages Ready**: Listo para desplegar

## 📁 Estructura del Proyecto

```
cafe-aroma/
├── index.html          # Página principal
├── style.css           # Estilos personalizados
├── script.js           # JavaScript interactivo
└── README.md           # Documentación
```

## 🛠️ Tecnologías Utilizadas

- **HTML5**: Estructura semántica
- **CSS3**: Estilos personalizados + TailwindCSS
- **JavaScript**: Interactividad y animaciones
- **Font Awesome**: Iconos
- **Formspree**: Formularios de contacto
- **Unsplash**: Imágenes de alta calidad

## ⚙️ Configuración

### 1. Configurar Formspree

1. Ve a [formspree.io](https://formspree.io) y crea una cuenta
2. Crea un nuevo formulario
3. Copia tu Form ID
4. En `index.html`, reemplaza `YOUR_FORM_ID` con tu ID real:

```html
<form action="https://formspree.io/f/YOUR_FORM_ID" method="POST">
```

### 2. Configurar WhatsApp

En `index.html` y `script.js`, reemplaza el número de teléfono:

```html
<!-- Cambiar +56912345678 por tu número real -->
<a href="https://wa.me/56912345678?text=Hola,%20me%20interesa%20conocer%20más%20sobre%20Café%20Aroma">
```

### 3. Personalizar Contenido

- **Nombre del negocio**: Buscar y reemplazar "Café Aroma"
- **Dirección**: Actualizar en la sección de contacto
- **Horarios**: Modificar en footer y sección de contacto
- **Precios**: Actualizar en la sección de menú
- **Imágenes**: Reemplazar URLs de Unsplash por tus propias imágenes

## 🚀 Despliegue en GitHub Pages

### Opción 1: Subir archivos directamente

1. Crea un nuevo repositorio en GitHub
2. Sube todos los archivos a la rama `main`
3. Ve a Settings → Pages
4. Selecciona "Deploy from a branch"
5. Elige `main` branch y `/root` folder
6. ¡Tu sitio estará disponible en `https://tu-usuario.github.io/nombre-repo`!

### Opción 2: Usando Git

```bash
# Clonar o inicializar repositorio
git init
git add .
git commit -m "Initial commit: Café Aroma landing page"

# Conectar con GitHub
git remote add origin https://github.com/tu-usuario/cafe-aroma.git
git branch -M main
git push -u origin main
```

## 🔧 Desarrollo Local

Para trabajar localmente:

1. Clona el repositorio
2. Abre `index.html` en tu navegador
3. Para desarrollo avanzado, usa un servidor local:

```bash
# Con Python
python -m http.server 8000

# Con Node.js (live-server)
npx live-server
```

## 📱 Funcionalidades Incluidas

### ✅ WhatsApp Integration
- Botón flotante siempre visible
- Enlaces directos desde botones de "Ordenar"
- Mensajes pre-configurados

### ✅ Formulario de Contacto
- Validación de campos
- Envío via Formspree
- Mensajes de confirmación
- Estados de carga

### ✅ Navegación
- Menú responsive
- Scroll suave entre secciones
- Navbar que cambia al hacer scroll

### ✅ Animaciones
- Fade-in al hacer scroll
- Hover effects en tarjetas
- Botones con efectos visuales

## 🎨 Personalización

### Colores
Los colores principales están definidos con clases de TailwindCSS:
- `amber-600`: Color principal
- `amber-900`: Color oscuro
- `gray-900`: Backgrounds oscuros

### Fuentes
Usando la fuente por defecto del sistema. Para cambiar:

```css
body {
    font-family: 'Tu-Fuente', sans-serif;
}
```

### Imágenes
Todas las imágenes usan Unsplash. Para usar tus propias imágenes:
1. Sube las imágenes a tu repositorio en una carpeta `images/`
2. Reemplaza las URLs en `index.html`

## 📞 Soporte

Si necesitas ayuda:
1. Revisa la documentación de [TailwindCSS](https://tailwindcss.com)
2. Consulta la guía de [Formspree](https://formspree.io/guides)
3. Para GitHub Pages: [Documentación oficial](https://pages.github.com)

## 📄 Licencia

Este proyecto es de uso libre. Puedes modificarlo y usarlo para cualquier propósito comercial o personal.

---

**¡Tu cafetería online está lista! ☕✨**
