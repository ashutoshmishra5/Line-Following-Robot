# Line-Following-Robot-
Pins are designated for motor control (motorAs1, motorAs2, motorBs1, motorBs2), speed control (pwmA, pwmB), encoder inputs (encoderA1, encoderA2), and Bluetooth communication (pinRX, pinTX). 

The QTRSensor library is utilized for sensor calibration. Motor speeds and directions are adjusted based on the calculated error to correct deviations from the expected path. 

Boost activation occurs based on encoder values within specified time frames (startBoostTime and endBoostTime).
