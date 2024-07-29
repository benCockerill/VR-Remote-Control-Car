RC car startup procedure:
  1. Start CAR SPIKE which controls the motors of the drive train and robot arm
  2. Start CAR PICO which receives control signals via RF transmission and relays them to the CAR SPIKE via bluetooth
  3. Start CONTROLLER SPIKE which takes input from the trigger and claw button force sensors and relays them to the CONTROLLER PICO via bluetooth
  4. Start CONTROLLER PICO which takes input from the CONTROLLER SPIKE and two i2c joysticks connected through a multiplexer and transmits via RF transceiver
