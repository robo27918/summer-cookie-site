# AGENTS.md

This file gives working instructions to coding agents operating in this repository.

## Repo Summary

- Project type: single-page static website
- Main entry point: `index.html`
- Documentation: `README.md`
- No package manager, build system, or test suite is present

## Goals

When making changes, preserve the site's existing purpose:

- Keep it as a lightweight baking-themed static page
- Maintain the warm, homemade visual style
- Push the atmosphere toward a "Welcome Home" feeling: cozy, neighborly, whimsical, and inviting
- Prefer simple solutions over added tooling
/
## Design Reference

Primary inspiration for tone and visual direction:

- https://welcomehomerestorationproject.net/welcomehomeyou
clea
Use that reference for mood rather than direct copying. The site should feel:

- Colorful and storybook-like
- Friendly, playful, and handmade
- Warmly welcoming instead of polished/corporate
- Full of personality, with charming details and decorative touches

Avoid cloning characters, artwork, branding, or page structure from the reference. Borrow the emotional direction only.

## Editing Rules

- Make focused edits and avoid unnecessary restructuring
- Do not introduce frameworks, bundlers, or dependencies unless explicitly requested
- Keep the project runnable by opening `index.html` directly in a browser
- If splitting code into separate files, do it only when the task clearly benefits from it
- Preserve existing content unless the user asks for content changes

## HTML, CSS, and JavaScript Guidance

- Keep markup semantic where practical
- Preserve responsive behavior for desktop and mobile layouts
- Match the current visual language: warm colors, soft cards, bakery-style presentation
- When updating visuals, prefer cheerful palettes, playful typography, rounded shapes, layered backgrounds, and handcrafted-looking accents
- Favor "welcome home" energy over minimalism: a little whimsy and texture is better than sterile simplicity
- Prefer small, readable JavaScript over complex abstractions
- Avoid inline event handlers in new code when a cleaner alternative is reasonable, but do not rewrite existing code without a reason

## Verification

Since there is no automated test setup, verify changes by:

- Checking that `index.html` still opens without errors
- Confirming navigation links and bread tab switching still work
- Watching for encoding regressions involving symbols or emoji
- Reviewing layout changes for obvious mobile issues

## File Expectations

- `index.html` contains the full app
- `README.md` should stay aligned with the actual project
- Add new files only when they provide clear value

## Common Safe Improvements

- Accessibility fixes
- Encoding cleanup
- Content updates requested by the user
- Visual polish that matches the existing theme and the "Welcome Home" mood target
- Small JavaScript cleanup without changing behavior

## Avoid

- Adding unnecessary libraries
- Turning the repo into a large multi-file app without a clear reason
- Rewriting working sections just for style preferences
- Removing user content or changing the theme away from the cookie/baking concept
- Copying protected characters, art, or branding from the reference site
