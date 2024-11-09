<div align="center">

# asdf-kitops [![Build](https://github.com/zloeber/asdf-kitops/actions/workflows/build.yml/badge.svg)](https://github.com/zloeber/asdf-kitops/actions/workflows/build.yml) [![Lint](https://github.com/zloeber/asdf-kitops/actions/workflows/lint.yml/badge.svg)](https://github.com/zloeber/asdf-kitops/actions/workflows/lint.yml)

[kitops](https://github.com/jozu-ai/kitops) plugin for the [asdf version manager](https://asdf-vm.com).

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
asdf plugin add kitops
# or
asdf plugin add kitops https://github.com/zloeber/asdf-kitops.git
```

kitops:

```shell
# Show all installable versions
asdf list-all kitops

# Install specific version
asdf install kitops latest

# Set a version globally (on your ~/.tool-versions file)
asdf global kitops latest

# Now kitops commands are available
kit version
```

Check [asdf](https://github.com/asdf-vm/asdf) readme for more instructions on how to
install & manage versions.

# Contributing

Contributions of any kind welcome! See the [contributing guide](contributing.md).

[Thanks goes to these contributors](https://github.com/zloeber/asdf-kitops/graphs/contributors)!

# License

See [LICENSE](LICENSE) © [Zachary Loeber](https://github.com/zloeber/)
