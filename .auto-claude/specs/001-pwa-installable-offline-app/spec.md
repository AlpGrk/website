# Progressive Web App (PWA) — Installable Offline App

Add a Web App Manifest and a Service Worker to make the app installable as a PWA on mobile and desktop. Users can add the app to their home screen or desktop and use it fully offline — even without loading the original URL. The Service Worker caches the single HTML file for instant offline access.

## Rationale
All major competitors (Todoist, Microsoft To Do, Google Tasks, TickTick) require internet connectivity to function or have sync failures when offline. Turning My Todo List into an installable PWA is a unique capability among privacy-focused lightweight alternatives (market gap-3). It reinforces the 'no internet dependency' differentiator and gives the app a native-like feel without an app store.

## User Stories
- As a mobile user, I want to install the app on my home screen so that I can access my tasks without opening a browser
- As a privacy-conscious user, I want the app to work fully offline so that my tasks are always available without any network dependency

## Acceptance Criteria
- [ ] A valid Web App Manifest is served with the page (name, icons, start_url, display: standalone)
- [ ] A Service Worker caches the app shell (HTML, CSS, JS) for full offline access
- [ ] The app can be installed via 'Add to Home Screen' on iOS Safari, Android Chrome, and desktop Chrome/Edge
- [ ] Installed app opens in standalone mode (no browser chrome) on all platforms
- [ ] All existing CRUD operations work identically when the app is used offline after installation
- [ ] No external resources are requested by the Service Worker — privacy guarantee is preserved

## Priority
must

## Complexity
medium

## Impact
high
