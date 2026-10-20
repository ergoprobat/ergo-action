# ergo-action

GitHub Action that runs ergo decision checks in CI and uploads SARIF results.

> Status: skeleton. The composite action lands in a later change, once a released CLI exists to download.

GitHub Marketplace requires an action at the root of its own repository. `action.yml` will be a composite action that downloads a released `ergo` binary and runs the check. Source for the CLI stays in the `ergo` repository.

## License

Apache License, Version 2.0. See [LICENSE](LICENSE).

Copyright 2026 Luca Bertelli.

## Contributing

Follow the contributor terms in [ergoprobat/.github](https://github.com/ergoprobat/.github/blob/main/CONTRIBUTING.md). Commits need a `Signed-off-by` trailer (`git commit -s`).
