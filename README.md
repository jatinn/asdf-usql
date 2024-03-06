<div align="center">

# asdf-usql [![Build](https://github.com/jatinn/asdf-usql/actions/workflows/build.yml/badge.svg)](https://github.com/jatinn/asdf-usql/actions/workflows/build.yml) [![Lint](https://github.com/jatinn/asdf-usql/actions/workflows/lint.yml/badge.svg)](https://github.com/jatinn/asdf-usql/actions/workflows/lint.yml)

[usql](https://github.com/xo/usql) plugin for the [asdf version manager](https://asdf-vm.com).

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
asdf plugin add usql
# or
asdf plugin add usql https://github.com/jatinn/asdf-usql.git
```

usql:

```shell
# Show all installable versions
asdf list-all usql

# Install specific version
asdf install usql latest

# Set a version globally (on your ~/.tool-versions file)
asdf global usql latest

# Now usql commands are available
usql --version
```

Check [asdf](https://github.com/asdf-vm/asdf) readme for more instructions on how to
install & manage versions.

# Contributing

Contributions of any kind welcome! See the [contributing guide](contributing.md).

[Thanks goes to these contributors](https://github.com/jatinn/asdf-usql/graphs/contributors)!

# License

See [LICENSE](LICENSE) © [jatinn](https://github.com/jatinn/)
