# ⚡ Bit&Volt - E-commerce de Electrónica

**Bit&Volt** es una plataforma de comercio electrónico web diseñada para la venta de componentes electrónicos y accesorios tecnológicos. Este proyecto simula un flujo de compra completo, desde la selección de productos hasta una pasarela de pago interactiva, todo desarrollado con tecnologías web estándar y almacenamiento local.

## 🚀 Características Principales

* **🛒 Carrito de Compras Persistente:** Los productos se guardan en `localStorage`, permitiendo que el usuario cierre el navegador sin perder su selección.
* **💳 Checkout Interactivo:**
    * **Formato en tiempo real:** Los campos de tarjeta de crédito agregan espacios automáticamente cada 4 dígitos.
    * **Validación de fechas:** Inserción automática de la barra `/` en el campo de expiración (MM/AA).
    * **Tarjeta Visual:** Una representación gráfica de la tarjeta que se actualiza mientras el usuario escribe.
* **🔐 Simulación de Pagos:** Sistema de *overlay* con animaciones de carga que simula la conexión con un banco y validación de fondos.
* **📱 Diseño Responsivo:** Interfaz adaptada a móviles y escritorio utilizando **Bootstrap 5**.
* **👤 Gestión de Sesión:** Verificación básica de sesión de usuario para acceder al checkout.

## 🛠️ Tecnologías Utilizadas

* **HTML5:** Estructura semántica.
* **CSS3:** Estilos personalizados y animaciones (Keyframes).
* **JavaScript (Vanilla ES6):** Lógica del carrito, manipulación del DOM y validaciones con **Regex**.
* **Bootstrap 5.3:** Framework de diseño y componentes (Modales, Badges, Grid).
* **LocalStorage:** Persistencia de datos del lado del cliente.

## 📂 Estructura del Proyecto

Bit-Volt/
├── css/
│   └── index.css       # Estilos globales y específicos
├── js/
│   └── main.js         # Lógica principal (Navbar, Footer, Carrito)
├── images/
│   └── Logo/           # Recursos gráficos
├── pages/
│   ├── cart.html       # Vista del carrito de compras
│   ├── checkout.html   # Formulario de pago con validaciones
│   ├── login.html      # Inicio de sesión
│   └── compra-exitosa.html # Pantalla de confirmación
└── index.html          # Página de inicio (Catálogo)

## 🔧 Instalación y Uso

Este proyecto es estático, por lo que no requiere instalación de dependencias de backend (Node.js, Python, etc.).

1.  **Clonar el repositorio:**
    ```bash
    git clone [https://github.com/TU_USUARIO/Bit-Volt.git](https://github.com/TU_USUARIO/Bit-Volt.git)
    ```
2.  **Ejecutar:**
    * Puedes abrir el archivo `index.html` directamente en tu navegador.
    * **Recomendado:** Usar la extensión "Live Server" en VS Code para simular un servidor local y evitar problemas con rutas absolutas.

## 📄 Licencia

Este proyecto está bajo la Licencia MIT - mira el archivo [LICENSE](LICENSE) para más detalles.

---
⌨️ con ❤️ por [Tu Nombre] para la materia de [Nombre de tu materia]
