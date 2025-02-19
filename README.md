# Análisis de datos de partidas de CS:GO

## Descripción del proyecto
Este repositorio contiene un notebook de Jupyter con el análisis de datos de más de 79.000 registros de partidas de Counter-Strike: Global Offensive (CS:GO). El objetivo es construir un modelo predictivo de Machine Learning para analizar el rendimiento de los jugadores y determinar la probabilidad de supervivencia en cada ronda.

Los datos provienen de archivos de replays extraídos mediante un scrapper, los cuales han sido preprocesados y almacenados en un archivo CSV. Cada fila del dataset representa a un jugador en una partida y contiene 29 variables que describen sus acciones y estadísticas dentro del juego.

## Objetivos del proyecto
- Analizar la relación entre las características de los jugadores y sus equipos.
- Identificar patrones de victoria y factores clave en la supervivencia de los jugadores.
- Construir modelos de Machine Learning para predecir la probabilidad de supervivencia en una ronda.
- Explorar el impacto de mapas, equipos y estrategias en los resultados de las partidas.

## Dataset
- **Registros**: 79.157 jugadores en distintas partidas.
- **Número de partidas registradas**: 333.
- **Número de rondas**: 7.916.
- **Características principales**:
  - Identificación de partidas y rondas.
  - Información del equipo y bando (Terrorista o Contra-Terrorista).
  - Variables de desempeño: kills, headshots, asistencias, distancia recorrida.
  - Valor de equipamiento y tipo de arma utilizada.
  - Supervivencia del jugador al final de la ronda.

## Contenido del repositorio
```
/
├── Informe_Técnico_FMY0100.ipynb   # Notebook con el análisis de datos y modelado predictivo
├── Anexo ET_demo_round_traces.csv  # Conjunto de datos
```

## Requisitos
Para ejecutar el notebook, se requiere tener instalados:
```cli
pip install pandas numpy matplotlib seaborn scikit-learn
```
