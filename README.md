| ID  | Description       | Steps                                                    | Expected result                                                    |
|-    |-                  |-                                                         |-                                                                   |
| TC1 | test_publish_rate | 1. Obtain 3 BatteryInfo messages                         | Publish rate must be 1 Hz. If this test fails, skip all next tests |
|     |                   | 2. Compare timestamp differences with 1 sec              | Timestamp differences is 1 sec, acceptable error is 50 ms          |
| TC2 | test_voltage      | 1. Obtain the voltage value                              |                                                                    |
|     |                   | 2. Verify that the voltage is within the specified range | The voltage value is within [4.5, 60.0] Volts                      |
| TC3 | 

