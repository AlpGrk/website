# Bulk Actions: Clear All Completed Tasks

Add a 'Clear completed' button that removes all completed tasks in a single click. The button should only appear when at least one completed task exists. This closes a known UX gap and directly addresses a pain point observed in Any.do where completed tasks cannot be permanently deleted.

## Rationale
Users who complete multiple tasks accumulate visual clutter. Any.do users specifically complain that completed tasks cannot be permanently deleted — a frustration My Todo List can solve trivially. This is a low-effort, high-satisfaction feature that reinforces data ownership (users control what persists).

## User Stories
- As a daily user, I want to clear all completed tasks at once so that I can start each day with a clean, uncluttered list
- As a privacy-conscious user, I want to permanently delete completed tasks so that my task history is not retained indefinitely

## Acceptance Criteria
- [ ] 'Clear completed' button is visible only when at least one completed task exists
- [ ] Clicking the button permanently removes all completed tasks from LocalStorage
- [ ] The task list updates immediately after bulk deletion without a page refresh
- [ ] A brief confirmation or undo mechanism is shown to prevent accidental bulk deletion
- [ ] The active task count updates correctly after clearing completed tasks

## Priority
must

## Complexity
low

## Impact
medium
