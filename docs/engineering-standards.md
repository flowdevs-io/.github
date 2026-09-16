# FlowDevs engineering standards

Short defaults for shared work in the [flowdevs-io](https://github.com/flowdevs-io) GitHub organization. Individual repositories may be stricter. Do not relax the secrets or 2FA rules.

## Default branch

Use **`main`** as the default branch for new and shared FlowDevs repositories.

## Pull requests

Changes to **shared** repositories go through a pull request. Do not push commits directly to `main` on a repo other people rely on.

## GitHub Actions

Pin Actions to a full commit **SHA**, not a moving tag (`@v4`, `@main`). That applies to third-party actions and to anything we reuse across repos.

This org `.github` repository does **not** ship reusable workflows or product CI. Do not treat it as a workflow catalog.

## Secrets

Never commit secrets, tokens, private keys, or customer data. Store them in GitHub Actions secrets, 1Password, or the owning system’s secret store.

Do not assume GitHub Secret Protection or secret scanning is enabled on **private** repositories. Rotate anything that leaked.

## Two-factor authentication

GitHub **2FA is required** for FlowDevs org members and for anyone with write access to our repositories.
