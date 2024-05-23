# Line Follower Car Robot

[https://github.com/FaresM0hamed/Line-Follower-Car-Robot/commit/bf9db523fb5060e1ef4eccf91954e3b3ffe907df](https://github.com/FaresM0hamed/Line-Follower-Car-Robot/assets/114820994/fb817b32-f039-4db4-980c-65a10139298d
)

A simple line-following robot built using an Arduino Uno, L298N motor driver, and IR sensors. The robot follows a black line on a white surface.

## Components

- Arduino Uno
- L298N motor driver
- 4 TT motors with wheels
- 2 IR sensors
- Battery pack
- Jumper wires

## How It Works

The Line-Follower Car Robot uses infrared (IR) sensors to detect and follow a black line on a white surface. Here's a brief explanation of the working mechanism:

1. **Sensors Detection**: The IR sensors are placed at the front of the robot. These sensors detect the black line by measuring the reflected infrared light. When a sensor is over the black line, it detects a lower amount of reflected light and sends a LOW signal to the Arduino. When the sensor is over the white surface, it detects a higher amount of reflected light and sends a HIGH signal.

2. **Signal Processing**: The Arduino processes these signals to determine the position of the line relative to the robot. If both sensors detect the white surface, the robot moves forward. If the left sensor detects the black line, the robot turns left. If the right sensor detects the black line, the robot turns right.

3. **Motor Control**: Based on the processed signals, the Arduino sends commands to the L298N motor driver to control the motors. This allows the robot to adjust its direction and follow the line accurately.

## Creators

- Fares Mohamed Elshahat Mahmoud
- Amr Mohy Mohamed Yousef
- Asmaa Mohamed Hamed Ibrahim
- Ashrakat Samaha Elsayed Goda
- Asmaa Mohamed Mohamed Elsayed
- Gehad Basiouny Elsayed Basiouny
