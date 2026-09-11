# Naman's Homebrew tap

## Canvas Buddy

```sh
brew install naman0r/tap/canvas-buddy
canvas-buddy
```

Connect your own Canvas URL and access token in first-run setup. For model answers, use an authenticated Codex/OpenCode CLI or a local Ollama chat model. Ollama embeddings are optional; keyword search works without them. No models are downloaded by the formula.

```sh
canvas-buddy doctor
canvas-buddy self-test
brew update
brew upgrade naman0r/tap/canvas-buddy
```

[Source, setup and privacy details](https://github.com/naman0r/canvas-buddy).

The formula installs an isolated Python environment from a versioned source release and checksummed dependency archives. Uninstalling keeps your private Canvas data; see the app README for deletion instructions.

## Maintainer checks

```sh
brew style naman0r/tap/canvas-buddy
brew install --build-from-source naman0r/tap/canvas-buddy
brew test naman0r/tap/canvas-buddy
```

Regenerate release URLs/resources using `scripts/homebrew_formula.py` in the source repository. Test before pushing updates; never move a published source tag.
