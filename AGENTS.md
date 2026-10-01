# Project Development Guidelines

## Project

This is a Laravel application.

## Technology

- PHP 8.5
- Laravel
- Livewire
- Vite
- Node.js
- MySQL
- Git

## Development Principles

- Follow Laravel conventions.
- Prefer simple, maintainable solutions.
- Inspect existing code before modifying it.
- Do not introduce unnecessary dependencies.
- Keep controllers thin.
- Use Form Requests for validation.
- Use Eloquent for database operations.
- Use Policies/Gates for authorization.
- Use migrations for database schema changes.

## Security

- Never expose `.env` contents.
- Never hard-code credentials or API keys.
- Validate all external input.
- Use Laravel authentication and authorization.
- Do not disable security controls to make a feature work.

## Database

- Use migrations for schema changes.
- Do not modify production databases directly.
- Do not execute destructive database operations without explicit approval.

## Testing

- Add tests for significant functionality.
- Run relevant tests after changes.
- Run Laravel Pint before completing significant changes.

## Git

- Do not commit secrets.
- Keep commits focused.
- Do not modify Git history unless explicitly requested.
- Do not commit changes automatically.

## Codex

Before significant changes:

1. Inspect the existing implementation.
2. Explain the proposed approach.
3. Identify the files that will change.
4. Wait for approval for large or architectural changes.

After implementation:

1. Run relevant tests.
2. Run code formatting.
3. Show the files changed.
4. Summarize the implementation.

Do not execute destructive commands without explicit approval.
