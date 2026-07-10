# OpenAQ Monitor — Gestión Ambiental IoT

## 📋 Descripción

**OpenAQ Monitor** es un dashboard profesional de monitoreo ambiental en tiempo real que integra datos de calidad del aire desde la red global de OpenAQ. Proporciona visualización de estaciones de monitoreo IoT, indicadores de calidad del aire (AQI) y gestión centralizada de dispositivos.

## ✨ Características principales

- **Dashboard en tiempo real**: Visualización de datos de calidad del aire actualizados constantemente
- **Índice de Calidad del Aire (AQI)**: Promedio global con indicadores de estado (Bueno, Moderado, Malo)
- **Gestión de dispositivos**: Seguimiento de 145+ estaciones de monitoreo conectadas
- **Mapa de calidad**: Visualización geográfica de las mediciones ambientales
- **Histórico de datos**: Acceso a datos históricos para análisis temporal
- **Sistema de alertas**: Notificaciones de eventos ambientales relevantes
- **Exportación de datos**: Capacidad de descargar datos para análisis externo
- **Interfaz multiidioma**: Soporte para español como idioma principal

## 📁 Estructura del proyecto

```
web/
├── index.html          # Estructura HTML del dashboard
├── styles.css          # Sistema de diseño y estilos
└── README.md          # Este archivo
```

## 🛠️ Requisitos técnicos

- Navegador web moderno (Chrome, Firefox, Safari, Edge)
- Conexión a Internet para acceso a API OpenAQ
- JavaScript habilitado

## 🚀 Cómo usar

1. **Abrir en navegador**: Abra el archivo `index.html` en su navegador web
2. **Navegar el dashboard**: Use la barra lateral para acceder a diferentes secciones
3. **Seleccionar región**: Cambie la región desde el selector en la esquina superior derecha
4. **Monitorear datos**: Visualice indicadores en tiempo real, alertas y datos de dispositivos

## 🎨 Diseño y Paleta de colores

### Sistema de diseño: "Noche-Instrumento"

**Colores principales**:
- **Sidebar**: Gradiente Navy (fondo oscuro profesional)
- **Contenido**: Fondo claro con cards blancos
- **Acentos**: Azul cielo (#2f7dd1), Teal (#17a398)

**Escala AQI**:
- 🟢 **Bueno**: Verde (#3fa66a)
- 🟡 **Moderado**: Ámbar (#d9a92a)
- 🔴 **Malo**: Naranja-rojo (#d9622a)

### Tipografía

- **Títulos**: Space Grotesk (500, 600, 700)
- **Texto**: Inter (400, 500, 600, 700)
- **Datos**: IBM Plex Mono (números y métricas)

## 📊 Secciones del dashboard

### Barra lateral (Sidebar)
- **Logo**: OpenAQ Monitor con identificación visual
- **Navegación General**: Dashboard, Mapa de calidad, Dispositivos
- **Monitoreo**: Histórico, Alertas activas, Exportar datos
- **Pie de página**: Información de fuente de datos y última actualización

### Área principal
- **Header**: Título descriptivo, región seleccionada, notificaciones y perfil
- **KPIs**: 
  - Promedio global de AQI (visualización radial)
  - Total de dispositivos
  - Métricas de monitoreo

## 🌐 API utilizada

**OpenAQ API**: Red global de estaciones de monitoreo de calidad del aire
- Actualización: Cada 3 minutos
- Cobertura: Múltiples regiones (Ecuador como región predeterminada)
- Datos: PM2.5, PM10, O3, NO2, CO y otros contaminantes

## 💻 Especificaciones técnicas

**Variables CSS principales**:
- Ancho sidebar: 248px
- Radio de bordes (lg): 18px
- Sombra elevada: `0 10px 30px -12px rgba(16, 26, 44, 0.18)`

**Características de accesibilidad**:
- Etiquetas ARIA para lectores de pantalla
- Navegación con teclado
- Indicadores visuales claros de enfoque

## 👤 Información del proyecto

- **Nombre**: OpenAQ Monitor
- **Versión**: 1.0
- **Enfoque**: Gestión ambiental y monitoreo IoT
- **Usuario actual**: Cristian Zambrano
- **Región predeterminada**: Ecuador

## 🔔 Panel de control

El dashboard proporciona acceso rápido a:
- Notificaciones ambientales
- Configuración de usuario (avatar)
- Cambio de región de monitoreo
- Métricas agregadas de la red

## 📝 Notas de desarrollo

- El proyecto utiliza un enfoque moderno con CSS Grid y Flexbox
- Scroll suave habilitado globalmente
- Diseño responsive preparado para múltiples tamaños de pantalla
- Iconos Unicode para interfaz limpia y accesible

---

**Última actualización**: 2026-07-09
