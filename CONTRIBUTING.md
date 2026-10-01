# Contributing to Tech Team Ko Bulao

Welcome to Tech Team Ko Bulao! We build, break, fix, and ship projects together. Follow these simple steps for contributing to team repositories.

---

## 1. Team Workflow

1. **Create an issue** for meaningful work (or pick an existing issue).
2. **Create a feature/fix branch** from `main`.
3. **Make changes** and test locally.
4. **Commit clearly** with descriptive commit messages.
5. **Push branch** to GitHub.
6. **Open a Pull Request** targeting `main`.
7. **Get review** (at least 1 teammate approval required).
8. **Fix review comments** and resolve conversations.
9. **Merge into main** (Squash and merge or Merge commit).
10. **Delete the feature branch** after merging.

---

## 2. Branch Naming Conventions

Always prefix branch names with the type of work:

* `feature/<name>` — New feature or functionality (e.g., `feature/login`, `feature/dashboard`)
* `fix/<name>` — Bug fixes (e.g., `fix/auth-callback`, `fix/nav-overflow`)
* `docs/<name>` — Documentation updates (e.g., `docs/setup`, `docs/api-guide`)
* `refactor/<name>` — Code cleanup without behavior changes (e.g., `refactor/api-client`)
* `test/<name>` — Adding or updating tests (e.g., `test/auth-flow`)
* `chore/<name>` — Maintenance, dependencies, config (e.g., `chore/bump-deps`)

---

## 3. Security Guidelines

* **NEVER commit sensitive credentials or secrets!**
  * `.env` files
  * API keys (Gemini, OpenAI, Anthropic, etc.)
  * Database passwords & connection strings
  * Supabase service-role keys
  * Private certificates or tokens
* Always use a `.env.example` file to document required environment variables without actual secret values.
* Ensure `.gitignore` ignores `.env`, `.env.local`, and build artifacts before committing.
