# Phase 4 validation

Passed with Node 24:
- Content generation across both courses, every topic and unit review; unique valid choice, six unique matching pairs, no removed pronoun forms.
- Five activities, 80% boundary, incorrect-answer rejection, Unicode accent/punctuation normalization and ñ distinction.
- Existing XP, personal records, badges and last-topic persistence; completion date recording.
- DOM end-to-end: new student course/topic access, matching failures and retries, recognition at 70% then 80%, ten typed questions, five sentence completions, final reading, accurate completion summary, manual copy fallback, completed-topic resume, and all unit/topic navigation.
- JavaScript syntax checks.

Not completed in this environment:
- Real Chromium desktop/mobile layout, visual screenshots, browser refresh and clipboard permission behavior. Chromium was unavailable and browser download was canceled. The updated browser smoke test is included for 320, 390, 768 and 1366 pixel widths.
- Live GitHub Pages deployment. Relative assets and static repository structure are retained.

Run tests/phase4.mjs and tests/phase4-dom.mjs through npm test after installing the test dependencies. Browser smoke tests run with npm run test:browser after installing Playwright Chromium.
