# AI Test Generator

![CI](https://github.com/Qyroxen/AI-Test-Generator/actions/workflows/ci.yml/badge.svg) ![Go](https://img.shields.io/badge/Go-1.23+-00ADD8?style=flat&logo=go) ![License](https://img.shields.io/badge/License-MIT-yellow.svg) ![Stars](https://img.shields.io/github/stars/Qyroxen/AI-Test-Generator?style=social)

> Auto-generate tests for your code using AI

[![Star Badge](https://img.shields.io/github/stars/Qyroxen/AI-Test-Generator?style=social)](https://github.com/Qyroxen/AI-Test-Generator/stargazers)

## What is it?

AI Test Generator analyzes your code and generates comprehensive unit tests, integration tests, and test cases.

## Why should you care?

Writing tests is time-consuming but essential. Let AI do the heavy lifting.

## Demo

```bash
./ai-test-gen generate --path ./my-project
```

**Output:**
```
Generated tests:
  - 25 unit tests
  - 8 integration tests
  - 100% function coverage
```

## Features

- Auto-generate unit tests
- Integration test generation
- Edge case detection
- Mock generation
- Coverage reporting

## Quick Start

```bash
# Install
git clone https://github.com/Qyroxen/AI-Test-Generator.git
cd AI-Test-Generator
go build -o ai-test-gen .

# Run
./ai-test-gen --path ./my-project
```

## CLI Flags

| Flag | Description | Default |
|------|-------------|---------|
| `--path` | Source code directory | `.` |
| `--type` | Test type (unit, integration, all) | `all` |
| `--coverage` | Target coverage percentage | `80` |
| `--mock` | Generate mocks | `true` |

## Examples

# Generate all tests
./ai-test-gen generate --path ./src

# Unit tests only
./ai-test-gen generate --path ./src --type unit

# Target 90% coverage
./ai-test-gen generate --path ./src --coverage 90

## Contributing

Contributions are welcome! Please see [CONTRIBUTING.md](CONTRIBUTING.md) for details.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

---

<p align="center">
  <a href="https://github.com/Qyroxen/AI-Test-Generator/stargazers">
    <img src="https://img.shields.io/github/stars/Qyroxen/AI-Test-Generator?style=social" alt="Star this repo">
  </a>
  <a href="https://github.com/Qyroxen/AI-Test-Generator/network/members">
    <img src="https://img.shields.io/github/forks/Qyroxen/AI-Test-Generator?style=social" alt="Fork this repo">
  </a>
  <a href="https://github.com/Qyroxen/AI-Test-Generator/issues">
    <img src="https://img.shields.io/github/issues/Qyroxen/AI-Test-Generator" alt="Issues">
  </a>
</p>
