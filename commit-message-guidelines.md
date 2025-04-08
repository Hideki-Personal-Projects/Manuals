# ✅ Commit Message Guidelines

Follow the **Conventional Commits** format to keep history readable, automate changelogs, and improve collaboration.

---

## Format

```
<type>(<optional scope>): <short summary>

<optional body>

<optional footer>
```

---

## Types

| Type        | Description                                 |
|-------------|---------------------------------------------|
| `feat`      | A new feature                               |
| `fix`       | A bug fix                                   |
| `docs`      | Documentation only                          |
| `style`     | Formatting, no logic change                 |
| `refactor`  | Code change that neither fixes nor adds     |
| `test`      | Adding or updating tests                    |
| `chore`     | Routine task or tool config                 |
| `perf`      | Performance improvements                    |
| `ci`        | CI/CD-related changes                       |
| `build`     | Build system or dependencies                |
| `revert`    | Reverts a previous commit                   |

---

## Scope (Optional)

Use to specify what part of the codebase you're touching.

**Examples:**
- `feat(auth): ...`
- `fix(profile): ...`
- `chore(deps): ...`

---

## Summary (Required)

- Use the **imperative mood**: “add” not “added”
- Be brief and descriptive
- Lowercase after `:`

**Examples:**

```
feat(api): add mood-based filter
fix(song): handle YouTube link validation
chore(env): update .env.example for clarity
```

---

## Reverts

**Example:**

```
revert: feat(auth): add GitHub login

This reverts commit 123abc.
```

---

## Note

- Limit subject line to ~72 characters
- Don’t end the subject line with a period
- Use the body to explain **why**, not just what

---

## Extra Info

| Type        | Description                                                                                                                       |
|-------------|-----------------------------------------------------------------------------------------------------------------------------------|
| `feat`      |Used when you add a new feature to the codebase. It’s user-facing and affects the product behavior.                                |
| `fix`       | Used when you fix a bug that causes incorrect behavior. It's usually something that was broken or didn’t work as expected.        |
| `docs`      | Used when you change documentation only. It does not affect code behavior.                                                        |
| `style`     | Used for code changes that don’t affect behavior or logic, but improve readability or styling.                                    |
| `refactor`  | Used when you're changing the structure of code without changing its behavior. It’s about cleaning up, not fixing.                |
| `test`      | Used for writing or modifying test code. No changes to actual application logic.                                                  |
| `chore`     | Used for non-code or non-feature tasks like config changes, dependency updates, tooling, etc.                                     |
| `perf`      | Used for changes that improve performance without altering features or logic.                                                     |
| `ci`        | Used for changes to Continuous Integration/Delivery (e.g., GitHub Actions, Travis, Jenkins).                                      |
| `build`     | Used for build-related changes like Webpack, Docker, Vite, Babel, etc.                                                            |
| `revert`    | Used to undo a previous commit, especially when it introduced bugs.                                                               |

---

## 🔗 References

- Based on [Conventional Commits v1.0.0](https://www.conventionalcommits.org/)
