# PeachlifeAB Homebrew Tap

Public Homebrew tap for PeachlifeAB tools.

## Install

```bash
brew tap peachlifeab/tap
```

## Formulas

### lgtvctrl

Command-line control for LG WebOS TVs — power, input, screen, queries, and raw commands over WebSocket.

```bash
brew install peachlifeab/tap/lgtvctrl
```

Pre-built bottle available for Apple Silicon (arm64 Tahoe). Source: [PeachlifeAB/lgtvctrl](https://github.com/PeachlifeAB/lgtvctrl)

### bgtail

Run long-running commands detached with minimal heartbeat — background a command, reconnect later, get the log.

```bash
brew install peachlifeab/tap/bgtail
```

Source: [PeachlifeAB/bgtail](https://github.com/PeachlifeAB/bgtail)

### sive

Sync secrets from your vault into your shell.

```bash
brew install peachlifeab/tap/sive
```

Source: [PeachlifeAB/sive](https://github.com/PeachlifeAB/sive)

## Casks

### Hyprspace

Tiling window manager based on AeroSpace. Requires macOS 15 (Sequoia) or later.

```bash
brew install --cask peachlifeab/tap/hyprspace
```

Homepage: [hyprspace.net](https://hyprspace.net/) · Source: [PeachlifeAB/hyprspace-core](https://github.com/PeachlifeAB/hyprspace-core) · Releases: [PeachlifeAB/hyprspace-releases](https://github.com/PeachlifeAB/hyprspace-releases)

## Update

```bash
brew upgrade peachlifeab/tap/<name>
```

## Uninstall

```bash
brew uninstall <name>
brew untap peachlifeab/tap
```
