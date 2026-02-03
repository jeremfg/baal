# baal

Configuration code for the Ba'al machine. The hardware is a Framework 16 laptop running Linux Mint.

## Installation

The machine can be configured by calling this one-liner:

```bash
wget -qO- 'https://raw.githubusercontent.com/jeremfg/setup/refs/heads/main/src/setup_git' | bash -s -- git@github.com:jeremfg/baal.git main -- ./src/setup
```

## Development

To set up the development environment, run:

```bash
./tool/setup
```

This will install all necessary dependencies including git, python3, pre-commit hooks, and shellcheck.
