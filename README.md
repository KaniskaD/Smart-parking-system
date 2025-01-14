# Smart-parking-system
Introduction:

The ultrasonic distance measurement system is designed to measure distances using an HC-SR04 ultrasonic sensor interfaced with an STM32F401 microcontroller. The system utilizes timer and interrupt capabilities to calculate the distance and subsequently activates a set of LEDs based on the measured range. This project demonstrates key concepts in embedded systems, including GPIO configuration, timer operations, and external interrupts.

Problem statement:

Our project is a smart parking system designed to assist drivers with precise object detection while reversing. When an object is detected close to the back of the car, all three LEDs will blink to indicate an immediate proximity warning. Based on varying distances, different LED patterns and behaviors provide additional alerts, helping drivers maintain safe distances and avoid obstacles.

Challenges:

The main challenges include:

Accurate Timing and Measurement: Using the ultrasonic sensor's ECHO signal to measure the time accurately and calculate the distance precisely in centimeters.

Interrupt Handling: Properly handling interrupts for the ECHO pin to capture the pulse duration without missing any signal transitions.

Real-Time Processing: Ensuring the system continuously measures distance and updates LED states without significant delays.

Effective Feedback Mechanism: Implementing a clear and immediate response through LEDs to indicate object proximity, aiding in user interaction or situational awareness.
