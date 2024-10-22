# Flappy Bird with Genetic Algorithms and Artificial Intelligence (JavaScript)

This project is a version of **Flappy Bird** where an **artificial intelligence** is trained using **genetic algorithms** to autonomously learn how to play. The focus is on two key genetic operators: **Genetic Crossover** and **Mutation Operator**. After implementing these operators, the results of the agents' learning and behavior are analyzed.

## Features

-   **Crossover Operator**: The best birds from each generation are combined, inheriting traits from their "parents" to create more capable new generations.
-   **Mutation Operator**: Small random changes are introduced to some of the genes (neural network weights) of the birds to promote diversity and prevent stagnation.
-   **Simple Neural Networks**: Each bird makes decisions based on environmental data through a neural network that improves over multiple generations.
-   **Result Analysis**: Once the evolutionary process is complete, the results are analyzed to observe how the crossover and mutation operators impact the agent's performance.

## Technologies Used

-   **JavaScript**: The primary language used for the game logic and genetic algorithm implementation.
-   **HTML5 Canvas**: Used for rendering the game's graphics and interface.
-   **Node.js** (optional): For running server-side logic (if needed).
-   **Math.js**: A library used to handle the mathematical computations related to the neural networks and genetic operators.

## How It Works

1.  **Crossover**: The best-performing birds from a generation are selected and combined to create the next generation, mixing their most successful traits.
2.  **Mutation**: Random mutations are applied to some genes (neural network weights) to ensure genetic diversity.
3.  **Evolution**: Over many generations, the birds improve their ability to avoid obstacles in the game.
4.  **Analysis**: The results of each generation are analyzed, showing how the AI evolves as the genetic operators are applied.

## Installation and Usage

1.  Clone the repository:
    
    bash
    
    Copiar código
    
    `git clone https://github.com/your-username/FlappyBird-AI-GeneticAlgorithm-JS.git` 
    
2.  Open the `index.html` file in your web browser to run the game locally.
    
    Or, to run with a local server:
    
    bash
    
    Copiar código
    
    `npm install http-server -g
    http-server` 
    
3.  Watch the AI evolve in real-time and analyze the performance of each generation.
    

## Contributions

Feel free to suggest improvements, report bugs, or contribute to the project.

----------

# Flappy Bird con Algoritmos Genéticos e Inteligencia Artificial (JavaScript)

Este proyecto es una versión de **Flappy Bird** en la que una **inteligencia artificial** es entrenada mediante **algoritmos genéticos** para aprender a jugar de forma autónoma. El enfoque se centra en dos operadores genéticos clave: **Operador de Cruce** y **Operador de Mutación**. Tras la implementación de estos operadores, se analizan los resultados del comportamiento y aprendizaje de los agentes.

## Características

-   **Operador de Cruce**: Los mejores pájaros de cada generación se combinan, heredando características de sus "padres" para crear nuevas generaciones más capaces.
-   **Operador de Mutación**: Se introducen pequeños cambios aleatorios en algunos genes (pesos de la red neuronal) de los pájaros para promover la diversidad y evitar el estancamiento.
-   **Redes Neuronales Simples**: Cada pájaro toma decisiones basadas en datos del entorno mediante una red neuronal que mejora a lo largo de varias generaciones.
-   **Análisis de Resultados**: Al completar el proceso evolutivo, se analizan los resultados para observar cómo los operadores de cruce y mutación impactan en el rendimiento del agente.

## Tecnologías Utilizadas

-   **JavaScript**: El lenguaje principal para la lógica del juego y la implementación de los algoritmos genéticos.
-   **HTML5 Canvas**: Utilizado para renderizar los gráficos e interfaz del juego.
-   **Node.js** (opcional): Para ejecutar lógica en el lado del servidor (si es necesario).
-   **Math.js**: Biblioteca utilizada para manejar los cálculos matemáticos relacionados con las redes neuronales y los operadores genéticos.

## Funcionamiento

1.  **Cruce**: Los mejores pájaros de una generación se seleccionan y combinan para crear la siguiente generación, mezclando sus rasgos más exitosos.
2.  **Mutación**: Se aplican mutaciones aleatorias a algunos genes (pesos de la red neuronal) para asegurar la diversidad genética.
3.  **Evolución**: A través de varias generaciones, los pájaros mejoran su habilidad para evitar obstáculos en el juego.
4.  **Análisis**: Se analizan los resultados de cada generación, mostrando cómo la IA evoluciona a medida que se aplican los operadores genéticos.

## Instalación y Uso

1.  Clona el repositorio:
    
    bash
    
    Copiar código
    
    `git clone https://github.com/tu-usuario/FlappyBird-AI-GeneticAlgorithm-JS.git` 
    
2.  Abre el archivo `index.html` en tu navegador web para ejecutar el juego localmente.
    
    O, si prefieres ejecutar con un servidor local:
    
    bash
    
    Copiar código
    
    `npm install http-server -g
    http-server` 
    
3.  Observa cómo la IA evoluciona en tiempo real y analiza el rendimiento de cada generación.
    

## Contribuciones

Siéntete libre de sugerir mejoras, reportar errores o contribuir al proyecto.