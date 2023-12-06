<div align="center">

# asdf-asmcli [![Build](https://github.com/frits-v/asdf-asmcli/actions/workflows/build.yml/badge.svg)](https://github.com/frits-v/asdf-asmcli/actions/workflows/build.yml) [![Lint](https://github.com/frits-v/asdf-asmcli/actions/workflows/lint.yml/badge.svg)](https://github.com/frits-v/asdf-asmcli/actions/workflows/lint.yml)

[asmcli](https://cloud.google.com/service-mesh/docs/unified-install/reference) plugin for the [asdf version manager](https://asdf-vm.com).

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
asdf plugin add asmcli
# or
asdf plugin add asmcli https://github.com/frits-v/asdf-asmcli.git
```

asmcli:

```shell
# Show all installable versions
asdf list-all asmcli

# Install specific version
asdf install asmcli latest

# Set a version globally (on your ~/.tool-versions file)
asdf global asmcli latest

# Now asmcli commands are available
asmcli --help
```

Check [asdf](https://github.com/asdf-vm/asdf) readme for more instructions on how to
install & manage versions.

# Contributing

Contributions of any kind welcome! See the [contributing guide](contributing.md).

[Thanks goes to these contributors](https://github.com/frits-v/asdf-asmcli/graphs/contributors)!

# License

See [LICENSE](LICENSE) © [Frits](https://github.com/frits-v/)
