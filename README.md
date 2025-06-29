# DisTracker

### *Design Thinking Group project, Texas Instruments India*

Objective: To design a chargeable distraction-monitoring wristband that detects and alerts the user in a non-intrusive way when distracted during study and focused sessions.

The overall project was carried out in 5 main steps:

1. ***Empathize*** - Understand the real need of user!!
   We floated a Google Form survey with 150+ responses and observed that the major distractions faced by users are smartphones, zoning out, and environmental factors.

2. ***Define*** - Find the WHY before the HOW
  How can we alert users when they are getting distracted by zoning out or smartphones, without them even realizing it?

3.***Ideation*** - The HOW 

How do we know if a person is getting distracted? - HRV , EDA , IMU sensors (Physiological Signals)
How do we process data? - TinyML models  which are used to enable real-time, low-power, on-device processing of sensor data for immediate distraction detection without relying on external devices.
How do we alert the user? - Vibration and LED feedback
How do we measure distraction via smartphones accurately, as they are a major cause?- We designed an Android app using ML to monitor screen activity and classify apps that cause distraction

4. ***Prototype*** - We built a 38mm × 31mm device with 2 layers:
 Bottom layer: GSR sensor, HRV sensor, vibration motor
 Top layer: Seeed MCU, Li-Po battery, LEDs

We also developed a mobile app and gamified the experience to attract students by incorporating daily streaks and focus scores.

5. ***Test*** -  Collect feedback ,iterate and refine our prototype
During prototype testing, we observed key issues and addressed them by adding new features to the device, such as:
Temperature sensitivity handling
Cost optimization
Improved accuracy
Accounting for inter-person variability in HRV and EDA signals

