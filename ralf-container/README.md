# Ralf

A CLI tool to iterate on a developer design.

## Installation

```bash
poetry install
```

## Usage

```bash
poetry run ralf version
```


# Example of running the Ralf loop

```bash
ralf loop --config tests/test_data/config.yaml --secrets tests/test_data/secrets -d tests/test_output tests/instructions0.md
ralf loop --config tests/test_data/config.yaml --secrets tests/test_data/secrets -d tests/test_output tests/instructions1.md
```
