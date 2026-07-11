Vision Based Cleaner Robot - Stage 2 Proposal 
Participant : Sandun
Stage Completed: 2
Repository : https://github.com/SandunGitHub/D-Robotics/tree/main/Stage%202

Stage 2 — Build up your own intelligent robot
Challenge 2 – Build Challenge
Challenges
Scenario: 
#### Operating environment and constraints
-	Indoor floors such as flat floors, narrow corridors and doorways, furniture and dynamic obstacles, stairs and drop-offs.
-	Reliable operation under vacuum cleaner green LED condition (20-50 lux).
-	Inference performance:  >= 15 FPS for real-time dust detection.
-	Maximum end-to-end latency: ~30 s  latency from image capture to power motor adjustment. 

##### Who benefits and primary interaction mode
-	Target Users: cleaners having disabilities, elderly individuals who may have difficulty in regular cleaning, non-commercial cleaning services.
-	Interaction Mode: IR-based remote controller.
-	Success Criterion: User can initiate a cleaning task and robot completes it without any further intervention.
##### Core AI capabilities: 
1.	Real-time dust and debris detection via a computer vision model.
2.	Classify the dust density as low, medium, or high.
3.	Intelligent adjustment of vacuum power based on the nature of cleaning load.
Innovation/differentiation
Adaptive cleaning strategy that balances cleaning performance, battery life and operational efficiency.
#####  Success Criteria
-	Dust detection accuracy: 
-	Vacuum power adjustment latency:
-	Battery power utilization:
-	Cleaning task completion:
-	Obstacle avoidance rate:

Challenge 2 – AI System architecture
1.	System flow diagram
a.	Non-AI system
i.	Path control and obstacle avoidance

<img width="821" height="572" alt="image" src="https://github.com/user-attachments/assets/0c190fdf-7f1e-4bce-8116-53b245fee5bd" />


b.	AI-System
i.	Dust detection and mapping algorithm

<img width="575" height="371" alt="image" src="https://github.com/user-attachments/assets/de849035-ca90-4e54-85ae-7f9a9390b685" />

2.	Module Design

<img width="940" height="770" alt="image" src="https://github.com/user-attachments/assets/2c40b081-ac3c-4400-bb7f-eb268a85632d" />

3.	ROS2 Node graphs and Compute Allocation

<img width="803" height="457" alt="image" src="https://github.com/user-attachments/assets/7a80e317-3e6d-4d69-a5a6-861876c26567" />










