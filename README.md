# ru-461/tap

Homebrew formulae for tools by [ru-461](https://github.com/ru-461).

## Formulae

| Formula | Description |
|---------|-------------|
| [`vv-synth`](https://github.com/ru-461/vv-synth) | Text-to-speech CLI for VOICEVOX Engine |

`vv-synth` needs a separately running VOICEVOX Engine; the formula does not install it.

## How do I install these formulae?

```shell
brew install ru-461/tap/<formula>
```

Installing by the fully qualified name trusts only that formula
([tap trust](https://docs.brew.sh/Tap-Trust), Homebrew 6.0+). To install by short name,
trust the formula first:

```shell
brew tap ru-461/tap
brew trust --formula ru-461/tap/<formula>
brew install <formula>
```

Or, in a `brew bundle` `Brewfile`:

```ruby
brew "ru-461/tap/<formula>", trusted: true
```

## Documentation

`brew help`, `man brew` or check [Homebrew's documentation](https://docs.brew.sh).
