Session: P3 (sid=Test-P3)
Date: 2025-12-4
Variant: Keyboard + Mouse, No-JS

| Time | Task | Observation | Tag |
|------|------|-------------|-----|
| 14:56 | T3 | P3 attempted to add a task (the task was added successfully after inputting the information) | ux-flow |
| 14:56 | T0 | Tried Filter → no live update | nojs-flow |
| 14:56 | T3 | The second task addition was successful → This indicates the process is simple and usable | ux-success |
| 14:56 | T0 | Tried Filter → no live update | nojs-flow |
| 14:56 | T0 | Tried Filter several times | performance |
| 14:56 | T3 | Try adding a blank title | error-handling |
| 14:57 | T3 | P3 then immediately added a valid title and successfully added the account | recovery |

| 14:57 | T0 | The list refreshes to show new tasks | nojs-flow |
| 14:57 | T4 | P3 successfully deleted the file on the first attempt | ux-flow |
| 14:57 | T0 | The page was completely reloaded after deletion | nojs-flow |
| 14:57 | T4 | The user attempted a second deletion, which also completed successfully | ux-flow |
| 14:57 | T0 | The page refreshes to display the deletion results | nojs-flow |

Debrief notes:
- "The No-JS version works, but it reloads the whole page every time, it feels slow."
- "Adding tasks is easy once P3 figured it out."
- "It would be nicer if actions didn’t refresh the whole page."
- "Deleting tasks works fine, but the page jumps because it reloads."