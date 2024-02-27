# Contributing

Testing Locally:

```shell
asdf plugin test <plugin-name> <plugin-url> [--asdf-tool-version <version>] [--asdf-plugin-gitref <git-ref>] [test-command*]

asdf plugin test fouskoti https://github.com/vladlosev/asdf-fouskoti.git "fouskoti version"
```

Tests are automatically run in GitHub Actions on push and PR.
