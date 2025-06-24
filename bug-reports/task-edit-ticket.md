# Bug Report – To-Do App: Task Edit Not Saving

**Summary**: When editing an existing task, changes sometimes do not save.

**Steps to Reproduce**:
1. Add a new task
2. Click "Edit"
3. Change the text
4. Click "Save"

**Expected Result**: The updated task text should replace the original

**Actual Result**: Task reverts to previous text in ~40% of attempts

**Environment**: Chrome, MacBook Pro, v1.2.0

**Severity**: Medium  
**Priority**: High

**Suggested Fix**: Ensure that save function is triggered correctly and that state updates persist

**Attachment**: Screenshot or Loom link (if available)
