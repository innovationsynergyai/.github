# Contributing

Thanks for your interest. These guidelines cover repositories owned by [innovationsynergyai](https://github.com/innovationsynergyai) — the personal account of Michael Joseph Bowen, Principal Forward Deployed Engineer at [INNOVATION SYNERGY AI](https://github.com/INNOVATION-SYNERGY-AI).

## Before you start

Most of this account's repositories are private client work. If a repository is public, contributions are welcome. If you reached a private repository through a client engagement, follow the process agreed in that engagement instead of this document.

## Ground rules

- Never include client names, credentials, API keys, provisioning profiles, customer data, or screenshots containing real customer records.
- Keep pull requests focused. One concern per pull request.
- Match the existing style of the file you are editing. Swift code follows the Swift API Design Guidelines.
- Open an issue before starting large or architectural changes so we can agree on direction first.

## Workflow

1. Fork the repository and create a branch from `main`.
2. Use a descriptive branch name, for example `fix/quote-form-validation` or `feat/mass-save-qualifier`.
3. Make your change and build locally. For Apple targets, build and run on a real device where the change touches UI, networking, or permissions.
4. Write a clear commit message in the imperative mood.
5. Open a pull request against `main` and fill in the template.

## Apple platform expectations

- Swift and SwiftUI first. Avoid adding dependencies unless they earn their weight.
- Support the minimum OS version declared by the target. Do not raise it in a drive-by change.
- Respect accessibility: Dynamic Type, VoiceOver labels, and sufficient contrast.
- Keep the app usable on a bad connection. Field software runs in basements and on roofs.
- Do not add analytics, tracking, or third-party SDKs that collect data without discussion.

## Reporting problems

Use the issue templates. For anything security related, do not open an issue — see [SECURITY.md](SECURITY.md).

## Questions

See [SUPPORT.md](SUPPORT.md) or email michael@innovationsynergyai.com.
