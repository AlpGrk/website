# Dark Mode with System Preference Detection

Implement a dark mode theme that activates automatically based on the user's system preference (prefers-color-scheme: dark) and can be toggled manually via a theme button. The preference is persisted in LocalStorage so the user's choice is remembered across sessions.

## Rationale
Dark mode is a universally expected modern UX feature. Its absence is a notable gap compared to every major competitor. It is also specifically mentioned in the project's own known gaps. Using CSS custom properties (already implied by the clean CSS architecture), this is a relatively low-effort enhancement with high user satisfaction impact.

## User Stories
- As a user who works at night, I want dark mode so that the app is comfortable to use in low-light environments
- As a user with system dark mode enabled, I want the app to respect my OS preference automatically so that I don't need to configure it manually

## Acceptance Criteria
- [ ] Dark mode activates automatically when the OS/browser reports prefers-color-scheme: dark
- [ ] A manual toggle button allows users to override the system preference
- [ ] The selected theme preference is saved to LocalStorage and restored on next visit
- [ ] All UI elements (inputs, buttons, cards, badges) are legible and accessible in dark mode
- [ ] Color contrast ratios meet WCAG AA standards in both light and dark modes
- [ ] The toggle is accessible via keyboard and has a proper ARIA label

## Priority
should

## Complexity
medium

## Impact
medium
