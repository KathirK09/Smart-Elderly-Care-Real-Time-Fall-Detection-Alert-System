# Circuit Connections

Use this page to record the wiring from your actual prototype. Do not assume the example labels below match every ESP8266 development board.

| ADXL345 pin | ESP8266 connection | Notes |
|---|---|---|
| VCC | Confirm module voltage requirement | Check your breakout-board specification |
| GND | GND | Common ground |
| SDA | Board I2C SDA | Confirm board pin mapping |
| SCL | Board I2C SCL | Confirm board pin mapping |
| CS | As required for I2C mode | Follow module documentation |
| SDO | As required for I2C address | Follow module documentation |

| Other component | ESP8266 connection |
|---|---|
| Buzzer signal | Record the GPIO used in your prototype |
| Buzzer supply/GND | Follow buzzer module ratings |
| Battery | Use suitable regulated power circuitry for the ESP8266 |

## Add to this folder
- Final circuit diagram (PNG/PDF)
- Photograph of the assembled hardware
- Notes about power regulation and battery protection

**Safety:** Do not connect a bare lithium-ion cell directly to a board pin unless the board explicitly supports that input. Use an appropriate charging/protection and voltage-regulation arrangement.
