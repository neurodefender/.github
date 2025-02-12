# Commit Message Guidelines

Clear, concise, and consistent commit messages help maintain a high-quality project history. Please follow these guidelines when committing changes to any NeuroDefender repository.

## Structure of a Commit Message

Each commit message should include:

1. **Header:**  
   - A short summary (max 50 characters) of the change.
   - Use the imperative mood (e.g., "Add", "Fix", "Update").
2. **Body (Optional):**  
   - A detailed description of the change, if necessary.
   - Include motivation, context, and any background information.
3. **Footer (Optional):**  
   - Reference related issues (e.g., "Closes #123").

### Example

```plaintext
Add support for multi-factor authentication

- Implement MFA using TOTP for enhanced security.
- Update user settings UI to allow enabling/disabling MFA.
- Closes #42
```

## Guidelines

- **Keep it Short:**  
  Aim for a brief summary in the header. The body is optional but useful for complex changes.
- **Use the Imperative Mood:**  
  Write as if you were giving a command: “Fix bug” not “Fixed bug” or “Fixes bug.”
- **Be Descriptive:**  
  When necessary, explain why a change was made, not just what was changed.
- **Separate Logical Changes:**  
  If a commit contains multiple logical changes, consider splitting them into separate commits.

Following these guidelines ensures that our commit history remains clear and maintainable for everyone involved in NeuroDefender.
