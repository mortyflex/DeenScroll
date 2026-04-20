# DeenScroll — Claude Code Instructions

## Commit Message Convention

All commit messages must follow this format:

```
emoji type(scope): short message
```

### Types and their emojis

| Type | Emoji | Use for |
|------|-------|---------|
| feat | ✨ | New feature |
| fix | 🐛 | Bug fix |
| docs | 📝 | Documentation changes |
| style | 🎨 | Formatting/stylistic changes, no functional impact |
| refactor | ♻️ | Code restructuring without new features or bug fixes |
| perf | ⚡ | Performance improvements |
| test | ✅ | Tests added or updated |
| build | 👷 | Build system or dependency changes |
| ci | 💚 | Continuous integration changes |
| chore | 🔧 | Maintenance tasks |

### Examples

```
✨ feat(auth): add password reset
🐛 fix(api): handle timeout correctly
📝 docs(readme): update installation steps
♻️ refactor(parser): simplify parsing logic
⚡ perf(feed): reduce re-renders on scroll
```

### Rules

- Use one main type per commit.
- Keep messages short, clear, and specific.
- Write messages in **English**.
- Use the **imperative mood** (e.g. "add", "fix", "update" — not "added", "fixed", "updated").
- The scope is optional but recommended when it helps identify the affected area.
- Avoid vague messages like "fix stuff" or "update code".
- Always place the emoji at the beginning of the message.
