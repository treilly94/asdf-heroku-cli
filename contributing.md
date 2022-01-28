# Contributing

Testing Locally:

```shell
asdf plugin test <plugin-name> <plugin-url> [--asdf-tool-version <version>] [--asdf-plugin-gitref <git-ref>] [test-command*]

#
asdf plugin test heroku-cli https://github.com/treilly94/asdf-heroku-cli.git "heroku --help"
```

Tests are automatically run in GitHub Actions on push and PR.
