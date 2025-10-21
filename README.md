
# Analizador de Estadísticas de Basquet

Este es un proyecto en Streamlit diseñado para descargar, procesar y visualizar estadísticas de partidos de básquet provenientes del sistema de Cabb.

La aplicación permite a un usuario encontrar partidos usando un buscador y luego analizar un partido específico introduciendo su `ID`.

## Características Principales

* **Buscador de Partidos:** Un panel desplegable que permite filtrar partidos por Año, Competencia, Categoría, Equipo, Fase y Grupo, facilitando encontrar el `ID` de un partido.
* **Análisis por Partido:** Al ingresar un `ID` de partido, la app descarga los datos y los presenta en tres pestañas:
  1. **Resumen:** Muestra los marcadores finales, la evolución del tanteador, la diferencia de puntos, el tiempo que cada equipo estuvo en ventaja y otras estadísticas clave del partido.
  2. **Estadísticas por jugador:** Tablas detalladas con el boxscore tradicional y avanzado (basado en el Play-by-Play) para cada jugador.
  3. **Estadística por Quintetos:** Análisis de rendimiento (+/-) de las diferentes alineaciones de 5 jugadores que estuvieron en cancha.

## Requisitos

El proyecto está construido en Python y requiere las siguientes librerías principales:

* `streamlit`
* `pandas`
* `altair`
* `requests`
* `numpy`
* `openpyxl` (para leer el archivo Excel)

Puedes instalarlas usando:

```bash
pip install streamlit pandas altair requests numpy openpyxl
```
