<div align="center">

# asdf-zjstatus [![Build](https://github.com/rmgpinto/asdf-zjstatus/actions/workflows/build.yml/badge.svg)](https://github.com/rmgpinto/asdf-zjstatus/actions/workflows/build.yml) [![Lint](https://github.com/rmgpinto/asdf-zjstatus/actions/workflows/lint.yml/badge.svg)](https://github.com/rmgpinto/asdf-zjstatus/actions/workflows/lint.yml)

[zjstatus](https://github.com/dj95/zjstatus) plugin for the [asdf version manager](https://asdf-vm.com).

</div>

# Contents

- [Dependencies](#dependencies)
- [Install](#install)
- [Contributing](#contributing)
- [License](#license)

# Dependencies

- `bash`, `curl`, and [POSIX utilities](https://pubs.opengroup.org/onlinepubs/9699919799/idx/utilities.html).

# Install

Plugin:

```shell
asdf plugin add zjstatus
# or
asdf plugin add zjstatus https://github.com/rmgpinto/asdf-zjstatus.git
```

zjstatus:

```shell
# Show all installable versions
asdf list-all zjstatus

# Install specific version
asdf install zjstatus latest

# Set a version globally (on your ~/.tool-versions file)
asdf global zjstatus latest

# Now zjstatus commands are available
echo 1
```

Check [asdf](https://github.com/asdf-vm/asdf) readme for more instructions on how to
install & manage versions.

# Contributing

Contributions of any kind welcome! See the [contributing guide](contributing.md).

[Thanks goes to these contributors](https://github.com/rmgpinto/asdf-zjstatus/graphs/contributors)!

# License

See [LICENSE](LICENSE) © [Ricardo Pinto](https://github.com/rmgpinto/)
