Session: P4 (sid=Test-P4)
Date: 2025-12-5
Variant: Screen reader (NVDA), JS-on

| Time | Task | Observation | Tag |
|------|------|-------------|-----|
| 15:30 | T3 | SR read filter label correctly | a11y-pass |
| 15:30 | T1 | Moving to filter, SR said filter(Javascript...) | live-region |
| 15:30 | T2 | Moving to edit, SR said edit | a11y-fail |
| 15:30 | T2 | P4 Thought for a while; This took about 20s to locate correct edit | nav-friction |
| 15:30 | T2 | Successfully saved edit; SR said confirmation | a11y-pass |
| 15:30 | T3 | Add Task input labeled correctly | a11y-pass |
| 15:30 | T4 | Delete button also good | a11y-fail |
| 15:30 | T4 | Confirmation modal not said without P4 move mouse to the window → confusion | aria-missing |

Debrief notes:
- "Some buttons tell P4 what they are."
- "The confirmation wasn’t said I didn’t know it happened."
