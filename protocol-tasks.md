## 4-5 evaluation tasks (scenario, action, success, target time)

## Task 1: Filter Task
- **Scenario**:  You need to quickly locate a specific task.
- **Action**: Type “buy milk” into the filter input blank
- **Success**: Only tasks containing the keyword are shown.
- **Target**: Less than 20 seconds
- **Linked to**: Story #S2(Easy Task Finding)

## Task 2: Edit Task
- **Scenario**: The current task name is inaccurate.
- **Action**: Edit the task “Buy milk” to “Buy oat milk”
- **Success**: The updated title appears and confirmation is visible.
- **Target**: Less than 20 seconds
- **Linked to**: Story #S3(Clear Edit and Delete Controls)

## Task 3: Add Task
- **Scenario**: You want to record a new reminder.
- **Action**: Add a task titled “Buy milk”
- **Success**: The task appears in the list and a confirmation is visible.
- **Target**: Less than 20 seconds
- **Linked to**: Story #S1(Reliable Task Creation)

## Task 4: Delete Task
- **Scenario**: You have completed the task and want to remove it.
- **Action**: Delete the task “Buy oat milk”
- **Success**: The task disappears from the list.
- **Target**: Less than 20 seconds
- **Linked to**: Story #S3(Clear Edit and Delete Controls)

## Consent script (verbatim, with rights/withdrawal)
# Informed Consent Protocol — Week 6 Peer Interviews

**Module**: COMP2850 Human-Computer Interaction
**Activity**: Low-risk needs-finding (peer interviews)
**Date**: [YYYY-MM-DD]
**Researcher**: [Your Name/Student ID]

---

## Purpose

We are conducting short peer interviews (5-10 minutes) to understand how people use task managers and identify accessibility improvements. This is part of our HCI coursework for Weeks 6-11.

## What You'll Do

I will ask you 3-5 questions about your experience with task management tools (e.g., "Tell me about a time you struggled to find a specific task"). I'll take brief notes. **No recordings** will be made unless you explicitly agree (and I'll ask again before starting).

## Data Collected

- **What I will collect**:
  - Pseudonymised notes (e.g., "Participant 1 said...")
  - Timestamps of interview
  - Contextual tags (e.g., "Uses keyboard only", "Prefers dark mode")

- **What I will NOT collect**:
  - Your name (unless you want credit in acknowledgements)
  - Student ID number
  - Email address
  - Any other personally identifiable information (PII)

## Data Storage

- **Where**: Local Git repository on my laptop (private repo, not shared publicly)
- **Who can access**: Me, my lab partner, module teaching staff (if requested for marking)
- **How long**: Until end of Semester 1 (January 2025), then deleted OR anonymised for portfolio

## Your Rights (UK GDPR / Data Protection Act 2018)

- **Right to withdraw**: You can stop at any time, no explanation needed
- **Right to access**: You can ask to see your data (I'll show you my notes)
- **Right to erasure**: You can request I delete your data (email me with interview date/pseudonym)

## Consent Confirmation

Before starting, I will ask:
- [ ] Have I explained the purpose clearly?
- [ ] Do you understand what data I'll collect?
- [ ] Do you know you can stop at any time?
- [ ] Do you consent to participate?

**Verbal consent is sufficient** for this low-risk activity. If you say "yes", I'll note:
- Date/time: [YYYY-MM-DD HH:MM]
- Pseudonym assigned: [e.g., "Participant 1"]
- Consent confirmed: [Initials]

---

## Opt-Out Process

If you change your mind after the interview:
1. Email me at [your-university-email]
2. Include: interview date and pseudonym (if you remember it)
3. I will delete all notes related to your session within 48 hours
4. I will confirm deletion via email

# Job Stories — Week 6 Needs-Finding

## Story S1: Reliable Task Creation
**Situation**: When I add a new task，
**Motivation**: I want a clear and immediate confirmation that it was successfully created，
**Outcome**: So I can quickly find the most time-sensitive tasks without scanning everything，
**Underlying need**: Because unclear feedback makes users double-click or doubt whether their action worked.

## Story S2: Easy Task Finding (Filter)
**Situation**: When my task list becomes long，
**Motivation**: I want to quickly filter items by typing a keyword，
**Outcome**: So I can find what I’m looking for without scanning everything，
**Underlying need**: Because long lists create cognitive load and make important tasks harder to find.

## Story S3: Clear Edit and Delete Controls
**Situation**: When I want to update or delete a task,
**Motivation**: I want buttons that clearly indicate which task they belong to
**Outcome**: So I don’t accidentally act on the wrong item
**Underlying need**: Because identical “edit” or “delete” buttons confuse both visual and screen-reader users.
