# 🌟 Awesome Marimo

A curated list of awesome resources, use cases, and setup guides for Marimo - a reactive Python notebook for computational thinking.

Marimo has the potential to bridge the instructional gap by reducing friction in programming and replacing it with an interactive, pure Python environment.

## 🚀 Why Marimo?

Marimo solves common frustrations in teaching and learning Python:

* Move beyond traditional console inputs to interactive UI elements.
* Pure Python: Notebooks are saved as standard `.py` files, allowing you to bring your own harness.
* Reactive & Deterministic: Variables are owned by cells. Cell order is irrelevant, ensuring deterministic execution and reproducible results.
* Publish Anywhere: Easily publish your notebooks to the web using WASM. Self-host static web pages anywhere or create a GitHub Actions workflow for automatic deployment and updates.

## ⚙️ Getting Started (Running Locally)

Running Marimo locally gives you access to native runtimes, system memory, hardware, network access, and real GenAI integrations.

1. Install `uv` - [a wonderful Python package manager](uv.md)

```sh
winget install astral-sh.uv # on Windows
dnf install uv # on Fedora Linux
brew install uv # on MacOS or Linux with Homebrew
```

2. Launch Marimo

You can start editing a new notebook immediately without permanently installing marimo globally:

```sh
uvx marimo edit new.py
```

Alternatively, install marimo globally using `uv tool install marimo`

## 💡 Key Features & Concepts

* Dataflow Execution: Marimo understands the dependencies between your cells and variables automatically. If `c = a * b` and you change `a`, `c` updates reactively.
* Private Variables: Keep your workspace clean by prefixing variables with an underscore (e.g., `_a = 5`).
* Interactive UI: Built-in sliders, buttons, and forms without complex web frameworks.

## 🛠️ Helpful Prompts in Educational Setting

> Help me to decompose ______________ in Python by illustrating the process step-by-step

> ELI5 - after each cell, add a quick summary of the Python concepts

> Teach me about Python variables and functions

## 📚 Resources & Tutorials

Official Tutorials:
* [Introduction](https://links.marimo.app/tutorial-intro)
* [Dataflow](https://links.marimo.app/tutorial-dataflow)
* [UI Elements](https://links.marimo.app/tutorial-ui)
* [Charts](https://links.marimo.app/tutorial-plotting)
* [SQL](https://links.marimo.app/tutorial-sql)
* [Layouts](https://links.marimo.app/tutorial-layout)

Reference:
* 🔗 [Marimo Official Website & Gallery](https://marimo.io/)
* 🔗 [Awesome Marimo](https://github.com/marimo-team/awesome-marimo)
