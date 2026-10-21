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

* `user.name`: User name
* `user.email`: User email
* `user.signingkey`: GPG key ID for signing commits
* `core.editor`: Editor (e.g., vim, nano, code)
* `core.autocrlf`: Line endings (true, input, false)
* `alias.<alias-name>`: Alias (e.g., `alias.co = checkout`)
* `commit.gpgsign`: Switch for signing commits (true, false)
* `gpg.program`: GPG program for signing commits (e.g., gpg, gpg2)
