# Privacy Badge & Auditable Zero-Tracking Guarantee

Add a visible, in-app privacy badge or banner that prominently states the zero-tracking guarantee — no cookies, no analytics, no external requests. Link directly to the source code so users can verify the claim themselves. This transforms the app's strongest differentiator from a hidden code comment into a visible trust signal.

## Rationale
Every major competitor (Todoist, Microsoft To Do, Google Tasks, TickTick, Any.do) shares user data with analytics platforms and third parties. No competitor can offer an auditable, in-browser, no-external-requests privacy guarantee. Making this visible captures the growing segment of privacy-aware users and directly addresses the market gap identified across all 5 competitors.

## User Stories
- As a privacy-conscious user, I want to see a clear, verifiable privacy guarantee on the page so that I can trust the app before adding my personal tasks
- As a developer, I want a link to the source code so that I can audit the zero-tracking claim myself

## Acceptance Criteria
- [ ] A privacy badge or notice is visible on the main page without requiring user interaction
- [ ] The badge clearly communicates zero external requests, zero cookies, zero account required
- [ ] A link to the source code (or 'View Source' instruction) is available from the badge
- [ ] No third-party analytics, tracking scripts, or external fonts are added in this feature
- [ ] The badge is legible and non-intrusive on both mobile (375px+) and desktop viewports

## Priority
must

## Complexity
low

## Impact
high
