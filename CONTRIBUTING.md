# Contributing

Thanks for helping improve curl-sms. This guide applies to every repository in the [curl-sms organization](https://github.com/curl-sms) unless a repository has its own `CONTRIBUTING.md`.

## Questions and support

- Account, billing or delivery questions: email [help@curl-sms.com](mailto:help@curl-sms.com). Please do not post account details or phone numbers in public issues.
- API usage questions: check the [docs](https://curl-sms.com/docs) first, then open an issue in the repository you are using.

## Reporting bugs

Open an issue with the bug report template. Include the SDK or tool version, your runtime version, what you expected and what happened. Redact API keys and phone numbers. The SMS `id` and the error `code` are enough for us to look it up.

Security issues go to help@curl-sms.com, see [SECURITY.md](SECURITY.md).

## Pull requests

1. Open an issue first for anything bigger than a small fix, so we can agree on the approach.
2. Fork the repository and create a branch from `main`.
3. Keep the change focused. Add or update tests and docs.
4. Run the repository's checks locally (see its README); CI must be green.
5. Use test keys (`cs_test_…`) and the example number `+4915123456789` in code, tests and docs. Never commit live keys.

By contributing you agree that your contribution is licensed under the repository's license (MIT unless stated otherwise).

## Style

- English for code, comments, docs and commit messages.
- Short, imperative commit subjects (`Add retry on 429`).
- Follow the existing formatting; each repository runs its formatter and linter in CI.
