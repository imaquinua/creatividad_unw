# creatividad_unw

Dashboard interactivo de seguimiento de producción de piezas creativas para UNW.

## 🌐 Demo en Vivo

**URL de Producción**: https://creatividad-unw-dashboard-d7cuh787n-chumbis-projects.vercel.app

El dashboard está desplegado en Vercel y se actualiza automáticamente con cada push a la rama `main`.

## 🎨 Características

### Dashboard Completo
- **114 tareas** extraídas de 6 hojas de cálculo diferentes
- **4 vistas especializadas**: General, Por Responsable, Por Estado, Por Producto
- **Filtros avanzados**: Producto, Estado, Responsable, Rango de fechas, Búsqueda
- **Actualización dinámica** en tiempo real

### Vista General
- Estadísticas globales (Total, Pendientes, En Proceso, Completadas)
- Gráfico de dona: Distribución por estado
- Gráfico de barras: Progreso por producto
- Gráfico Top 6 Responsables
- Tabla completa con todas las tareas

### Vista Por Responsable (Bento Box)
- **Diseño tipo Bento**: Cajas de tamaño proporcional a la carga de trabajo
- 4 tamaños diferentes según cantidad de tareas (1x1, 2x1, 2x2, 3x2)
- Estadísticas individuales por responsable
- Barras de progreso visuales
- Porcentaje de completitud prominente

### Vista Por Estado
- Tarjetas grandes con cantidad por estado
- Tabla filtrada por estado actual
- Visualización clara de distribución

### Vista Por Producto
- Gráfico de barras apiladas (Pendiente/Proceso/Listo)
- Tabla resumen con totales y porcentajes
- Barras de progreso por producto

## 🚀 Uso

### Iniciar servidor local

```bash
python3 -m http.server 8000
```

Luego abre tu navegador en: `http://localhost:8000/dashboard.html`

### Archivos principales

- `dashboard.html` - Dashboard interactivo completo (HTML + CSS + JS)
- `data.json` - Datos procesados de 114 tareas
- `PENDIENTES PRODUCTO - EVENTO - CONSOLIDADO.xlsx` - Archivo Excel fuente

## 🎯 Productos incluidos

- **Eventos - Audiovisual 3**: 35 tareas
- **Salud - Audiovisual 3**: 26 tareas
- **NID - Nahuel**: 24 tareas
- **CGT - Charlie**: 17 tareas
- **LN - Charlie**: 8 tareas
- **Transversal**: 4 tareas

## 📊 Estados de tareas

- ✅ **Listo**: 45 tareas
- ⏳ **Pendiente**: 39 tareas
- 🔄 **En Proceso**: 8 tareas
- ❌ **Cancelado**: 3 tareas

## 🔍 Filtros disponibles

- **Por Producto**: Filtra por cualquier producto específico
- **Por Estado**: Pendiente, En Proceso, Listo, Cancelado
- **Por Responsable**: Filtra por cualquier responsable
- **Rango de fechas**: Filtra por fecha desde/hasta
- **Búsqueda libre**: Busca en descripciones, responsables y detalles

## 💡 Tecnologías

- HTML5
- CSS3 (Grid, Flexbox, Animations)
- JavaScript Vanilla
- Canvas API para gráficos
- Diseño responsive

## 🎨 Características de diseño

- Diseño minimalista y limpio
- Paleta de colores consistente
- Animaciones suaves
- Efectos hover interactivos
- Responsive para móviles
- Bento box layout para responsables

## 📝 Licencia

Este proyecto es privado y pertenece a UNW.
