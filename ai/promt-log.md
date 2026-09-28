## Prompt 01
Time: 19:43 27/09/2026
Tool: Claude CLI

Prompt:
Create a mindmap describing modern QA/QC roles and responsibilities in software testing, based on the ISTQB testing process.

Include:
- QA vs QC
- Test planning
- Test analysis
- Test design
- Test implementation
- Test execution
- Test monitoring and control
- Test completion
- Modern AI-assisted testing roles

Output as Mermaid mindmap syntax.

Do not assume your answer is correct. I will independently verify it against ISTQB.

Purpose:
Generate initial QA/QC role mindmap.


## Prompt 02
Time: 20:50 27/09/2026
Tool: Claude CLI

Prompt:
I am testing a physical mechanical countdown timer. Based on the product description below and the attached image, create 15 test cases for this product. Product description: - The timer has a rotary knob in the center. - Turning the knob sets the countdown time. - As the knob is turned, a red-colored indicator appears on the dial to visually represent the amount of time that has been set. - The timer supports countdown durations from 0 to 120 minutes. - When the countdown reaches 0, the timer produces an alarm sound. - There is a button on the top of the timer. - When the alarm is sounding, pressing the top button stops the alarm. - The timer also has a Silent Mode. - Pressing and holding the top button for 2 seconds toggles Silent Mode ON/OFF. - When Silent Mode is ON, the timer should not produce an alarm sound when the countdown reaches 0. - On the back of the timer, there is a removable battery cover. - The timer uses 2 AA batteries. Create exactly 15 test cases covering: - Normal/functional scenarios - Boundary values (especially 0 and 120 minutes) - Invalid or unusual user actions - Alarm behavior - Silent Mode - Rotary knob and red time indicator - Battery compartment and battery-related behavior - Basic physical/usability checks For each test case, provide: 1. Test Case ID 2. Test Case Title 3. Preconditions 4. Test Steps 5. Expected Result 6. Test Type (Positive, Negative, Boundary, Usability, etc.) Do not invent undocumented features or requirements. If an expected behavior cannot be determined from the provided requirements, explicitly mark it as "Requirement clarification needed" instead of assuming the behavior. Present the 15 test cases in a clear table.

Purpose:
Generate test cases for the physical device.

## Prompt 03
Time: 22:00 27/09/2026
Tool: Claude CLI

Prompt:
make the same table above for my 3 test cases: 1. Rotate the knob backwards at 0, 2. Rotate the knob backwards at 30 mins, 3. Only 1 battery installed

Purpose:
Add my test cases to the table

## Prompt 04
Time: 07:30 28/09/2026
Tool: Claude CLI

Prompt:
Write a 200300-word paragraph critiquing the AI. Where did the AI get it
wrong, biased, or incomplete? Why did the AI fail to catch it? What principle
have you learned for collaborating with AI on this HW?

Purpose:
Write the initial critique
