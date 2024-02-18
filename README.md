# Flightdynamic-detection
This project focuses on classifying various flight dynamic positions—pitch, roll, and yaw—utilizing an STM32 Nucleo F401 RE development board coupled with a motion sensor, the MPU 6050. The implementation is carried out through STM32 Cube IDE.
Key Features:
1. Hardware: Utilizes STM32 Nucleo F401 RE development board and MPU 6050 motion sensor.
2. Software: Developed using STM32 Cube IDE.
3. Classification: Differentiates between pitch, roll, and yaw positions.
4. NanoEdge AI: Integrates NanoEdge AI to interface the appropriate machine learning model, enabling standalone operation for position detection.

Usage:
1. Hardware Setup: Connect the STM32 Nucleo F401 RE board with the MPU 6050 motion sensor.
2. Software Setup: Import the project into STM32 Cube IDE and compile.
3. Deploying NanoEdge AI: Configure NanoEdge AI to interface with the machine learning model for position detection.
4. Run: Execute the program on the STM32 board to begin classifying flight dynamic positions.

Dependencies:
1. STM32 Cube IDE
2. NanoEdge AI
