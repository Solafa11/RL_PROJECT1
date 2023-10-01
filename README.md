# Diverse Reinforcement Learning Approaches for Tackling the Classic Rocket Trajectory Problem

# Description
In this repository we implemented an agent that is trained to play the game lunar lander using i) DQN algorithm, and ii) a (double) deep Q-learning algorithm utilizing Jax and Haiku frameworks.

# Lunar Lander Environment
starting state  
In every episode, the rocket starts from a consistent position, precisely at the top center of the view-port.

Observation Space  
encompasses eight state variables:
the lander’s horizontal position (x-coordinate), the lander’s vertical position (y-coordinate), horizontal
velocity (vx), vertical velocity (vy), orientation in space (θ), angular velocity (𝒘), whether the left
leg is touching the ground (Boolean) and whether the right leg is touching the ground (Boolean).


<img src="https://github.com/Solafa11/RL_Project/assets/126588690/9b67dd24-0339-421f-ad06-5eb788e8f9cf.jpg" width="300" alt="states">



Actions:
Actions
There are 4 actions within this environment:

• 0: Taking no action    
• 1: Activating the left orientation engine  
• 2: Activating the main engine  
• 3: Activating the right orientation engine  

<img src="https://github.com/Solafa11/RL_Project/assets/126588690/867dca9b-f8a5-47c2-af7b-3aaa3dbd2bea.jpg" width="300" alt="actions">

# Goal
maintaining an average score of 200 points or greater over a span of 200 consecutive landing attempts.

# Findings
DDQN outperforms the DQN as expected

# Visual illustration of a trained agent playing the game (DDQN)
. Here is a video of a trained agent playing the game:


https://github.com/Solafa11/RL_Project/assets/126588690/f7adab11-67ae-464e-838c-1dc245374dca



# Visual illustration of a trained agent playing the game (DQN):




https://github.com/Solafa11/RL_Project/assets/126588690/8811411a-5d49-40a4-8053-6d84a7242892




# Visual illustration of a trained agent playing the game (DDQN using PyTorch):





https://github.com/Solafa11/RL_Project/assets/126588690/e5748c37-2c96-47aa-8aca-bb9d3d6794e9






    
# contributing
We welcome contributions from the community! If you'd like to contribute to our project, please follow these guidelines:




  1. Fork the repository.
  2. Create a new branch for your feature or bug fix.
  3. Make your changes and submit a pull request.



