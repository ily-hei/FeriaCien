# EcoSmart - Tanque de Basura Inteligente

Un sitio web moderno y responsivo para presentar el tanque de basura inteligente con tecnología sin contacto y monitoreo IoT.

## 🚀 Características del Sitio Web

### ✨ Funcionalidades Principales
- **Diseño Moderno**: Interfaz limpia y profesional con animaciones suaves
- **Totalmente Responsivo**: Optimizado para dispositivos móviles, tablets y desktop
- **Navegación Intuitiva**: Menú fijo con scroll suave entre secciones
- **Formulario de Contacto**: Sistema completo de solicitud de demo y compra
- **Mapa Interactivo**: Integración con Google Maps para mostrar ubicaciones de tanques
- **Animaciones CSS**: Efectos visuales atractivos y profesionales

### 📱 Secciones del Sitio
1. **Página de Inicio**: Presentación del producto con llamadas a la acción
2. **Características**: Detalles técnicos del tanque inteligente
3. **App Móvil**: Información sobre la aplicación de monitoreo
4. **Mapa**: Visualización de tanques distribuidos con OpenStreetMap (sin API key)
5. **Contacto**: Formulario completo para solicitudes comerciales

## 🛠️ Tecnologías Utilizadas

- **HTML5**: Estructura semántica y accesible
- **CSS3**: Estilos modernos con Flexbox y Grid
- **JavaScript ES6+**: Funcionalidad interactiva y animaciones
- **OpenStreetMap (Leaflet)**: Mapa interactivo gratuito sin API key
- **Font Awesome**: Iconografía profesional
- **Google Fonts**: Tipografía moderna (Inter)

## 📁 Estructura del Proyecto

```
EcoSmart/
├── index.html              # Página principal
├── css/
│   └── styles.css          # Estilos principales
├── js/
│   └── script.js           # Funcionalidad JavaScript
├── maps/
│   └── map-config.js       # Configuración del mapa
├── images/
│   └── placeholder.txt     # Información sobre imágenes
└── README.md              # Este archivo
```

## 🚀 Instalación y Uso

### Requisitos Previos
- Navegador web moderno (Chrome, Firefox, Safari, Edge)
- Servidor web local (opcional, para desarrollo)

### Instalación Rápida
1. **Clona o descarga** el proyecto
2. **Abre** `index.html` en tu navegador
3. **¡Listo!** El sitio está funcionando

### Para Desarrollo Local
```bash
# Opción 1: Servidor Python
python -m http.server 8000

# Opción 2: Servidor Node.js
npx http-server

# Opción 3: Live Server (VS Code)
# Instala la extensión "Live Server" y haz clic derecho en index.html
```

## 🗺️ Mapa Interactivo con OpenStreetMap

### ✅ Sin API Key Requerida
El sitio utiliza **OpenStreetMap** a través de **Leaflet**, que es completamente gratuito y no requiere configuración de API key.

### Características del Mapa
- **Marcadores personalizados** por estado del tanque (Lleno, Vacío, Mantenimiento)
- **Rutas de recolección** visualizadas con colores diferentes
- **Controles interactivos** para filtrar por tipo de tanque
- **Popups informativos** con detalles de cada ubicación
- **Zoom y navegación** completamente funcionales

### Personalizar Ubicaciones
Edita `maps/map-config.js` para:
- Cambiar ubicaciones de tanques
- Modificar rutas de recolección
- Personalizar colores y estados
- Ajustar el centro del mapa

## 🎨 Personalización

### Colores del Tema
Los colores principales están definidos en `:root` en `styles.css`:
```css
:root {
    --primary-color: #2E7D32;    /* Verde principal */
    --secondary-color: #FF6F00;  /* Naranja secundario */
    --accent-color: #00BCD4;     /* Azul acento */
}
```

### Contenido
- **Texto**: Edita directamente en `index.html`
- **Imágenes**: Reemplaza los placeholders en la carpeta `images/`
- **Información de contacto**: Modifica la sección de contacto
- **Datos de la empresa**: Actualiza el footer

## 📱 Características Responsivas

### Breakpoints
- **Desktop**: > 768px
- **Tablet**: 768px - 480px
- **Mobile**: < 480px

### Optimizaciones Móviles
- Menú hamburguesa en dispositivos pequeños
- Imágenes adaptativas
- Botones táctiles optimizados
- Texto legible en todas las pantallas

## 🔧 Funcionalidades JavaScript

### Navegación
- Scroll suave entre secciones
- Menú móvil responsivo
- Indicador de sección activa

### Formulario de Contacto
- Validación en tiempo real
- Notificaciones de éxito/error
- Prevención de envío duplicado

### Mapa Interactivo (OpenStreetMap)
- Marcadores personalizados por estado
- Controles de filtrado
- Popups informativos
- Rutas de recolección
- Sin API key requerida

### Animaciones
- Efectos de entrada al hacer scroll
- Transiciones suaves
- Animaciones CSS optimizadas

## 🌐 Compatibilidad

### Navegadores Soportados
- ✅ Chrome 60+
- ✅ Firefox 55+
- ✅ Safari 12+
- ✅ Edge 79+

### Dispositivos
- ✅ Desktop (Windows, macOS, Linux)
- ✅ Tablet (iPad, Android)
- ✅ Mobile (iOS, Android)

## 📈 Optimizaciones de Rendimiento

### CSS
- Variables CSS para consistencia
- Flexbox y Grid para layouts eficientes
- Animaciones optimizadas con `transform`
- Media queries para responsividad

### JavaScript
- Event listeners optimizados
- Debouncing en eventos de scroll
- Lazy loading preparado para imágenes
- Código modular y reutilizable

## 🚀 Próximas Mejoras

### Funcionalidades Adicionales
- [ ] Integración con backend real
- [ ] Sistema de autenticación
- [ ] Panel de administración
- [ ] Notificaciones push
- [ ] PWA (Progressive Web App)

### Optimizaciones
- [ ] Compresión de imágenes
- [ ] Minificación de CSS/JS
- [ ] Service Worker para cache
- [ ] SEO optimizado

## 📞 Soporte

### Documentación
- Comentarios detallados en el código
- Estructura modular para fácil mantenimiento
- Variables CSS para personalización rápida

### Contacto
Para soporte técnico o consultas sobre el proyecto:
- **Email**: info@ecosmart.com
- **Teléfono**: +1 (555) 123-4567

## 📄 Licencia

Este proyecto está desarrollado para fines educativos y comerciales. Todos los derechos reservados.

---

**EcoSmart Solutions** - Revolucionando la gestión de residuos con tecnología inteligente y sostenible.
