# Dashboard Geoespacial - Colonias de Zapopan

Dashboard interactivo que visualiza datos geoespaciales de colonias específicas en Zapopan, Jalisco, México.

## 🗺️ Colonias Incluidas

- Mesa Colorada (Oriente y Poniente)
- Nextipac (Zapopan)
- San Juan de Ocotan
- San Isidro (Zapopan)
- San Esteban (Zapopan)

## 📊 Características

- **Visualización Interactiva**: Mapa interactivo con múltiples capas
- **Estadísticas en Tiempo Real**: Tarjetas con métricas clave
- **Gráficos Dinámicos**: Visualización de delitos y población
- **Diseño Responsivo**: Optimizado para desktop, tablet y móvil
- **Múltiples Capas**:
  - Colonias (polígonos)
  - Rutas de transporte público
  - Delitos registrados
  - Establecimientos de recreación
  - Centros de cuidado

## 🚀 Uso

### Ver en GitHub Pages

El dashboard está disponible en: [GitHub Pages](https://[tu-usuario].github.io/[tu-repo]/)

### Uso Local

1. Clona el repositorio
2. Abre `index.html` en tu navegador
3. O usa un servidor local:
   ```bash
   python -m http.server 8000
   ```
   Luego abre `http://localhost:8000` en tu navegador

## 📁 Estructura de Archivos

```
.
├── index.html                    # Dashboard principal
├── colonias_filtradas.geojson   # Datos de colonias
├── rutas_filtradas.geojson      # Rutas de transporte
├── delitos_filtrados.csv        # Datos de delitos
├── recreaciones_filtradas.csv   # Establecimientos de recreación
├── centros_de_cuidado_filtrados.xlsx  # Centros de cuidado
└── README.md                    # Este archivo
```

## 🛠️ Tecnologías

- **Leaflet.js**: Visualización de mapas
- **Chart.js**: Gráficos interactivos
- **PapaParse**: Procesamiento de CSV
- **SheetJS**: Lectura de archivos Excel
- **OpenStreetMap**: Capa base del mapa

## 📱 Diseño Responsivo

El dashboard se adapta automáticamente a diferentes tamaños de pantalla:
- **Desktop**: Layout de 3 columnas (stats, mapa, gráficos)
- **Tablet**: Layout vertical con paneles colapsables
- **Móvil**: Vista optimizada con botones de toggle

## 📄 Licencia

Este proyecto es de uso público para visualización de datos geoespaciales.

## 👤 Autor

Dashboard creado para visualización de datos geoespaciales de Zapopan, Jalisco.
