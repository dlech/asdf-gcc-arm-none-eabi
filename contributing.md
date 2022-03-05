# Contributing

Testing Locally:

```shell
asdf plugin test <plugin-name> <plugin-url> [--asdf-tool-version <version>] [--asdf-plugin-gitref <git-ref>] [test-command*]

#
asdf plugin test gcc-arm-none-eabi https://github.com/dlech/asdf-gcc-arm-none-eabi.git "arm-none-eabi-gcc --version"
```

Tests are automatically run in GitHub Actions on push and PR.
