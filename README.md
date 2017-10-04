# Homebrew Repo
A centralized repo for any custom Homebrew formalae that I use.

## Requirements

* [Homebrew](https://github.com/Homebrew/brew)
* Yosemite, El Capitan, and Sierra. Untested everywhere else.

## Installation
### Tap

Run the following in your command-line:

```sh
$ brew tap Nunnery/homebrew-repo
```

### Formulae
#### yarn-nightly

If you want to install node as well, run the following in your command-line after tapping:

```sh
$ brew install yarn-nightly
```

If you don't want to install node as well (due to using nvm or other node managers), run the following in your command-line after tapping:

```sh
$ brew install yarn-nightly --without-node
```

## License

See [LICENSE](LICENSE).
