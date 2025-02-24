# CS-370
Current/Emerging Trends in CS

Treasure Hunt AI - Project Summary:

Project Overview:

In this project, I implemented a deep Q-learning algorithm to create an intelligent agent (a pirate) that can navigate through a maze to find a treasure. The agent learns through exploration and exploitation, gradually improving its pathfinding capabilities to find the optimal route to the treasure.

My Contribution:

Provided Code: components:

1.) TreasureMaze.py - An environment class defining the maze structure, reward system, and game mechanics
2.) GameExperience.py - A class for storing and retrieving game episodes for experience replay
3.) A Jupyter notebook with the skeleton structure including:
      Functions for visualizing the maze
      Functions for building the neural network model
      Functions for testing the completed model
      Predetermined maze layout and action definitions

Code I Created:

I implemented the central reinforcement learning algorithm in the qtrain() function, which includes:

1.) Setting up the training loop across multiple epochs
2.) Implementing the exploration-exploitation balance (epsilon-greedy approach)
3.) Creating the learning process where the agent:
      Selects actions based on current policy or random exploration
      Updates its neural network based on rewards received
      Stores and learns from past experiences
      Gradually improves its decision-making capabilities

This implementation required understanding both the theory of reinforcement learning and how to apply it practically with neural networks.

Connection to Computer Science:

What Computer Scientists Do and Why It Matters:
Computer scientists develop algorithms and computational systems to solve complex problems. In this project, I developed an AI agent capable of learning how to navigate an environment autonomously - exemplifying how computer scientists create systems that can adapt and improve without explicit programming for every scenario. This matters because similar approaches can be applied to solve real-world problems in robotics, logistics, healthcare, and countless other domains where autonomous decision-making is valuable.

How I Approach Problems as a Computer Scientist:

My approach to this problem demonstrated core computer science problem-solving principles:
  Breaking down a problem - I analyzed the environment, state space, and reward structure
  Applying the necessary theoretical knowledge - I implemented Q-learning and neural networks to create a learning system
  Implement systematic testing - I evaluated performance across multiple epochs and starting positions
  Exploring tIterative improvement - I refined the algorithm through parameter adjustments and testing

This systematic process mirrors how I approached my plant monitoring system in Module One, where I identified a complex problem and developed a structured AI solution by breaking it down into manageable components.

Ethical Responsibilities:

Working on this AI agent highlighted several ethical responsibilities:

End Users:
  Creating systems that are transparent in their decision-making
  Ensuring the system behaves reliably and predictably
  Providing appropriate controls for human oversight


To Organizations:
  Developing efficient solutions that use resources responsibly
  Creating systems that can be maintained and understood by others
  Balancing innovation with practical implementation concerns

Just as I considered environmental impact and privacy concerns in my plant monitoring system proposal, all AI implementations require careful ethical consideration. As reinforcement learning becomes more prevalent in critical applications, these ethical considerations become increasingly important. From this course, I've gained not only technical skills in implementing AI algorithms but also a deeper understanding of how these technologies fit into the broader field of computer science and their potential impact on society.
