# Simulador de Energía Eléctrica en una Red de Distribución

Este proyecto implementa un simulador para modelar el flujo de energía eléctrica en una red de distribución entre varias ciudades. El simulador calcula la cantidad de energía que llega a cada ciudad, identifica las rutas más eficientes y muestra visualmente el flujo de energía en la red, considerando pérdidas debido a la resistencia y distancia de cada conexión.

## Características

- **Modelo de red**: Representación de una red de ciudades y conexiones con un grafo.
- **Cálculo de rutas**: Uso del algoritmo de Dijkstra para encontrar las rutas más eficientes.
- **Simulación de pérdidas de energía**: Cálculo de pérdidas basadas en la distancia y la resistencia de cada conexión.
- **Visualización**: Visualización gráfica de la red, rutas eficientes y pérdidas de energía usando Matplotlib.

## Requisitos

Asegúrate de tener instaladas las siguientes bibliotecas de Python:

- `networkx`: Para la creación y manipulación de grafos.
- `matplotlib`: Para la visualización gráfica de la red de distribución.

Puedes instalarlas usando el siguiente comando:

```bash
pip install networkx matplotlib
