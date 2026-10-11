# Homebrew tap for Espetero

[Espetero](https://github.com/JarJarFran/espetero) is a native Metal LLM server for Apple silicon.

```bash
brew install JarJarFran/espetero/espetero
```

The formula builds Espetero from the release's source (Xcode Command Line Tools needed). `brew services start espetero` runs `espetero serve` at login with the settings of `~/.config/espetero/config.json`.
