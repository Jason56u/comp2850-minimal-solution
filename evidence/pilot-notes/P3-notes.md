Session: P3 (sid=P3_71sh)
Date: 2025-12-5
Variant: Screen reader (NVDA), JS-on

| Time | Task | Observation | Tag |
|------|------|-------------|-----|
| 15:30 | T3 | Used keyboard to submit Add Task; SR read label but not confirmation | sr-status-missing |
| 15:30 | T3 | Added another task; SR repeated field label instead of announcement | sr-verbosity |
| 15:31 | T1 | SR announced “Search by title” but user could not tell results updated | sr-feedback |
| 15:31 | T3 | Add Task again; smooth interaction | a11y-pass |
| 15:32 | T2 | Edited a task; SR did not announce edit mode appeared | aria-live-missing |
| 15:32 | T4 | Delete task; confirmation dialog read after delay | focus-delay |
| 15:32 | T4 | Deleted second task; SR read button before message | focus-order |
| 15:32 | T4 | Deleted third task; SR did not announce removal | sr-status-missing |
| 15:32 | T3 | Add Task input labeled correctly | a11y-pass |
| 15:32 | T1 | Filtered tasks — no feedback for list change | sr-feedback |
| 15:33 | T1 | Filter again; participant waited for confirmation | ux-feedback |
| 15:33 | T4 | Deleted last task; confirmation read correctly | a11y-pass |

Debrief notes:
- "Filtering was the hardest because I couldn’t tell when the results changed."
- "I expected it to tell me the edit saved, but it didn’t say anything."
- "Yes, especially editing and filtering. I wasn’t sure the actions succeeded."
- "The biggest barrier was that the screen reader didn’t announce the state changes. I was guessing what happened."