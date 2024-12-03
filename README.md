# Sistema Multiagente de Gestión de Residuos Urbanos

Este repositorio contiene un sistema de simulación interactivo desarrollado con **Python** y **Pygame**, cuyo objetivo es gestionar la recolección y clasificación de residuos urbanos mediante agentes inteligentes.

## Descripción

El proyecto implementa un modelo multiagente en el que:

- **Puntos de residuos** se generan aleatoriamente en un entorno urbano simulado.
- Los **agentes de recolección** se encargan de recoger los residuos y llevarlos al camión de transporte.
- El **camión de transporte** clasifica los residuos y los entrega a centros de tratamiento específicos.
- Los **agentes de clasificación** procesan los residuos en los centros correspondientes según su tipo (orgánico, inorgánico u otro).

La simulación incluye algoritmos como **A*** para el movimiento de los agentes y una visualización interactiva de todo el proceso.

## Contenido

- [`caso1.py`](caso1.py): El código fuente de la simulación.
- [`caso1.mp4`](caso1.mp4): Video demostrativo que muestra la ejecución de la simulación.

## Funcionalidades

- **Generación aleatoria de puntos de residuos**: Cada punto tiene un tipo (orgánico, inorgánico u otro) y una posición dentro del mapa.
- **Algoritmo A***: Los agentes calculan rutas óptimas para llegar a los residuos o a los centros de tratamiento.
- **Clasificación de residuos**: Los residuos se entregan a los centros correspondientes para ser procesados.
- **Agentes interactivos**: Los agentes muestran estados visuales como parpadeo para indicar éxito o fallo en sus tareas.

## Cómo ejecutar

1. Instalar las dependencias necesarias:
   ```bash
   pip install pygame numpy
   ```

2. Ejecutar el archivo `caso1.py`:
   ```bash
   python caso1.py
   ```

3. La simulación se abrirá en una ventana interactiva. Observa cómo los agentes se mueven, recogen residuos y los entregan.

## Estructura de la Simulación

- **Puntos de residuos**: Representan los desechos generados en el entorno urbano.
- **Agentes de recolección**: Robots encargados de recoger los residuos y transportarlos al camión.
- **Camión de transporte**: Vehículo que lleva los residuos a los centros de tratamiento.
- **Centros de tratamiento**: Infraestructura para clasificar y procesar los residuos.
