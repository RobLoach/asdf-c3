<div align="center">

# asdf-c3 [![Build](https://github.com/RobLoach/asdf-c3/actions/workflows/build.yml/badge.svg)](https://github.com/RobLoach/asdf-c3/actions/workflows/build.yml) [![Lint](https://github.com/RobLoach/asdf-c3/actions/workflows/lint.yml/badge.svg)](https://github.com/RobLoach/asdf-c3/actions/workflows/lint.yml)

[C3](https://c3-lang.org/) plugin for the [asdf version manager](https://asdf-vm.com).

</div>

# Contents

- [Dependencies](#dependencies)
- [Install](#install)
- [Contributing](#contributing)
- [License](#license)

# Dependencies

- `git`
- `curl`
- `awk`
- `sed`
- `tar` (Linux/BSD)
- `unzip` (macOS)

# Install

Plugin:

```shell
asdf plugin add c3
```

c3c:

```shell
# Show all installable versions
asdf list all c3

# Install the latest version
asdf install c3 latest

# Set a version globally (on your ~/.tool-versions file)
asdf set -u c3 latest

# Now c3c commands are available
c3c --version
```

Check [asdf](https://github.com/asdf-vm/asdf) readme for more instructions on how to
install & manage versions.

# Contributing

Contributions of any kind welcome! See the [contributing guide](contributing.md).

[Thanks goes to these contributors](https://github.com/RobLoach/asdf-c3/graphs/contributors)!

# License

See [LICENSE](LICENSE) © [Rob Loach](https://github.com/RobLoach/)
