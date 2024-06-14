# Contributing

Testing Locally:

```shell
asdf plugin test <plugin-name> <plugin-url> [--asdf-tool-version <version>] [--asdf-plugin-gitref <git-ref>] [test-command*]

# TODO: adapt this
asdf plugin test starknet-devnet https://github.com/ptisserand/asdf-starknet-devnet.git "starknet-devnet --version"
```

Tests are automatically run in GitHub Actions on push and PR.
