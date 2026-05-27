# note-timestamper

Single-page note-taking tool that timestamps each entry at the moment you start typing, not when you submit.

## Structure

One file: `index.html` — all HTML, CSS, and JS embedded. No build step.

## Key behaviour

- First keystroke into the textarea sets the entry's timestamp
- Enter saves; Shift+Enter inserts a newline
- Notes persist in `localStorage` under the key `field-notes` as `[{timestamp, note}]`, newest-first
- Export and Reset buttons in the toolbar

## Deployment

GitHub Pages from the root of `main`. Push to deploy.
Use HTTPS for git push — SSH keys are sandboxed on this machine.
