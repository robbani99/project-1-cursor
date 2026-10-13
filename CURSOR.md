# Cursor — Cursor test project 1

This file is project context for Cursor. Prefer it when deciding how to work in this folder.

## Project

- Owner: Khandoker (marketer)
- Stack: Node.js with TypeScript
- Package manager: npm (do not use yarn, pnpm, or bun)
- Preference: work directly in code — create, debug, and iterate
- Status: new Node.js + TypeScript workspace

## How to work here

- Implement in the repo instead of only describing steps
- Keep changes small and focused
- Do not commit unless asked
- Use TypeScript (`.ts`) for all application code; avoid plain JavaScript except where Node config requires it (`package.json`, config files)
- After API or server changes, verify with the running Node process, tests, or `curl` — not only by reading the code

## Conventions

- Prefer TypeScript strict typing; do not use `any` unless there is no practical alternative
- Use ES modules and a clear `src/` layout
- Keep `package.json` scripts as the way to build, start, and test (`npm run …`)
- Install and update packages with npm only (`npm install`, `npm ci`)
- Use clear names and simple structure
- Avoid extra files, docs, or comments unless they are needed
- Match existing style once code exists
