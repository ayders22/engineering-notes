# git config

## List configuration

```sh
git config list [--local|--global|--show-origin]
```

## Get/set/unset configuration

```sh
git config set [--local|--global] <config-key> <config-value>
git config get [--local|--global] <config-key>
git config unset [--local|--global] <config-key>
```

### Configuration keys

* `user.name`: User name for commits
* `user.email`: User email for commits
* `user.signingkey`: GPG key ID for signing commits
* `core.editor`: Editor for commit messages (e.g., vim, nano, code)
* `core.autocrlf`: Handle line endings automatically (true, input, false)
* `alias.<alias-name>`: Create a custom command alias (e.g., `alias.co = checkout`)
* `commit.gpgsign`: Sign commits by default (true, false)
* `gpg.program`: GPG program to use for signing commits (e.g., gpg, gpg2)
