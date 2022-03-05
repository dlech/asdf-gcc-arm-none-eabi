<div align="center">

# asdf-gcc-arm-none-eabi [![Build](https://github.com/dlech/asdf-gcc-arm-none-eabi/actions/workflows/build.yml/badge.svg)](https://github.com/dlech/asdf-gcc-arm-none-eabi/actions/workflows/build.yml) [![Lint](https://github.com/dlech/asdf-gcc-arm-none-eabi/actions/workflows/lint.yml/badge.svg)](https://github.com/dlech/asdf-gcc-arm-none-eabi/actions/workflows/lint.yml)


[gcc-arm-none-eabi](https://developer.arm.com/tools-and-software/open-source-software/developer-tools/gnu-toolchain) plugin for the [asdf version manager](https://asdf-vm.com).

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
asdf plugin add gcc-arm-none-eabi
# or
asdf plugin add gcc-arm-none-eabi https://github.com/dlech/asdf-gcc-arm-none-eabi.git
```

gcc-arm-none-eabi:

```shell
# Show all installable versions
asdf list-all gcc-arm-none-eabi

# Install specific version
asdf install gcc-arm-none-eabi latest

# Set a version globally (on your ~/.tool-versions file)
asdf global gcc-arm-none-eabi latest

# Now gcc-arm-none-eabi commands are available
arm-none-eabi-gcc --version
```

Check [asdf](https://github.com/asdf-vm/asdf) readme for more instructions on how to
install & manage versions.

# Contributing

Contributions of any kind welcome! See the [contributing guide](contributing.md).

[Thanks goes to these contributors](https://github.com/dlech/asdf-gcc-arm-none-eabi/graphs/contributors)!

# License

See [LICENSE](LICENSE) © [David Lechner](https://github.com/dlech/)
