# Screen Content Specification

## 1. Welcome
**Goal:** Explain the app value quickly.
- Brand: StudyFlow
- Headline: “Make every study session count.”
- Supporting text: “Plan classes, track assignments, and see progress in one simple place.”
- Benefits: Know what's next · Stay on top of deadlines · See your progress
- Primary CTA: Get Started

## 2. Home Dashboard
**Goal:** Answer “What should I focus on today?”
- Greeting and date
- Summary cards: Tasks due today, Next class, Daily goal
- Priority task list with title, subject, due time, status
- Today's progress indicator
- Primary action: + Add task
- Navigation: Home, Tasks, Timetable, Progress

## 3. Tasks
**Goal:** Find and update academic work.
- Filters: All, Today, Upcoming, Completed
- Task row: title, subject, due date, priority, completion status
- Actions: Add task, mark complete, open/edit task
- Empty state: “You're all caught up. Add a task whenever something comes up.”

## 4. Add / Edit Task
**Goal:** Capture a task with minimal effort.
- Fields: Task title (required), subject, due date, priority (Low/Medium/High), optional notes
- Primary CTA: Save Task
- Secondary CTA: Cancel
- Validation: Show an inline message if the task title is empty.
- Success message: “Task saved. You're one step ahead.”

## 5. Timetable
**Goal:** Review the day chronologically.
- Day selector: Mon–Sun
- Time blocks with time, subject, class/study label, optional location
- Empty state: “No sessions planned yet.”

## 6. Progress
**Goal:** Make progress easy to understand.
- Weekly completion summary
- Completed vs pending task count
- Subject-wise summary
- Encouraging copy: “Small steps add up. Keep going.”

## Main transitions
Welcome → Home; Home ↔ Tasks; Home ↔ Timetable; Home ↔ Progress; Home/Tasks → Add/Edit Task → Save → Home or Tasks.
