# Changelog

All notable changes to this project will be documented in this file.

## Unreleased

### Changed

- Formatted the Python source with Black.
- Normalized import ordering with isort.
- Corrected PEP 8 whitespace, indentation, quoting, and `None` comparison style.
- Preserved the existing public camelCase APIs to avoid breaking current callers.

### Validation

- Python bytecode compilation, formatter, import-order, pycodestyle, whitespace,
  and focused utility smoke checks pass.
- **Not fully tested:** the application has not undergone end-to-end or live Podimo
  API testing. The local Python 3.8 environment could not build the pinned
  `aiohttp` dependency required for a full application import test.
