# Project Euler Solutions

Welcome to my solutions repository for [Project Euler](https://projecteuler.net/), a collection of challenging mathematical and programming problems. This repository includes my solutions to the problems in various languages and is organized for easy navigation.

## Table of Contents
- [About Project Euler](#about-project-euler)
- [Structure of This Repository](#structure-of-this-repository)
- [Getting Started](#getting-started)
- [How to Run Solutions](#how-to-run-solutions)
- [License](#license)

---

## About Project Euler

Project Euler is a series of complex mathematical problems intended for computer-based solutions. These problems are excellent for anyone interested in algorithmic problem-solving, mathematical reasoning, and programming.

## Structure of This Repository

```plaintext
project-euler-solutions/
├── docs/                     # Documentation files
│   ├── en/                   # English version
│   │   ├── mkdocs.yml        # MkDocs config for English docs
│   │   └── ...               # Other docs
│   └── es/                   # Spanish version
│   |   ├── mkdocs.yml        # MkDocs config for Spanish docs
│   |   └── ...               # Other docs
|   └── ...                   # Additional language folders, if any
├── docs_src/                 # Code solutions
│   ├── 001.py                # Solution for Problem 1
│   ├── 002.py                # Solution for Problem 2
│   └── ...                   # Other solutions
└── README.md                 # Project overview (this file)
```

Each problem markdown file typically includes:
- **Problem Statement**: The problem as presented on Project Euler.
- **Solution Approach**: A high-level explanation of the algorithm.
- **Code**: A link or embedded code snippet for the solution.

## Getting Started

1. **Clone the repository**:
   ```bash
   git clone https://github.com/your-username/project-euler-solutions.git
   cd project-euler-solutions
   ```

2. **Install dependencies**:
   If any Python dependencies are needed, they are listed in `pyproject.toml`. Install them with:
   ```bash
   pip install -r requirements.txt
   ```

## How to Run Solutions

Each solution is written in Python. You can run a specific solution by executing the corresponding file in the `src` directory:

```bash
python docs_src/001.py
```

## Documentation

Documentation for each problem is available in both English and Spanish using MkDocs. To serve the documentation locally:

1. Install MkDocs and the theme (if not already installed):
   ```bash
   pip install mkdocs mkdocs-material
   ```

2. Run the MkDocs server for the desired language:
   ```bash
   mkdocs serve --config-file docs/en/mkdocs.yml  # for English
   mkdocs serve --config-file docs/es/mkdocs.yml  # for Spanish
   ```

The documentation will be available at `http://127.0.0.1:8000`.

## License

This repository is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.
