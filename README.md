<div align="center">

# asdf-zoxide ![Build](https://github.com/nyrst/asdf-zoxide/workflows/Build/badge.svg) ![Lint](https://github.com/nyrst/asdf-zoxide/workflows/Lint/badge.svg)

[zoxide](https://github.com/ajeetdsouza/zoxide) plugin for the [asdf version manager](https://asdf-vm.com).

</div>

# Contents

- [Dependencies](#dependencies)
- [Install](#install)
- [Why?](#why)
- [Contributing](#contributing)
- [License](#license)

# Dependencies

- `bash`, `curl`, `tar`: generic POSIX utilities.
- `SOME_ENV_VAR`: set this environment variable in your shell config to load the correct version of tool x.

# Install

Plugin:

```shell
asdf plugin add zoxide
# or
asdf plugin add zoxide https://github.com/nyrst/asdf-zoxide.git
```

zoxide:

```shell
# Show all installable versions
asdf list-all zoxide

# Install specific version
asdf install zoxide latest

# Set a version globally (on your ~/.tool-versions file)
asdf global zoxide latest

# Now zoxide commands are available
zoxide --version
```

Check [asdf](https://github.com/asdf-vm/asdf) readme for more instructions on how to
install & manage versions.

# Contributing

Contributions of any kind welcome! See the [contributing guide](contributing.md).

[Thanks goes to these contributors](https://github.com/nyrst/asdf-zoxide/graphs/contributors)!

# License

See [LICENSE](LICENSE) © [Siegfried Ehret](https://github.com/SiegfriedEhret/)
