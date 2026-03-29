# Dashboard Moderno

Dashboard interactivo construido en HTML puro, CSS y JavaScript vanilla. Inspirado en el **Dashboard Design System** desarrollado en Figma.

## Características

- **Barra de navegación** fija con badge de notificaciones y avatar
- **Tarjeta de perfil** con estadísticas (Proyectos, Usuarios, Uptime)
- **Menú lateral** con 6 ítems y estado activo
- **3 tarjetas de métricas** — Usuarios activos, Ingresos, Pedidos
- **Gráfica en tiempo real** con Canvas API — se actualiza cada 800ms
- **Tabla de registros** con checkboxes, paginación y badges de estado
- **Botones de acción** — Agregar, Editar, Eliminar con modal
- **Modal de formulario** — crear y editar registros

## Paleta de colores (Design System)

| Token | Valor | Uso |
|-------|-------|-----|
| `slate/900` | `#1e293b` | Nav, texto primario |
| `blue/300` | `#38bdf8` | Acento, gráfica |
| `blue/500` | `#3b82f6` | Botón primario, activo |
| `green/500` | `#22c55e` | Deltas positivos, live |
| `amber/500` | `#f59e0b` | Botón warning |
| `red/500` | `#ef4444` | Botón danger, badge |

## Uso

Abre `dashboard.html` directamente en el navegador — no requiere servidor ni dependencias.

```bash
# Clonar el repositorio
git clone https://github.com/juancamilo49/dashboard-moderno.git
cd dashboard-moderno

# Abrir en el navegador
open dashboard.html
```

## Recursos relacionados

- [Dashboard en Figma](https://www.figma.com/design/kWor5lha6WaNrQuQ70rQHK)
- [Design System en Figma](https://www.figma.com/design/uXHjA9ogQ22WdZwWUd5wRr)
