# Contributing

Testing Locally:

```shell
asdf plugin test <plugin-name> <plugin-url> [--asdf-tool-version <version>] [--asdf-plugin-gitref <git-ref>] [test-command*]

#
asdf plugin test gradle https://github.com/tripplilley/asdf-gradle.git "gradle -v"
```

Tests are automatically run in GitHub Actions on push and PR.
