# Contributing to GitPulse

Thanks for helping improve GitPulse.

## Before you start

1. Search existing issues for duplicates.
2. Open an issue for substantial feature changes before implementing them.
3. Keep changes focused and explain their user impact.

## Local setup

Clone the repository and run a static web server from its root:

```bash
python -m http.server 8000
```

Open http://localhost:8000.

## Pull requests

- Create a descriptive branch, such as `fix/profile-loading` or `docs/readme`.
- Avoid unrelated formatting or large refactors.
- Test the landing page, public-profile search, navigation, mobile layout, and light/dark themes.
- Describe your testing steps and link any relevant issue.
- Do not commit API tokens, credentials, or private user data.

## Reporting bugs

Include steps to reproduce, expected and actual behavior, browser/device, and any relevant console errors (with secrets removed).

## Licensing

The repository currently has no explicit open-source license. Contributions do not by themselves grant third parties permission to redistribute the project.
