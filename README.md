# gh-switch-user

An extension to make it easier to switch between GitHub accounts in the `gh` CLI.

## Installation

```sh
# Clone and install
git clone https://github.com/stuartleeks/gh-switch-user.git ~/.gh-switch-user
cd ~/.gh-switch-user
gh extension install .
```

## Usage

```sh
# Save the current user config
gh switch-user --save

# Sign in with new user
gh auth login

# Switch back to the saved user (change my-username to the username you originally saved)
gh switch-user my-username
```

## Uninstall

```sh
gh extension remove gh-switch-user
```