# StudyFlow — Navigation Flow

```mermaid
flowchart TD
    A[Welcome] --> B[Home Dashboard]
    B --> C[Tasks]
    B --> D[Timetable]
    B --> E[Progress]
    B --> F[Add / Edit Task]
    C --> F
    F --> G[Save Task]
    G --> C
    G --> B
    C --> H[Mark Task Complete]
    H --> C
```

## Main journey: add an assignment
1. Open Home Dashboard.
2. Select **+ Add task**.
3. Enter task title, subject, due date, and priority.
4. Select **Save Task**.
5. See a confirmation and return to Home or Tasks.
6. Find the task in the list and mark it complete when finished.
