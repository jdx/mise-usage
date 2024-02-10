<div align="center">

# mise-usage [![Build](https://github.com/jdx/mise-usage/actions/workflows/build.yml/badge.svg)](https://github.com/jdx/mise-usage/actions/workflows/build.yml) [![Lint](https://github.com/jdx/mise-usage/actions/workflows/lint.yml/badge.svg)](https://github.com/jdx/mise-usage/actions/workflows/lint.yml)

[usage](https://usage.jdx.dev) plugin for the [mise version manager](https://mise.jdx.dev).

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
mise plugin add usage
# or
mise plugin add usage https://github.com/jdx/mise-usage.git
```

usage:

```shell
# Show all installable versions
mise list-all usage

# Install specific version
mise install usage latest

# Set a version globally (on your ~/.tool-versions file)
mise global usage latest

# Now usage commands are available
usage --version
```

Check [mise](https://github.com/mise-vm/mise) readme for more instructions on how to
install & manage versions.

# Contributing

Contributions of any kind welcome! See the [contributing guide](contributing.md).

[Thanks goes to these contributors](https://github.com/jdx/mise-usage/graphs/contributors)!

# License

See [LICENSE](LICENSE) © [jdx](https://github.com/jdx/)
