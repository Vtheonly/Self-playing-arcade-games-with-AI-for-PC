# Arcade AI Project with Genetic Algorithms  

The **Arcade AI Project** is an innovative attempt to integrate artificial intelligence into three classic arcade games. Using **C++** and **SDL** for game development, this project focuses on creating AI agents that learn and adapt to master the following games:  

- **Tetris**  
- **Snake**  
- **Flappy Bird**  

The AI utilizes **genetic algorithms** to evolve its gameplay strategies. By simulating a natural selection process, the AI refines its abilities over successive generations, improving its performance and demonstrating adaptive behavior in real-time gaming environments.  

---

### Key Features  

1. **Classic Arcade Game Development**:  
   - Implemented using **C++** and **SDL** for efficient rendering and game mechanics.  

2. **AI with Genetic Algorithms**:  
   - **Natural Selection Process**: Simulates evolution by selecting the best-performing agents in each generation.  
   - **Crossover and Mutation**: Combines traits from successful agents and introduces randomness to create new strategies.  
   - **Adaptive Learning**: AI progressively improves its decision-making to master each game.  

3. **Cross-Game AI**:  
   - A unified AI system that adapts and evolves to play all three games effectively.  

---

### Technology Stack  

- **Programming Language**: C++  
- **Game Framework**: SDL (Simple DirectMedia Layer) for rendering and mechanics  
- **AI Algorithms**: Genetic algorithms (natural selection, crossover, mutation)  

---

### How It Works  

1. **Game Mechanics**:  
   - The games (Tetris, Snake, Flappy Bird) are fully implemented with custom rules and mechanics.  
   - SDL is used for rendering and handling inputs.  

2. **AI Training**:  
   - The AI begins with random behaviors and plays the game.  
   - A **fitness function** evaluates the performance of each agent (e.g., score, survival time).  
   - Top-performing agents are selected for reproduction through crossover and mutation.  

3. **Evolution**:  
   - Over multiple generations, the AI learns patterns, improves strategies, and adapts to maximize performance.  
