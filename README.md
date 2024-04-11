| ID | Description | Steps | | Expected result |
|-|-|
| Steps | 1. Obtain 3 `BatteryInfo` messages </br> 2. Compare timestamp differences with 1 sec |
| Expected result | Timestamp differences is 1 sec, acceptable error is 50 ms |
| TC1 | test_publish_rate | 1. Obtain 3 BatteryInfo messages| Publish rate must be 1 Hz. If this test fails, skip all next tests |
| | | | 2. Compare timestamp differences with 1 sec | Timestamp differences is 1 sec, acceptable error is 50 ms |
