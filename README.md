# SETUP - Setup Development Enviroment Plugin for [ZMicro](https://github.com/zcorky/zmicro)

[![Release](https://img.shields.io/github/tag/zmicro-design/plugin-setup.svg?label=Release)](https://github.com/zmicro-design/plugin-setup/tags)
[![Build Status](https://github.com/zmicro-design/plugin-setup/actions/workflows/test.yml/badge.svg?branch=master)](https://github.com/zmicro-design/plugin-setup/actions/workflows/test.yml)
[![GitHub issues](https://img.shields.io/github/issues/zmicro-design/plugin-setup.svg)](https://github.com/zmicro-design/plugin-setup/issues)

## Installation

To install the package, run:

```bash
zmicro plugin install setup
```

### If you donot install [ZMicro](https://github.com/zcorky/zmicro):

```bash
# CURL
curl -o- https://raw.githubusercontent.com/zmicro-design/plugin-setup/master/install | bash

# WGET
wget -qO- https://raw.githubusercontent.com/zmicro-design/plugin-setup/master/install | bash
```

## Usage

```markdown
setup (v0.0.0)

Setup Developer Environment

Usage:
  zmicro setup action <language>      - Setup developer language environment
  zmicro setup help                   - Show help

Example:
  zmicro setup action go              - Setup Go environment
  zmicro setup action node            - Setup Node.js environment
```

## License

ZMicro Design is released under the [MIT License](./LICENSE).
