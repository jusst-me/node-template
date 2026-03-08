# Agent instructions

Context for AI coding agents working on this project.

## Project structure

- `src/` – all source code
- Root – configuration only (tsconfig, eslint, prettier, etc.)

## Code conventions

### Documentation and comments

All documentation and code comments must be written in English.

- README files
- JSDoc comments
- Inline comments
- API documentation

### Source files (`src/**/*.ts`)

- Keep source code in `src/`
- Entry point: `src/index.ts`

## Commands

| Command         | Description                                      |
| --------------- | ------------------------------------------------ |
| `pnpm dev`      | Development with watcher (restart on save)       |
| `pnpm build`    | Compile TypeScript to `dist/`                    |
| `pnpm start`    | Run built application                            |
| `pnpm eslint`   | Run ESLint                                       |
| `pnpm prettier` | Check formatting                                 |
| `pnpm format`   | Fix formatting                                   |
| `pnpm lint`     | Run ESLint + Prettier                            |

## Before committing

Run `pnpm lint` to ensure ESLint and Prettier pass.
