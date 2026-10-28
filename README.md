# SimTool Homebrew tap

[SimTool](https://github.com/platacard/SimTool) streams and automates Apple
Simulators. The build is for Apple silicon (arm64).

```sh
brew tap platacard/simtool
brew trust platacard/simtool         # Homebrew loads a third-party tap's formulae only once it is trusted
brew install simtool
simtool doctor
```

Upgrade with `brew upgrade simtool`. Installs from the previous tap move here
on `brew update`.
