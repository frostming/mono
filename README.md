# Monas

[![Tests](https://github.com/frostming/monas/workflows/Tests/badge.svg)](https://github.com/frostming/monas/actions?query=workflow%3Aci)
[![pypi version](https://img.shields.io/pypi/v/monas.svg)](https://pypi.org/project/monas/)
[![Code style: black](https://img.shields.io/badge/code%20style-black-000000.svg)](https://github.com/psf/black)
[![pdm-managed](https://img.shields.io/badge/pdm-managed-blueviolet)](https://pdm.fming.dev)

Python monorepo made easy.

🚧 **[WIP]** This project still in a rapid development and the behaviors may change. 🚧

## Features

**Monas** is a tool to manage multiple Python projects in a single monorepo. It is mainly inspired by [Lerna](https://lerna.js.org/). It supports the following build systems:

- [setuptools](https://setuptools.pypa.io/)
- [pdm](https://pdm.fming.dev/)
- [flit](https://flit.pypa.io/)
- [hatch](https://ofek.dev/hatch/latest/)

## Installation

**Monas** requires Python >=3.7.

It is recommended to install with `pipx`, if `pipx` haven't been installed yet, refer to the [pipx's docs](https://github.com/pipxproject/pipx)

```bash
$ pipx install monas
```

Alternatively, install with `pip` to the user site:

```bash
$ python -m pip install --user monas
```

## To-do

- [ ] Documentation
- [ ] Tests
- [ ] `setup.cfg` support
- [ ] (Possible) Poetry backend support

## License

MIT.
