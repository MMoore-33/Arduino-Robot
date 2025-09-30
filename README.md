# Arduino-Robot
Autonomous robot to track objects. Using Arduino UNO. Ultrasonic Follower Robot (no LCD)

  Description:
  This robot uses an ultrasonic sensor to measure the distance to objects
  in front of it. Based on how far the object is, the robot will move forward,
  stop, or move backward. An LED is also used as an indicator.

  Behavior:
  - If an object is closer than 15 cm → move backward (avoid collision).
  - If an object is between 15 and 30 cm → stop (safe distance).
  - If an object is between 30 and 45 cm → move forward (follow object).
  - If no object is detected (>45 cm) → stop.