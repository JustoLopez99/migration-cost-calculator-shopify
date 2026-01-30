# Shopify Migration Cost Calculator 🚀

Sección personalizada de Shopify que calcula el coste estimado de una migración a Shopify en función del número de clientes, pedidos y productos.

## ✨ Características Principales

* **Interfaz Interactiva**: Tres sliders de rango para seleccionar el volumen de Clientes, Pedidos y Productos.
* **Lógica de Precio Inteligente**: El sistema calcula automáticamente el presupuesto basándose en el valor más alto de los tres campos, siguiendo una tabla de niveles (tiers).
* **Formulario Nativo de Shopify**: Integración total con el motor de formularios de Shopify (`form 'contact'`). Los datos de la calculadora se envían como campos personalizados (`hidden inputs`) directamente al email del administrador.
* **Totalmente Configurable**: Control absoluto desde el Theme Editor de Shopify:
    * Gestión de tramos de precios mediante **bloques** (sin tocar código).
    * Personalización de colores (sliders, botones, textos).
    * Configuración de límites (min, max, step) y textos de éxito.
* **Globalización**: Adaptación automática de moneda y capacidad de aplicar incrementos de precio por país (ej: +20% en USA) utilizando el objeto nativo de localización de Shopify.

## 🚀 Instalación

1.  Carga el archivo `.liquid` en la carpeta `sections/` de tu tema de Shopify.
2.  Desde el **Personalizador de Temas**, añade la sección "Migration Cost Calculator".
3.  Configura tus tramos de precios añadiendo bloques de tipo "Price Tier".
4.  ¡Listo para recibir leads!
