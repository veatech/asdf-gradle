<div align="center">

# asdf-gradle [![Build](https://github.com/tripplilley/asdf-gradle/actions/workflows/build.yml/badge.svg)](https://github.com/tripplilley/asdf-gradle/actions/workflows/build.yml) [![Lint](https://github.com/tripplilley/asdf-gradle/actions/workflows/lint.yml/badge.svg)](https://github.com/tripplilley/asdf-gradle/actions/workflows/lint.yml)


[gradle](https://docs.gradle.org/current/userguide/userguide.html) plugin for the [asdf version manager](https://asdf-vm.com).

</div>

# Contents

- [Dependencies](#dependencies)
- [Install](#install)
- [Contributing](#contributing)
- [License](#license)

# Dependencies

**TODO: adapt this section**

- `bash`, `curl`, `tar`: generic POSIX utilities.
- `SOME_ENV_VAR`: set this environment variable in your shell config to load the correct version of tool x.

# Install

Plugin:

```shell
asdf plugin add gradle
# or
asdf plugin add gradle https://github.com/tripplilley/asdf-gradle.git
```

gradle:

```shell
# Show all installable versions
asdf list-all gradle

# Install specific version
asdf install gradle latest

# Set a version globally (on your ~/.tool-versions file)
asdf global gradle latest

# Now gradle commands are available
gradle -v
```

Check [asdf](https://github.com/asdf-vm/asdf) readme for more instructions on how to
install & manage versions.

# Contributing

Contributions of any kind welcome! See the [contributing guide](contributing.md).

[Thanks goes to these contributors](https://github.com/tripplilley/asdf-gradle/graphs/contributors)!

# License

See [LICENSE](LICENSE) © [Tripp Lilley](https://github.com/tripplilley/)
