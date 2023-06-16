<div align="center">

# asdf-tree-sitter [![Build](https://github.com/ivanvc/asdf-tree-sitter/actions/workflows/build.yml/badge.svg)](https://github.com/ivanvc/asdf-tree-sitter/actions/workflows/build.yml) [![Lint](https://github.com/ivanvc/asdf-tree-sitter/actions/workflows/lint.yml/badge.svg)](https://github.com/ivanvc/asdf-tree-sitter/actions/workflows/lint.yml)

[tree-sitter](https://github.com/tree-sitter/tree-sitter) plugin for the [asdf version manager](https://asdf-vm.com).

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
asdf plugin add tree-sitter
# or
asdf plugin add tree-sitter https://github.com/ivanvc/asdf-tree-sitter.git
```

tree-sitter:

```shell
# Show all installable versions
asdf list-all tree-sitter

# Install specific version
asdf install tree-sitter latest

# Set a version globally (on your ~/.tool-versions file)
asdf global tree-sitter latest

# Now tree-sitter commands are available
tree-sitter --help
```

Check [asdf](https://github.com/asdf-vm/asdf) readme for more instructions on how to
install & manage versions.

# Contributing

Contributions of any kind welcome! See the [contributing guide](contributing.md).

[Thanks goes to these contributors](https://github.com/ivanvc/asdf-tree-sitter/graphs/contributors)!

# License

See [LICENSE](LICENSE) © [Ivan Valdes](https://github.com/ivanvc/)
