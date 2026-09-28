# Racha 2.0 — Phase 4.2 Flashcards

Complete static application based on the exact Phase 4.1 ZIP. See PHASE-4.2.md for the development summary, card editing guide, and limitations.

Extract this ZIP and upload its contents into the root of `bjw3a/RACHA_PHASE-4-TEST-ONLY`. Keep `index.html`, `styles.css`, `favicon.svg`, and `js/` together. Include the new `js/flashcards.js` and `js/flashcards-data.js`. Upload the extracted contents, not the ZIP or its enclosing folder. No build is required.

Choose a course, then Learn or Flashcards. Continue Learning resumes the existing learning progression. Flashcards offers topic, unit, and whole-course review without affecting XP or mastery.

Learning progress stays in the same browser and origin. Flashcard results last only for the open round and reset on refresh or exit. Completion summaries remain student-provided local results, not verified teacher records.

Developer checks: Node 20.19+; run `npm ci`, `npm test`, and `npx playwright install chromium` followed by `npm run test:browser` in `tests/`. See TESTING.md for checks performed.
