Abstract:
This project develops an Adaptive Traffic Signal Control (ATSC) system using Reinforcement Learning (RL). We present problem motivation, literature background, RL formulation, simulation setup (SUMO), training and evaluation pipelines, and provide complete runnable code (network generation, route generation, training with Stable-Baselines3, evaluation scripts). 
The implementation uses SUMO (microscopic traffic simulator), SUMO-RL (gym-style wrapper), and PPO (Stable-Baselines3) as the main RL algorithm. Results are measured using average travel time, queue length, throughput and number of stops.


Introdution:
This project's goal is to replace fixed-timer traffic lights with a smart Reinforcement Learning (RL) agent. 
This agent will watch traffic in real-time and make intelligent decisions to minimize vehicle wait times and prevent gridlock.
Traffic congestion reduces mobility, increases fuel consumption, and contributes to pollution. Traditional fixed-time and actuated controllers cannot adapt optimally to dynamically-changing demand. 
Reinforcement Learning provides a data-driven method to learn adaptive policies that minimize delays and queues by interacting with a traffic simulator.


Dataset:
https://www.kaggle.com/datasets/boukraailyesali/traffic-road-object-detection-dataset-using-yolo

