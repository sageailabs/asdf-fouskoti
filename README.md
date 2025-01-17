<div align="center">

# asdf-fouskoti [![Build](https://github.com/sageailabs/asdf-fouskoti/actions/workflows/build.yml/badge.svg)](https://github.com/sageailabs/asdf-fouskoti/actions/workflows/build.yml) [![Lint](https://github.com/sageailabs/asdf-fouskoti/actions/workflows/lint.yml/badge.svg)](https://github.com/sageailabs/asdf-fouskoti/actions/workflows/lint.yml)

[fouskoti](https://github.com/sageailabs/fouskoti) plugin for the [asdf version manager](https://asdf-vm.com).

</div>

# Contents

- [Dependencies](#dependencies)
- [Install](#install)
- [Contributing](#contributing)
- [License](#license)

# Dependencies

- `bash`, `curl`, `tar`, and [POSIX utilities](https://pubs.opengroup.org/onlinepubs/9699919799/idx/utilities.html).

# Install

Plugin:

```shell
asdf plugin add fouskoti
# or
asdf plugin add fouskoti https://github.com/sageailabs/asdf-fouskoti.git
```

fouskoti:

```shell
# Show all installable versions
asdf list-all fouskoti

# Install specific version
asdf install fouskoti latest

# Set a version globally (on your ~/.tool-versions file)
asdf global fouskoti latest

# Now fouskoti commands are available
fouskoti version
```

Check [asdf](https://github.com/asdf-vm/asdf) readme for more instructions on how to
install & manage versions.

# Contributing

Contributions of any kind welcome! See the [contributing guide](contributing.md).

[Thanks goes to these contributors](https://github.com/sageailabs/asdf-fouskoti/graphs/contributors)!

# License

See [LICENSE](LICENSE) © The Sage Group plc or its licensors.
