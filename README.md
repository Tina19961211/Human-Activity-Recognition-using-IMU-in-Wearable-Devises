Human Activity Recognition for Health Monitoring
Overview

This project focuses on Human Activity Recognition (HAR) using sensor data to classify everyday human movements into meaningful activity categories. The goal is to support health monitoring, rehabilitation, and lifestyle analysis by identifying patterns in physical behavior.

By automatically recognizing activities such as walking, sitting, eating, or exercising, this system can provide valuable insights into daily physical activity levels, which are essential for preventive healthcare, wellness tracking, and clinical support.

Activity Classes

The model classifies the following activities:

0: Walking (A)  
1: Jogging (B)  
2: Stairs (C)  
3: Sitting (D)  
4: Standing (E)  
5: Typing (F)  
6: Brushing Teeth (G)  
7: Eating Soup (H)  
8: Eating Chips (I)  
9: Eating Pasta (J)  
10: Drinking from Cup (K)  
11: Eating Sandwich (L)  
12: Kicking (Soccer Ball) (M)  
13: Playing Catch w/ Tennis Ball (O)  
14: Dribbling (Basketball) (P)  
15: Writing (Q)  
16: Clapping (R)  
17: Folding Clothes (S)

These activities cover a broad spectrum of human behavior:

Sedentary activities (e.g., sitting, typing)
Daily living activities (e.g., eating, drinking, grooming)
Moderate movement (e.g., walking, stairs)
Dynamic physical actions (e.g., jogging, sports-related movements)

This makes the dataset particularly relevant for real-world health and behavioral analysis.

Model Performance

The model achieved the following performance:

Accuracy: 40.39%
Macro F1-score: 0.40
Weighted F1-score: 0.40
Key Observations
Strong performance on more distinct activities:
Jogging shows high precision (0.82) and recall (0.87)
Walking is also well-recognized
Moderate to low performance on subtle activities:
Sitting, standing, typing, and similar motions are harder to distinguish
These activities often overlap in motion patterns
Overall, the model performs better on highly dynamic movements than on low-motion or similar classes
Health Perspective

This system plays an important role in modern health applications:

Physical Activity Monitoring
Tracks levels of daily movement
Helps assess whether individuals meet recommended activity guidelines
Sedentary Behavior Detection
Identifies prolonged inactivity (e.g., sitting, typing)
Useful for preventing lifestyle-related conditions
Early Health Insights
Can support early detection of risks related to inactivity
Useful in long-term health tracking
Rehabilitation & Clinical Use
Helps monitor patient movement during recovery
Can assist in physical therapy progress tracking
Sports & Performance Analysis
Tracks athletic movements such as jogging and ball handling
Useful for performance optimization and biomechanics studies
Wearable Technology Integration

This project is highly aligned with wearable technology, which is one of the most impactful real-world applications of Human Activity Recognition.

Wearable devices such as:

Smartwatches
Fitness trackers
Smart bands
Motion sensors (IMUs)

can collect real-time data such as:

Acceleration
Gyroscope readings
Movement patterns
How This System Fits into Wearables
The trained model can be deployed on wearable devices or mobile apps
It enables real-time activity detection
Users can receive instant feedback on their behavior
Health Applications in Wearables
Continuous health monitoring without manual input
Step counting and activity classification
Detection of sedentary behavior alerts
Monitoring exercise intensity and consistency
Supporting elderly care and remote patient monitoring
Impact

By integrating this model into wearable systems, we move toward:

Personalized healthcare
Preventive medicine
Smart fitness tracking
AI-powered health assistants
Challenges & Limitations

While promising, the system has several challenges:

Moderate overall accuracy (40%)
Confusion between similar activities
Overlapping motion patterns (e.g., sitting vs. standing)
Variability in human movement
Need for improved feature extraction and model tuning
Research Directions

Future improvements can focus on:

Advanced feature engineering from sensor signals
Deep learning approaches (e.g., LSTM, CNN for time-series data)
Handling class imbalance and improving dataset quality
Multi-sensor fusion for better accuracy
Integration of biomechanical insights into modeling
Conclusion

This Human Activity Recognition system demonstrates the potential of machine learning in health-aware computing and wearable technology.

Although the current model achieves moderate performance, it establishes a strong foundation for:

Health monitoring systems
Wearable-based activity tracking
Intelligent lifestyle analysis
Clinical and rehabilitation support

With further improvements, this system can contribute to smarter, more proactive healthcare solutions, enabling better understanding of human behavior through data.
