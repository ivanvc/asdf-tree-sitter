# Contributing

Testing Locally:

```shell
asdf plugin test <plugin-name> <plugin-url> [--asdf-tool-version <version>] [--asdf-plugin-gitref <git-ref>] [test-command*]

# TODO: adapt this
asdf plugin test tree-sitter https://github.com/ivanvc/asdf-tree-sitter.git "tree-sitter --help"
```

Tests are automatically run in GitHub Actions on push and PR.
