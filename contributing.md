# Contributing

Testing Locally:

```shell
asdf plugin test <plugin-name> <plugin-url> [--asdf-tool-version <version>] [--asdf-plugin-gitref <git-ref>] [test-command*]

asdf plugin test zjstatus https://github.com/rmgpinto/asdf-zjstatus.git "echo 1"
```

Tests are automatically run in GitHub Actions on push and PR.
