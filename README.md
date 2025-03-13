<div align="center">

# asdf-starknet-devnet [![Build](https://github.com/ptisserand/asdf-starknet-devnet/actions/workflows/build.yml/badge.svg)](https://github.com/ptisserand/asdf-starknet-devnet/actions/workflows/build.yml) [![Lint](https://github.com/ptisserand/asdf-starknet-devnet/actions/workflows/lint.yml/badge.svg)](https://github.com/ptisserand/asdf-starknet-devnet/actions/workflows/lint.yml)

[starknet-devnet](https://0xspaceshard.github.io/starknet-devnet/) plugin for the [asdf version manager](https://asdf-vm.com).

</div>

# Contents

- [Dependencies](#dependencies)
- [Install](#install)
- [Contributing](#contributing)
- [License](#license)

# Dependencies

**TODO: adapt this section**

- `bash`, `curl`, `tar`, and [POSIX utilities](https://pubs.opengroup.org/onlinepubs/9699919799/idx/utilities.html).
- `SOME_ENV_VAR`: set this environment variable in your shell config to load the correct version of tool x.

# Install

Plugin:

```shell
asdf plugin add starknet-devnet
# or
asdf plugin add starknet-devnet https://github.com/ptisserand/asdf-starknet-devnet.git
```

starknet-devnet:

```shell
# Show all installable versions
asdf list-all starknet-devnet

# Install specific version
asdf install starknet-devnet latest

# Set a version
asdf set starknet-devnet latest

# Now starknet-devnet commands are available
starknet-devnet --version
```

Check [asdf](https://github.com/asdf-vm/asdf) readme for more instructions on how to
install & manage versions.

# Contributing

Contributions of any kind welcome! See the [contributing guide](contributing.md).

[Thanks goes to these contributors](https://github.com/ptisserand/asdf-starknet-devnet/graphs/contributors)!

# License

See [LICENSE](LICENSE) © [Patrice Tisserand](https://github.com/ptisserand/)
