AI-Powered Flappy Bird Clone

Project Overview

This project presents an AI-driven Flappy Bird game built with Python and Pygame. The AI learns to play the game using reinforcement learning, enabling it to improve performance by optimizing its decisions based on past experiences. The objective is to develop an AI agent capable of achieving high scores by skillfully avoiding obstacles and maintaining flight.

Key Features
    •    AI-Controlled Gameplay: The bird’s movements are managed by an AI agent that learns through reinforcement learning.
    •    Adaptive Training: The AI continuously refines its strategy based on past successes and failures.
    •    Dynamic Obstacle Generation: Pipes appear randomly, progressively increasing the game’s difficulty.
    •    Pygame Integration: The game leverages Pygame for rendering graphics and handling game mechanics.

Technologies Used
    •    Python – Primary programming language for game logic and AI development.
    •    Pygame – Framework for graphics rendering and game controls.
    •    Reinforcement Learning – AI methodology that rewards successful actions and penalizes failures.

Installation Instructions
    1.    Clone the repository:

git clone https://github.com/evertte/flappy-bird-ai.git


    2.    Move into the project directory:

cd flappy-bird-ai


    3.    Install the required dependencies:

pip install -r requirements.txt



Running the Game
    1.    Launch the game using:

python main.py


    2.    The AI will start playing and improving its performance over time. You can observe how it adapts to the game environment.

How It Works
    •    Game Mechanics: The game environment simulates gravity, requiring the bird to flap to stay airborne while avoiding obstacles.
    •    AI Agent: The AI is rewarded for successfully passing pipes and penalized for collisions. Using reinforcement learning principles, it refines its decisions over time to improve gameplay.

AI Training Process
    •    Initially, the AI takes random actions and gradually learns from its experiences.
    •    It updates its Q-values (state-action values) to optimize decision-making and enhance its ability to navigate through obstacles.

Potential Enhancements
    •    Advanced AI Models: Implementing Deep Q-Learning for a more sophisticated learning approach.
    •    Improved Graphics: Enhancing visuals and animations for a better user experience.
    •    Multi-Agent Learning: Training multiple AI agents simultaneously to explore competitive and cooperative behaviors.

Contributions

Contributions are welcome! Feel free to fork the repository, report issues, or submit pull requests for new features, optimizations, or bug fixes.
