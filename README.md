# Governor

Policy engine for AI agent tool governance.

Every human tool has a safety — the red button, the confirmation dialog, the childproof cap. AI agents have none of it. Governor is the missing safety layer.

## Install

```bash
brew tap tymrtn/governor
brew install governor
```

Or download from [Releases](https://github.com/tymrtn/governor/releases).

## Usage

```bash
# Run a command through governor
governor <command> [args...]

# Governed passthrough with attributes
governor <command> [args...] -- --attr <key> [--attr <key> ...]

# See all options and available attributes
governor --help
```

## License

Functional Source License 1.1, Apache 2.0 Future License (FSL-1.1-ALv2).

© 2026 Tyler Martin. All rights reserved.

