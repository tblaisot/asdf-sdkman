<div align="center">

# asdf-sdkman [![Build](https://github.com/tblaisot/asdf-sdkman/actions/workflows/build.yml/badge.svg)](https://github.com/tblaisot/asdf-sdkman/actions/workflows/build.yml) [![Lint](https://github.com/tblaisot/asdf-sdkman/actions/workflows/lint.yml/badge.svg)](https://github.com/tblaisot/asdf-sdkman/actions/workflows/lint.yml)

[sdkman](https://sdkman.io/) plugin for the [asdf version manager](https://asdf-vm.com).

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
asdf plugin add sdkman
# or
asdf plugin add sdkman https://github.com/tblaisot/asdf-sdkman.git
```

sdkman:

```shell
# Show all installable versions
asdf list-all sdkman

# Install specific version
asdf install sdkman latest

# Set a version globally (on your ~/.tool-versions file)
asdf global sdkman latest

# Now sdkman commands are available
sdkman --help
```

Check [asdf](https://github.com/asdf-vm/asdf) readme for more instructions on how to
install & manage versions.

# Contributing

Contributions of any kind welcome! See the [contributing guide](contributing.md).

[Thanks goes to these contributors](https://github.com/tblaisot/asdf-sdkman/graphs/contributors)!

# License

See [LICENSE](LICENSE) © [tblaisot](https://github.com/tblaisot/)
