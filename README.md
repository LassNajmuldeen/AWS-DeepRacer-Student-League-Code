# AWS-DeepRacer-Student-League-Code


**🏎️ AWS DeepRacer Student League – Custom Reward Function**

Welcome to my AWS DeepRacer Student League repository! This repo contains the custom reward function I developed to enhance the performance of my autonomous car on the American Hills Speedway track.

**🚀 Project Overview**

The AWS DeepRacer Student League provides an exciting platform to explore reinforcement learning in autonomous driving. For this project, I focused on optimizing a reward function that balances speed, track direction, and position on the track to achieve maximum performance. I successfully achieved a lap time of 1:13.668 with only 3h of training, ranking me #1 in Sweden.


**⚙️ Reward Function Logic**

Reward Function Highlights:

 - If the car goes off track, it receives a minimal reward.
 - Encourages the car to stay near the centerline of the track.
 - Penalizes significant deviation from the track’s direction.
 - Prioritizes higher speeds up to a target of 1.0 m/s, the highest speed possible in the student league. 

**📈 Results and Achievements**

 - Achieved the fastest time on the American Hills Speedway track for the AWS DeepRacer Student League.
 - Ranked #1 in Sweden, 43rd in the EU, and 408th globally even with minimal training.
 - Qualified for the Udacity AI & ML Nanodegree scholarship application.

**📚 Learning Outcomes**

 - Deepened my understanding of reinforcement learning algorithms, specifically PPO and SAC.
 - Explored the practical applications of AI in autonomous driving and real-world simulation environments.
 - Sharpened my skills in optimization in competitive settings.

**🛠️ How to Use**

To use this code in your AWS DeepRacer environment:

  1. Upload the PPO model configuration to your AWS DeepRacer console.
  2. Train the model on the American Hills Speedway track or any other track of your choice.
  3. Fine-tune based on your track's specific challenges and test your model in the simulator.

**🤝 Contributions**

Feel free to fork this repository and contribute! I’m always open to collaboration and feedback on further improving the model.

**📧 Contact**

If you have any questions, suggestions, or would like to connect, reach out via LinkedIn or open an issue in this repository.

**Tags:**
#ReinforcementLearning #DeepRacer #AutonomousDriving #MachineLearning #AI #PPO #AIProjects
