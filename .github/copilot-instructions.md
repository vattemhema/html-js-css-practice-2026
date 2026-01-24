# Copilot Instructions (Repository)

This repository is for learning and practicing **HTML, CSS, and JavaScript**.

## Goals

- Keep solutions beginner-friendly and easy to read.
- Prefer small, focused examples over large rewrites.
- Preserve the existing folder structure under `src/`.

## Repo Conventions

- Keep each exercise under `src/` in its existing day folder (for example: `src/day1/`, `src/day2/`, `src/day 3/`, `src/day4/`).
- Prefer editing the day’s `index.html` directly.
- If adding files for a day, keep them in the same folder as that day’s `index.html`:
	- `styles.css`
	- `script.js`
- Reference new files using relative paths (for example: `./styles.css`, `./script.js`).

## Tech Constraints

- Use **vanilla HTML/CSS/JS** (no frameworks unless explicitly requested).
- Avoid adding build tooling (Webpack/Vite/React) unless asked.
- Prefer working within existing `index.html` files for each day.

## Defaults (Preferred)

- Keep examples small and readable (no over-engineering).
- Avoid unnecessary dependencies, generators, or tooling.
- Use responsive-friendly CSS (flex/grid), and test basic mobile layout assumptions.

## Code Style

- Use semantic HTML: `header`, `main`, `section`, `nav`, `footer` where appropriate.
- Keep CSS organized (group related rules, use CSS variables for colors when helpful).
- In JS, avoid global variables; prefer `const`/`let`, and wrap code in an IIFE or use `type="module"` when adding scripts.
- Add accessibility basics: labels for inputs, alt text for meaningful images, visible focus styles.

## Accessibility Checklist (Minimum)

- Use landmarks (`header`, `main`, `footer`) and meaningful headings (`h1` once per page).
- Ensure interactive elements are reachable and visible with keyboard focus.
- Associate inputs with `<label for="...">`.
- Provide `alt` text for meaningful images (empty `alt` for decorative images).

## When Editing

- Make minimal, targeted changes.
- If you add new files, keep them next to the day’s `index.html` (or in a clear subfolder) and reference them with relative paths.

## What to Avoid

- Large rewrites across multiple days unless explicitly requested.
- Introducing frameworks (React/Vue/etc.) or build steps.
- Duplicating the same CSS/JS across many day folders without a clear reason.

