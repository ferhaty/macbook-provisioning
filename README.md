# Macbook Provisioning

Automate your macOS Configuration by using Brewfile

## Getting started

Install Homebrew

```bash
./homebrew.sh
```

## Install packages

Customize the `Brewfile` where needed.

```bash
brew bundle -v
```

## Auto update

Enable auto update every 24 hours.

```
brew autoupdate start 86400 --upgrade --cleanup --immediate --sudo
```

## Install pip packages

```bash
pip install -r requirements.txt
```

## Install NPM packages

```bash
npm install -g
```

## Install Ruby Gems

```bash
bundle install
```

## Bash Aliases

Include the following line in `~/.bash_profile` .

```bash
if [ -f "$HOME/aliases.bash.inc" ]; then . "$HOME/aliases.bash.inc"; fi
```

Copy `aliases.bash.inc` to your home directory using the following command.

```bash
cp aliases.bash.inc ~/
```
