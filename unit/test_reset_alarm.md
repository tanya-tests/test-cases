## Test Name: test_reset_alarm

**Test Description:**
This test verifies whether the alarm system resets the alarm successfully after it has been set off by simulating an event that should activate the alarm and checking if it goes off again.

**Prerequisites:**
- Have the clock app installed
- Have an alarm that has previously gone off

**Test Environment:**
- Alarm system version: IOS Clock App
- Testing equipment: iPhone 7s
- Alert/notification mechanisms: speaker on the phone

| Test Steps                                         | Expected Results                                       |
|----------------------------------------------------|--------------------------------------------------------|
| 1. Open the clock app.                            | The Clock app should open. |
| 2. Go to "Alarm" by tapping the Alarm icon at the bottom of the screen. | A list of alarms should render. |
| 3. Press the alarm list item button that was previously set during prerequisites. | The alarm system should detect the enabled event and activate the alarm. |
| 4. Choose your time by scrolling.                 | The time should be selectable.                                                       |
| 5. Press Save.                                    | The time should be updated visually, and the toggle button is green.|
| 6. Wait for your set alarm time.                  | The alarm should not go off.                                                       |
