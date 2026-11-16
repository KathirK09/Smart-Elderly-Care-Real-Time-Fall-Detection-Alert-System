# Testing and Validation Plan

Perform tests safely. Do not deliberately drop or endanger a person to test the device. Use controlled sensor movement or a test rig where possible.

| Test | Procedure | Expected observation | Actual result |
|---|---|---|---|
| Power-on | Switch on the prototype | ESP8266 starts correctly | To be filled |
| Sensor connection | Start with ADXL345 connected | Sensor initializes and readings appear | To be filled |
| Normal movement | Move the device during ordinary activity | No unintended fall alert, according to configured logic | To be filled |
| Simulated fall pattern | Use a controlled, repeatable motion/test fixture | Detection logic responds as designed | To be filled |
| Buzzer | Trigger the test alert condition | Buzzer activates | To be filled |
| Blynk notification | Trigger the test alert condition with Wi-Fi available | Notification is received | To be filled |
| Wi-Fi unavailable | Disable Wi-Fi during a test | Behaviour matches the documented offline design | To be filled |
| Battery operation | Test with the intended battery setup | Stable operation for the measured duration | To be filled |

## Record
- Detection threshold(s) and timing window
- Sampling frequency
- False-positive and missed-detection observations
- Wi-Fi notification delay and connectivity limitations
- Battery runtime measured under stated conditions

Do not claim medical-grade accuracy from a small number of prototype tests.
