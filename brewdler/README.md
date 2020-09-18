# settings

## Brewfile
### Backup
brewdlerをinstall
```shell
$ brew tap Homebrew/brewdler
```
brew fileのdump
```shell
$ brew bundle dump
```
### Restore
1. Homebrewのインストール
1. `brew install git` brew経由で`git`インストール
1. `Brewfile`を`git clone`
1. `brew bundle`実行
