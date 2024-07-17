[![Donate](https://img.shields.io/badge/-%E2%99%A5%20Donate-%23ff69b4)](https://hmlendea.go.ro/fund.html) [![Latest GitHub release](https://img.shields.io/github/v/release/hmlendea/polyglot-language-validate)](https://github.com/hmlendea/polyglot-language-validate/releases/latest)

# About

Validates a PolyGlot language.

# Usage

```yaml

- name: Validate
  uses: hmlendea/polyglot-language-validate@latest
  with:
    polyglot_dictionary_file_path: "/path/to/PGDictionary.xml" # From an unpacked language
    words_file_path: "/path/to/words.json"
    sentences_file_path: "/path/to/sentences.json"
```
