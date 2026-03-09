# Task Count & Progress Summary Bar

Display a real-time summary at the bottom or top of the task list showing the count of active tasks remaining and completed tasks (e.g., '3 tasks remaining · 5 completed'). Update instantly as tasks are added, completed, or deleted. This closes an identified UX gap and provides a motivating at-a-glance progress indicator.

## Rationale
The current app has no progress feedback, which reduces the motivational loop of task completion. This is a low-complexity, high-satisfaction improvement that makes the app feel more complete and polished — matching the baseline UX of every major competitor while adding zero complexity for the user.

## User Stories
- As a daily user, I want to see how many tasks I have left at a glance so that I feel motivated to complete them
- As a productivity-focused user, I want a progress indicator so that I can get a sense of accomplishment when I clear tasks

## Acceptance Criteria
- [ ] The task count updates in real-time when tasks are added, completed, or deleted
- [ ] Both active (incomplete) and completed task counts are visible
- [ ] The count correctly reflects the current filter state (e.g., 'Active' filter shows only active count)
- [ ] The summary is visible without scrolling on mobile viewports
- [ ] Zero tasks shows a meaningful empty state (e.g., 'No tasks yet — add one above!')

## Priority
must

## Complexity
low

## Impact
medium
