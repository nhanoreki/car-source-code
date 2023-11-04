# car-source-code
# About the functions provided in the library carMazeOfOz.h
# Notes: Please press the reset button on Arduino before use

1. ```setMotorLeft(int speed, bool direction)```
  - Description: The function is used to controls the left motor speed and direction of rotation.
  - Syntax: setMotorLeft(speed, direction)
  - Parameters:
    - speed: control the speed of the left motor.
      - arg: PWM value, from 0 to 255
    - direction: control the direction of rotation of the left motor
      - arg: FORWARD
      - arg: BACKWARD
  - Returns: None.

2. ```setMotorRight(int speed, bool direction)```
  - Description: The function is used to controls the right motor speed and direction of rotation.
  - Syntax: setMotorRight(speed, direction)
  - Parameters:
    - speed: control the speed of the right motor.
      - arg: PWM value, from 0 to 255
    - direction: control the direction of rotation of the right motor
      - arg: FORWARD
      - arg: BACKWARD
  - Returns: None.

3. ```getSpeedLeft(void)```
  - Description: The function performs the calculation of the left motor speed value.
  - Syntax: getSpeedLeft()
  - Parameters: None.
  - Returns: Speed value of left motor
    -type: float
    -unit: cm/s.

4. ```getSpeedRight(void)```
  - Description: The function performs the calculation of the right motor speed value.
  - Syntax: getSpeedLeft()
  - Parameters: None.
  - Returns: Speed value of right motor
    -type: float
    -unit: cm/s. 

5. ```getDistanceHead(void)```
  - Description: The function performs the calculation of the distance value in front of the car.
  - Syntax: getDistanceHead()
  - Parameters: None.
  - Returns: Distance in front of the car
    -type: float
    -unit: cm.

6. ```getDistanceLeft(void)```
  - Description: The function performs the calculation of the distance value on the left side of the car.
  - Syntax: getDistanceLeft()
  - Parameters: None.
  - Returns: Distance on the left side the car
    -type: float
    -unit: cm.

7. ```getDistanceRight(void)```
  - Description: The function performs the calculation of the distance value on the right side of the car.
  - Syntax: getDistanceRight()
  - Parameters: None.
  - Returns: Distance on the right side the car
    -type: float
    -unit: cm.
