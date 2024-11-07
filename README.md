
# Arduino Projects Collection

This repository contains several Arduino projects designed for various sensor applications, including distance measurement, counting, and monitoring. All projects utilize components such as ultrasonic sensors, 7-segment displays, and other sensors to demonstrate different functionalities. Each project is designed to be easily tested and demonstrated on online platforms like Tinkercad.

## Projects Overview

### 1. Distance Measurement Display
**Components:** Ultrasonic Sensor, 7-Segment Display  
**Description:** Measures the distance to an object in front of the ultrasonic sensor and displays the result on the 7-segment display.  
**Instructions:** Connect the ultrasonic sensor and 7-segment display to the Arduino. The display shows the distance in centimeters.

### 2. Smart Distance Counter
**Components:** Ultrasonic Sensor, Touch Sensor, 7-Segment Display  
**Description:** This project counts the number of times an object crosses a set distance threshold detected by the ultrasonic sensor. The count is shown on the 7-segment display. A touch sensor resets the counter.  
**Instructions:** Connect the sensors and 7-segment display to the Arduino. Set a distance threshold in the code, and increment the counter each time an object crosses the threshold.

### 3. Touch-Activated Range Finder
**Components:** Ultrasonic Sensor, Touch Sensor, 7-Segment Display  
**Description:** Takes a distance reading from the ultrasonic sensor only when the touch sensor is activated. The distance measurement is displayed on the 7-segment display for 5 seconds before clearing.  
**Instructions:** Press the touch sensor to trigger a distance reading and display it temporarily.

### 4. Countdown Timer with Obstacle-Activated Reset
**Components:** Touch Sensor, Ultrasonic Sensor, 7-Segment Display  
**Description:** Starts a countdown on the 7-segment display when the touch sensor is activated. If an obstacle is detected by the ultrasonic sensor during the countdown, it resets. If the countdown completes without interruption, it displays "E" on the display.  
**Instructions:** Use the touch sensor to start the countdown and set a distance threshold for the ultrasonic sensor to reset the countdown if an obstacle is detected.

### 5. Digital Stopwatch
**Components:** LCD Display, Two Buttons  
**Description:** A simple stopwatch with a start/stop button and a reset button, displayed on an LCD.  
**Instructions:** Connect the LCD display and buttons to the Arduino. Press one button to start and stop the stopwatch and the other button to reset.

### 6. Motion-Activated Alarm
**Components:** PIR Motion Sensor, Buzzer  
**Description:** An alarm system that sounds a buzzer when motion is detected. The timestamp of each movement detection is logged in the Serial Monitor.  
**Instructions:** Connect the PIR motion sensor and buzzer to the Arduino. Movement triggers the buzzer and logs to the Serial Monitor.

### 7. Temperature Monitoring System
**Components:** DHT11 or LM35 Temperature Sensor  
**Description:** Monitors temperature and displays the data on the Serial Monitor. Sends a warning if the temperature exceeds a certain threshold.  
**Instructions:** Connect the temperature sensor to the Arduino. The temperature is displayed on the Serial Monitor, and a warning is triggered if it exceeds the defined limit.

### 8. People Counter with Direction Detection
**Components:** Two IR Sensors, Ultrasonic Sensor, 7-Segment Display  
**Description:** Counts the number of people entering and exiting a doorway. The ultrasonic sensor helps determine direction, confirming entry or exit based on timing.  
**Instructions:** Place IR sensors on either side of a doorway and connect them to the Arduino. The counter displays the number of people entering or exiting.

---

## Platform for Demonstration

These projects are designed to be tested on Tinkercad, an online simulation platform. You can create a Tinkercad account [here](https://www.tinkercad.com) and upload the provided code and circuit setup to test the functionality virtually.

## How to Use

1. Clone or download the repository.
2. Open Tinkercad and set up each project according to the provided instructions.
3. Upload the code to the virtual Arduino in Tinkercad.
4. Test and modify thresholds or settings as needed.

## Requirements

- [Tinkercad](https://www.tinkercad.com)
- Arduino IDE (optional for local testing)
  
