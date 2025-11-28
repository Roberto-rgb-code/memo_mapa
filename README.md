# Dashboard Geoespacial - Colonias de Zapopan

Dashboard interactivo que visualiza datos geoespaciales de colonias específicas en Zapopan, Jalisco, México.

## 🗺️ Colonias Incluidas

- Mesa Colorada (Oriente y Poniente)
- Nextipac (Zapopan)
- San Juan de Ocotan
- San Isidro (Zapopan)
- San Esteban (Zapopan)

## 📊 Características

- **Visualización 3D**: Mapa interactivo con soporte 3D (pitch, bearing)
- **Vista Satelital**: Mapa base satelital con calles de Mapbox
- **Estadísticas en Tiempo Real**: Tarjetas con métricas clave
- **Gráficos Dinámicos**: Visualización de delitos y población
- **Diseño Responsivo**: Optimizado para desktop, tablet y móvil
- **Navegación por Colonias**: Selector para hacer zoom automático a colonias específicas
- **Múltiples Capas**:
  - Colonias (polígonos con relleno y borde)
  - Rutas de transporte público
  - Delitos registrados
  - Establecimientos de recreación
  - Centros de cuidado
  - Escuelas

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
├── escuelas_filtradas.csv            # Escuelas
└── README.md                    # Este archivo
```

## 🛠️ Tecnologías

- **Mapbox GL JS**: Visualización de mapas 3D
- **Chart.js**: Gráficos interactivos
- **PapaParse**: Procesamiento de CSV
- **SheetJS**: Lectura de archivos Excel
- **Mapbox**: Capa base del mapa con soporte 3D

## 🔑 Configuración de Mapbox

Este proyecto usa Mapbox GL JS para visualización 3D. Necesitas un token de Mapbox:

1. Crea una cuenta en [Mapbox](https://account.mapbox.com/)
2. Obtén tu token de acceso en [Access Tokens](https://account.mapbox.com/access-tokens/)
3. Reemplaza el token en `index.html` (línea con `mapboxgl.accessToken`)

**Nota**: El token actual es un token público de ejemplo que puede tener limitaciones. Se recomienda usar tu propio token para producción.

## 📱 Diseño Responsivo

El dashboard se adapta automáticamente a diferentes tamaños de pantalla:
- **Desktop**: Layout de 3 columnas (stats, mapa, gráficos)
- **Tablet**: Layout vertical con paneles colapsables
- **Móvil**: Vista optimizada con botones de toggle

## 📄 Licencia

Este proyecto es de uso público para visualización de datos geoespaciales.

## 👤 Autor

Dashboard creado para visualización de datos geoespaciales de Zapopan, Jalisco.
