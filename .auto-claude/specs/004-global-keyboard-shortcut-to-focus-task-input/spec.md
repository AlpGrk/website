# Global Keyboard Shortcut to Focus Task Input

Implement a keyboard shortcut (e.g., pressing '/' or 'n') from anywhere on the page to instantly focus the task input field, ready for typing. Show a keyboard shortcut hint near the input placeholder. This allows power users to add tasks without reaching for the mouse.

## Rationale
The current app lacks a way to focus the input from anywhere on the page, requiring mouse interaction. Technical users and keyboard-first users (a key secondary persona) expect this behavior. It also supports the core success metric: adding a first task in under 10 seconds from page load.

## User Stories
- As a keyboard-first user, I want a keyboard shortcut to focus the task input so that I can add tasks without using the mouse
- As a power user, I want to quickly jump to task entry from anywhere on the page so that adding tasks feels instant and frictionless

## Acceptance Criteria
- [ ] Pressing '/' or a configurable key from anywhere on the page focuses the task input field
- [ ] The shortcut does not trigger when a user is already typing in an input or contenteditable element
- [ ] A visual hint (e.g., 'Press / to add a task') is shown in the input placeholder or below the field
- [ ] The shortcut works on both desktop and does not conflict with mobile browser shortcuts
- [ ] Pressing Escape while in the input blurs it and returns focus to the page

## Priority
must

## Complexity
low

## Impact
medium
