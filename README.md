# pycache-wipe

![pycache-wipe Logo](https://pypi.org/static/images/logo-small.8998e9d1.svg)

---

**Simple, safe, and fast .pyc / __pycache__ folder cleaner.**

`pycache-wipe` is a lightweight Python utility that recursively finds and safely deletes `__pycache__` directories and `.pyc`/`.pyo` files from a project. It's designed for developers who want an easy way to clean up their repositories without accidentally deleting important source files.

---

## Features

- Recursively deletes `__pycache__` folders.
- Removes `.pyc` and `.pyo` files.
- Safe deletion with dry-run option.
- Works on Linux, MacOS, and Windows.
- Tiny, fast, and dependency-free.

---

## Installation

Install from PyPI:

```bash
pip install pycache-wipe
```

---

## Usage

Clean current directory recursively:

```bash
pycache-wipe
```

Clean a specific folder:

```bash
pycache-wipe /path/to/your/project
```

Run in dry-run mode (preview what would be deleted):

```bash
pycache-wipe --dry-run
```

Force confirmation off:

```bash
pycache-wipe --yes
```

Show help menu:

```bash
pycache-wipe --help
```

---

## Why Use pycache-wipe?

- Keep your repositories clean.
- Remove unnecessary build artifacts.
- Save disk space.
- Simplify preparing a project for version control or distribution.

---

## License

MIT License. See `LICENSE` file for details.

---

## Contributing

Pull requests are welcome! If you find a bug or have a feature request, feel free to open an issue.

---

## Author

Maintained by [DatadudeDev](https://github.com/datadudedev).

---

## Project Links

- [PyPI](https://pypi.org/project/pycache-wipe/)
- [Source Code](https://github.com/yourusername/pycache-wipe)

