# 🌐 Portal Web - Deb&Lopers

Este directorio contiene el portal web completo de Deb&Lopers, organizado para GitHub Pages.

## 📂 **Estructura**

```
github-pages/
├── index.html          → 🏠 Página principal (Confirmed Mail + Theme Toggle)
└── qr/                 → 📱 Sistema completo de QR Codes
    ├── index.html      → 🎯 Panel principal QR
    ├── entrance.html   → 🚪 QR de entrada al restaurante
    ├── tables.html     → 🍽️ QR codes de las 5 mesas
    └── tips.html       → 💰 QR codes de propinas
```

## 🌐 **URLs de GitHub Pages**

Cuando esté desplegado en GitHub Pages:

- **🏠 Portal Principal:** `https://usuario.github.io/primer-parcial-pps/github-pages/`
- **📱 Sistema QR:** `https://usuario.github.io/primer-parcial-pps/github-pages/qr/`
- **🚪 QR Entrada:** `https://usuario.github.io/primer-parcial-pps/github-pages/qr/entrance.html`
- **🍽️ QR Mesas:** `https://usuario.github.io/primer-parcial-pps/github-pages/qr/tables.html`  
- **💰 QR Propinas:** `https://usuario.github.io/primer-parcial-pps/github-pages/qr/tips.html`

## ✨ **Características**

### **🎨 Diseño Consistente**
- **Theme Toggle** (Light/Dark) en todas las páginas
- **Navegación fluida** entre secciones  
- **Estilos unificados** con variables CSS
- **Responsive design** para todos los dispositivos
- **Efectos visuales** modernos (glassmorphism, hover states)

### **📧 Confirmed Mail (Página Principal)**
- ✅ **Funcionalidad original preservada** sin cambios
- ✅ **Theme selector** Light/Dark añadido
- ✅ **Navegación** hacia el sistema QR
- ✅ **Estilos mejorados** manteniendo compatibilidad
- ✅ **Avatar loading** y token parsing funcionando

### **📱 Sistema QR**
- ✅ **11 QR Codes funcionales** (1 entrada + 5 mesas + 5 propinas)
- ✅ **Deep links reales:** `deblopers://table/1`, `deblopers://entrance`, etc.
- ✅ **QR images reales** via qr-server.com API
- ✅ **Imprimibles** con estilos optimizados para impresión
- ✅ **Iconografía mejorada** - Mesa 4 con silla de ruedas 🦽

## 🔗 **Deep Links Configurados**

### **Entrada al Restaurante:**
```
deblopers://entrance
```

### **Mesas del Restaurante:**
```
deblopers://table/1    # Mesa 1 (4 personas, estándar)
deblopers://table/2    # Mesa 2 (2 personas, estándar)  
deblopers://table/3    # Mesa 3 (6 personas, VIP)
deblopers://table/4    # Mesa 4 (4 personas, accesibilidad 🦽)
deblopers://table/5    # Mesa 5 (8 personas, VIP)
```

### **Propinas por Mesa:**
```
deblopers://tip/1      # Propina Mesa 1
deblopers://tip/2      # Propina Mesa 2
deblopers://tip/3      # Propina Mesa 3
deblopers://tip/4      # Propina Mesa 4 🦽
deblopers://tip/5      # Propina Mesa 5
```

## 🎯 **Cumplimiento del Enunciado**

- ✅ **Generación de QR codes** - 11 códigos funcionales
- ✅ **Lectura de QR codes** - Deep links automáticos  
- ✅ **QR de mesa** - Funcionalidades específicas por perfil
- ✅ **QR de entrada** - Lista de espera y encuestas
- ✅ **QR de propinas** - 5 niveles de satisfacción (0% a 20%)
- ✅ **Disponibilidad completa** - Impresos, en pantalla y digitales

## 🛠️ **Tecnologías Utilizadas**

- **HTML5 Semántico**
- **CSS3 Avanzado** (Variables, Grid, Flexbox, Animations)
- **JavaScript Vanilla** (Theme management, Local storage)
- **QR Server API** - Generación de códigos QR reales
- **Glassmorphism Design** - Efectos visuales modernos
- **Print CSS** - Estilos optimizados para impresión

## 📱 **Uso del Sistema**

### **Para Administradores:**
1. Imprime las páginas QR desde el navegador
2. Coloca los QR en las ubicaciones correspondientes
3. Configura GitHub Pages para acceso público

### **Para Clientes:**
1. Escanea cualquier QR con la cámara
2. Se abre automáticamente la app Deb&Lopers  
3. Accede a las funcionalidades según el QR escaneado

## 🎨 **Personalización**

Todas las páginas comparten las mismas variables CSS para fácil personalización:

```css
:root {
    --bg-primary: linear-gradient(135deg, #667eea 0%, #764ba2 100%);
    --bg-card: #ffffff10;
    --text-primary: #fff;
    --text-secondary: rgba(255,255,255,0.85);
    --border-color: #ffffff22;
    --success-color: #00dfa0;
    --shadow: 0 10px 35px -8px rgba(0,0,0,.55);
}
```

---

**🎉 Portal web completo y listo para producción!**
