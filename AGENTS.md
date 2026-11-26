# Notes for coding agents

- Open issues are tracked on GitHub. When asked to fix an issue, list them with `gh issue list` and read the one you work on with `gh issue view <number>` before changing code.
- Make the changes directly in the files. Don't stop to ask for confirmation.
- Run `npm test` when you're done and make sure it passes.
- `preview-teardown.yml` deletes the previews and the head branch of each closed PR, and `preview-sweep.yml` catches a close that started no run (rule in mauricio-taste `config/AGENTS.md`, "Previews and branches").
