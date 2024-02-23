<div align="center">

# asdf-sver [![Build](https://github.com/robzr/asdf-sver/actions/workflows/build.yml/badge.svg)](https://github.com/robzr/asdf-sver/actions/workflows/build.yml) [![Lint](https://github.com/robzr/asdf-sver/actions/workflows/lint.yml/badge.svg)](https://github.com/robzr/asdf-sver/actions/workflows/lint.yml)

[sver](https://github.com/robzr/sver) plugin for the [asdf version manager](https://asdf-vm.com).

</div>

# Contents

- [Dependencies](#dependencies)
- [Install](#install)
- [Contributing](#contributing)
- [License](#license)

# Dependencies

- `bash` v3 or newer - that's it

# Install

Plugin:

```shell
asdf plugin add sver
# or
asdf plugin add sver https://github.com/robzr/asdf-sver.git
```

sver:

```shell
# Show all installable versions
asdf list-all sver

# Install specific version
asdf install sver latest

# Set a version globally (on your ~/.tool-versions file)
asdf global sver latest

# Now sver commands are available
sver version
```

Check [asdf](https://github.com/asdf-vm/asdf) readme for more instructions on how to
install & manage versions.

# Contributing

Contributions of any kind welcome! See the [contributing guide](contributing.md).

[Thanks goes to these contributors](https://github.com/robzr/asdf-sver/graphs/contributors)!

# License

See [CC-BY-SA-3.0](https://creativecommons.org/licenses/by-sa/3.0/deed.en) © [Rob Zwissler](https://github.com/robzr/)
