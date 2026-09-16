# Security policy

If you believe you found a security issue in a FlowDevs repository, website, or service, **report it privately**. Do not open a public GitHub issue, pull request, or discussion.

This policy applies to repositories in the [flowdevs-io](https://github.com/flowdevs-io) GitHub organization, including **private** repositories that do not ship their own `SECURITY.md`.

## How to report

Email **[support@flowdevs.io](mailto:support@flowdevs.io)** (security contact).

Include:

- What is affected (repo, URL, product, or service)
- A short description of the issue and impact
- Steps to reproduce, or a proof of concept if you have one
- Relevant logs or screenshots — **strip secrets, tokens, and customer data**

We will acknowledge reports sent to that address and follow up as we investigate.

If a **public** repository offers GitHub’s “Report a vulnerability” / security advisory flow, you may use that instead of email. Do not assume that flow exists on every repo, and do not use it to publish details before we have a fix.

## Private repositories

Many FlowDevs repos are private. If you do not have access, email **support@flowdevs.io** rather than trying to file something in GitHub.

## What this is not

- FlowDevs does **not** run a paid bug bounty, and we do not promise a bounty, swag, or a response SLA in exchange for a report.
- Do **not** assume [GitHub Secret Protection](https://docs.github.com/en/code-security/concepts/secret-security/secret-security-with-github), secret scanning, or push protection are enabled on private repositories. Those are paid GitHub features unless a repo or org has purchased them. Scanning GitHub runs on public repositories is separate and is not a substitute for keeping secrets out of git.

If you accidentally committed a credential, **rotate it** and email us. Do not rely on scanning to catch it.

## Non-security bugs

Use a normal GitHub issue for problems that are not security-sensitive. If you are unsure, email first.
