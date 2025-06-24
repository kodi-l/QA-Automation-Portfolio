# Exploratory Testing Notes – To-Do App

## Goal
Test core task functionality: adding, editing, deleting, completing tasks.

---

## Observations

| Feature         | Observation                                          | Pass/Fail |
|----------------|------------------------------------------------------|-----------|
| Add Task       | New task appears immediately in list                | Pass   |
| Edit Task      | Edited task sometimes doesn’t save properly         | Bug    |
| Delete Task    | Task disappears from UI + console shows 200 OK      | Pass   |
| Mark Complete  | Checkbox toggles task state visually                |  Pass   |
| Persistence    | Tasks persist after refresh                         | Pass   |
| Blank Input    | App accepts blank task with no error                |  Bug    |

---

## Potential Bugs
1. **Task edit not saving**  
   - Intermittent — sometimes task reverts to old text  
2. **Blank task input accepted**  
   - Should trigger a validation message

---

## Notes
- Would manually test edge cases like:
   - Entering emoji-only tasks
   - Super long strings
   - Enter key instead of click
