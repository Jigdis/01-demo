# AGENTS.md

## Quick start

```bash
# No build step — open directly in a browser
start index.html
```

## Project structure

- `index.html` — single-page static site, the only source file
- `README.md` — project description (Spanish)

## Notable gaps

- README lists **Tailwind CSS** as a used technology, but `index.html` does not include the Tailwind CDN script or any Tailwind utility classes (uses inline styles instead). Verify intent before adding Tailwind.
- No `package.json`, no dependencies, no build, test, lint, or typecheck tooling.
- No CI/CD, no pre-commit hooks, no deployment config.
