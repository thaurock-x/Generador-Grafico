<div align="center">
  <h1>📊 Generador de Gráficos Interactivos</h1>
  <p><strong>Crea, personaliza y analiza gráficos interactivos en segundos directamente desde tu navegador con procesamiento 100% local y privado.</strong></p>
  
[![Version](https://img.shields.io/badge/version-1.0.0-4c4fff.svg?style=for-the-badge)](https://github.com/tu-usuario/generador-graficos)
[![License](https://img.shields.io/badge/license-MIT-000000.svg?style=for-the-badge)](LICENSE)
[![Chart.js](https://img.shields.io/badge/Chart.js-FF6384?style=for-the-badge&logo=chartdotjs&logoColor=white)](https://www.chartjs.org/)
[![Tailwind CSS](https://img.shields.io/badge/Tailwind_CSS-38B2AC?style=for-the-badge&logo=tailwind-css&logoColor=white)](https://tailwindcss.com/)
[![Client-Side Privacy](https://img.shields.io/badge/privacy-100%25_client_side-00c853.svg?style=for-the-badge)](#-privacidad-y-seguridad)
  
  <br />
  <a href="#-características">Características</a> •
  <a href="#-métricas-y-análisis">Métricas</a> •
  <a href="#-privacidad-y-seguridad">Privacidad</a> •
  <a href="#-tecnologías-utilizadas">Tecnologías</a> •
  <a href="#-instalación-y-uso">Instalación</a> •
  <a href="#-licencia">Licencia</a>
</div>
---
## 📌 Descripción
**Generador de Gráficos Interactivos** es una herramienta web ligera y autónoma (*zero-backend*) diseñada para visualizar datos numéricos de forma rápida y personalizada sin depender de software pesado ni servicios en la nube. 
Permite ingresar valores, asignar colores a medida para cada serie, seleccionar diferentes representaciones visuales (barras, líneas, pastel) y realizar un análisis estadístico descriptivo automático, todo directamente dentro del navegador del usuario.
---
## ✨ Características Principales
- 📈 **Múltiples Tipos de Gráficos:** Alterna al instante entre gráficos de **Barra**, **Línea** y **Torta (Pastel)** mediante [Chart.js](https://www.chartjs.org/).
- 🎨 **Personalización Visual Completa:** Control individual de valores, etiquetas y selectores de color hexadecimal para cada punto de datos.
- 🧮 **Cálculo Estadístico Automático:** Genera métricas clave en tiempo real al procesar la información ingresada.
- 💾 **Exportación a CSV:** Descarga los datos configurados (etiquetas, valores y colores) en formato `.csv` estandarizado en un solo clic.
- 🌙 **Soporte para Modo Oscuro y Claro:** Interfaz adaptable con cambio de tema dinámico para mejorar la visibilidad.
- 🔒 **Garantía de Privacidad (Zero Data Transmission):** Todo el cómputo se realiza en el cliente. Ninguna información se envía a ningún servidor.
---
## 📐 Métricas y Análisis Estadístico
La aplicación calcula automáticamente las siguientes métricas estadísticas sobre los valores ingresados ($N$ elementos):

| Métrica | Fórmula / Descripción |
| :--- | :--- |
| **Promedio ($\bar{x}$)** | $\bar{x} = \frac{1}{N} \sum_{i=1}^{N} x_i$ |
| **Valor Máximo / Mínimo** | $\max(x_i)$ y $\min(x_i)$ |
| **Desviación Estándar ($\sigma$)** | $\sigma = \sqrt{\frac{1}{N} \sum_{i=1}^{N} (x_i - \bar{x})^2}$ |

---
## 🔒 Privacidad y Seguridad
- **Procesamiento Local:** Los datos no abandonan tu dispositivo; el renderizado del lienzo Canvas y los cálculos estadísticos corren en el motor de JavaScript de tu navegador.
- **Sin Dependencias de Backend:** No utiliza APIs externas para procesar o guardar los datos.
- **Cero Rastro:** Al cerrar la pestaña o refrescar la página, el estado de la aplicación se reinicia limpiamente.
---
## 🛠️ Tecnologías Utilizadas
- **HTML5 Canvas & JavaScript Vanilla (ES6+):** Lógica nativa de renderizado y cálculos dinámicos.
- **Chart.js:** Biblioteca de renderizado de gráficos reactivos.
- **Tailwind CSS (via CDN):** Estilizado utilitario responsivo para la maquetación.
- **html2canvas:** Soporte para captura de lienzo.
---
## 🚀 Instalación y Uso Local
No requiere la instalación de módulos con `npm` ni la configuración de servidores web.
1. **Clonar el repositorio:**
   ```bash
   git clone [https://github.com/tu-usuario/generador-graficos.git](https://github.com/tu-usuario/generador-graficos.git)
   ```
   ---

### ​📄 Licencia:

<div align="center">
Desarrollado con 💚 por <strong>Thaurock</strong>
</div>

