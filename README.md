# hello-world

This repository is a playground for experimenting with GitHub Flow and basic
tooling configuration.

## Repository structure

- `LICENSE` – The MIT license covering this example project.
- `.vscode/launch.json` – VS Code debug profile for launching the project in a
  Chromium-based browser.

Feel free to add additional folders such as `src/` for source code or `docs/`
for documentation as you grow the project.

## Debugging in VS Code

1. Open the repository in VS Code.
2. Ensure you have a development server running on `http://localhost:8080` (for
   example, via `npm run dev` in a separate terminal).
3. Press <kbd>F5</kbd> and select **Launch Chrome against localhost**.

The launch configuration uses the built-in *pwa-chrome* debugger, so no extra
extensions are required.
