# X Modern Dark (VS Code Theme)

A VS Code color theme inspired by X.com (Twitter) modern UI dark mode: near‑black surfaces, cool neutral grays, and the signature blue accent.

## Install

- From the VSIX:
  1. Download the built `.vsix` (see Packaging below).
  2. In VS Code: Extensions panel → ⋮ → Install from VSIX… → select the file.

## Activate

- Open Command Palette → Preferences: Color Theme → select "X Modern Dark".

## Packaging (local)

If you want to build the VSIX yourself:

```bash
cd x-dark-theme
npx --yes @vscode/vsce package
```

This will create a file like `x-modern-dark-0.0.1.vsix` in the project folder.

## Notes

- This theme is an independent, fan-made interpretation of X.com's aesthetic.
- Tested against common languages; semantic highlighting is enabled.
