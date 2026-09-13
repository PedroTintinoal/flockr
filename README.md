# flockr

Small Go tool: declutter ~/Downloads in one command

## What it does

- Dry-run prints the plan before moving anything
- Skips hidden files and folders by default
- Single static binary, no runtime deps
- Groups files into folders by extension

## Install

```bash
go build -o bin/ ./...
```

## Examples

```bash
./bin/flockr ~/Downloads --dry-run
./bin/flockr ~/Downloads
```

## Project structure

```text
├── .github/
│   └── workflows/
│       └── ci.yml
├── docs/
│   ├── development.md
│   └── roadmap.md
├── examples/
│   └── quickstart.md
├── .gitignore
├── CHANGELOG.md
├── CODE_OF_CONDUCT.md
├── CONTRIBUTING.md
├── SECURITY.md
├── go.mod
└── main.go
```

## Development

```bash
go build ./...
go vet ./...
```
