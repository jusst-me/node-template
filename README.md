# Node Template

Minimal Node.js TypeScript template for backend projects (Express, NestJS, etc.).

## Project structure

- `src/` – source code
- Root – configuration (tsconfig, eslint, etc.)
- `AGENTS.md` – instructions for AI coding agents

## Requirements

- Node.js >= 24
- pnpm

## Installation

```bash
pnpm install
```

## Scripts

| Command         | Description                                      |
| --------------- | ------------------------------------------------ |
| `pnpm dev`      | Start development with watcher (restart on save) |
| `pnpm build`    | Compile TypeScript to `dist/`                    |
| `pnpm start`    | Start the built application                      |
| `pnpm eslint`   | Run ESLint                                       |
| `pnpm prettier` | Check formatting with Prettier                   |
| `pnpm format`   | Format code with Prettier                        |
| `pnpm lint`     | Run ESLint + Prettier                            |

## Development

```bash
pnpm dev
```

The application restarts automatically when you save files.

## Production

```bash
pnpm build
pnpm start
```
