# Contributing

Thanks for helping! This guide applies to every `orchnesai` repository that has no `CONTRIBUTING.md` of its own.
Please read the [code of conduct](CODE_OF_CONDUCT.md). Security issues go through [SECURITY.md](SECURITY.md), not public issues.

## Before you start
- For anything bigger than a small fix, open an issue first so we can agree on the approach.
- Check the repository's README for build and test commands.

## Pull requests
1. Fork the repository and create a branch from `main`.
2. Keep the PR small and focused; describe what changes and how you tested it.
3. CI must be green. `main` is protected: changes land through pull requests and are squash-merged.
4. Do not commit secrets, API keys or personal data.

## Repository guides
- [orchnes-360](https://github.com/orchnesai/orchnes-360/blob/main/CONTRIBUTING.md): adding or improving skills.
- [orchnes-cli](https://github.com/orchnesai/orchnes-cli): Rust; run `cargo fmt --check`, `cargo clippy --all-targets -- -D warnings` and `cargo test` before opening a PR.
