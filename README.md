[![Donate](https://img.shields.io/badge/-%E2%99%A5%20Donate-%23ff69b4)](https://hmlendea.go.ro/funding)
[![Latest Release](https://img.shields.io/github/v/release/hmlendea/polyglot-language-validate)](https://github.com/hmlendea/polyglot-language-validate/releases/latest)
[![License: GPL v3](https://img.shields.io/badge/License-GPLv3-blue.svg)](https://gnu.org/licenses/gpl-3.0)

# PolyGlot Language Validate

A composite GitHub Action that validates PolyGlot language assets by checking dictionary, word list, and sentence files for consistency.

## 📑 Table of Contents

- [Capabilities](#-capabilities)
- [Usage](#-usage)
- [Known Limitations](#-known-limitations)
- [Installation](#-installation)
- [Development](#-development)
  - [Requirements](#requirements)
  - [Setup](#setup)
- [Contributing](#-contributing)
- [Supporting the Project](#-supporting-the-project)
- [License](#-license)

## ✨ Capabilities

- Validates a PolyGlot dictionary XML file with corresponding words and sentences JSON files.
- Executes validation in GitHub Actions using .NET 8 via a reusable composite action interface.

## 🚀 Usage

```yaml
- name: Validate language assets
  uses: hmlendea/polyglot-language-validate@v1.0.0
  with:
    polyglot_dictionary_file_path: /path/to/PGDictionary.xml
    words_file_path: /path/to/words.json
    sentences_file_path: /path/to/sentences.json
```

## ⚠️ Known Limitations

- Input paths must point to files present in the workflow runner workspace.
- The action currently references validator tag `v1.0.0` from `hmlendea/polyglot-language-validator`.

## 📦 Installation

[![Obtain it from GitHub](https://raw.githubusercontent.com/hmlendea/readme-assets/master/badges/stores/github.png)](https://github.com/hmlendea/polyglot-language-validate/releases)

No local installation is necessary. Reference the action in your workflow file and provide the required input paths.

## 🛠️ Development

### Requirements

- GitHub Actions workflow context (or a compatible local runner) to execute the composite action.

### Setup

Clone the repository and revise `action.yaml` as required.

## 🤝 Contributing

You are welcome to submit any suggestion, feedback, or modification to this project.

When doing so, please:
- Maintain cross-platform compatibility
- Maintain the pull requests as focused and consistent with the existing code style
- Maintain your branch up-to-date with `master`
- Properly test all changes

## 💝 Supporting the Project

Discovered a problem or have a suggestion? [Open an issue](https://github.com/hmlendea/polyglot-language-validate/issues)!

If you find this project useful, consider [funding it](https://hmlendea.go.ro/funding) or starring ⭐️ it on GitHub!

[![Donate](https://raw.githubusercontent.com/hmlendea/readme-assets/master/donate_generic.png)](https://hmlendea.go.ro/funding)

## 📄 License

This project is being distributed under the `GNU General Public License v3.0` or later.
See [LICENSE](./LICENSE) for further information.
