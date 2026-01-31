# fast-scaffold 🚀

CLI to generate **FastAPI project scaffolding** in a fast, standardized, and extensible way.

`fast-scaffold` creates the initial structure of a FastAPI project using Mako templates, allowing for easy evolution into multiple types of scaffolds in the future.

---

## ✨ Features

- 📦 Simple and fast CLI
- ⚡ Generate FastAPI projects in seconds
- 🧱 Template-based structure (Mako)
- 🧩 Easy to extend for new scaffolds
- 🐍 Compatible with Python 3.10+

---

## 📦 Installation

### Using pipx (recommended for CLIs)

```bash
pipx install fast-scaffold
```

Or using pip:

```bash
pip install fast-scaffold
```

## 🚀 Quick Start

Create a new FastAPI project:

```bash
fast-scaffold project init my-api
```

This will generate the project structure in the current directory:

```text
my-api/
├── pyproject.toml
├── README.md
└── app/
    └── main.py
```

## 🧠 How it works

fast-scaffold utilizes Mako templates located within the package:

```text
fast_scaffold/
└── templates/
    └── project/
        ├── pyproject.toml.mako
        ├── README.md.mako
        └── app/
            └── main.py.mako
```

## 🛠️ Local Development

Clone the repository and install the dependencies:

```bash
poetry install
```

Run the CLI locally:

```bash
poetry run fast-scaffold project init my-api
```

## 📄 Requirements

* Python >= 3.10
* Poetry (for development)
* pipx (recommended for global use)


## 🤝 Contributing

Contributions are welcome! Feel free to open issues or submit pull requests.

##📜 License

MIT License
