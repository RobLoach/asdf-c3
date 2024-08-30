# Contributing

Testing Locally:

```shell
asdf plugin test <plugin-name> <plugin-url> [--asdf-tool-version <version>] [--asdf-plugin-gitref <git-ref>] [test-command*]

# TODO: adapt this
asdf plugin test c3 https://github.com/RobLoach/asdf-c3.git "c3c --version"
```

Tests are automatically run in GitHub Actions on push and PR.
