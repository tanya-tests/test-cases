## Test Case: test_set_alarm

**Test Description:**
This test verifies whether the alarm system triggers the alarm successfully by simulating an event that should activate the alarm and checking if it goes off as expected.

**Prerequisites:**
- Have the clock app installed
- Assume the user is logging in for the first time and does not have previous alarms set

**Test Environment:**
- Alarm system version: IOS Clock App
- Testing equipment: iPhone 7s
- Alert/notification mechanisms: speaker on the phone

| Test Steps                                         | Expected Results                                       |
|----------------------------------------------------|--------------------------------------------------------|
| 1. Open the clock app.                            | Clock app should open.|
| 2. Go to "Alarm" by tapping the Alarm icon at the bottom of the screen. | A list of alarms should render. |
| 3. Press the "+" symbol at the top of the screen. | The workflow for setting an alarm should render. |
| 4. Scroll to set the time one minute past the current time. | The time should be scrollable and selectable                                                       |
| 5. Press Save.                                    | The alarm should be set                                                       |
| 6. Wait 1 minute.                                | After 1 minute has elapsed the alarm should produce the expected sound or visual indicators to signify it is going off.                                                    |



