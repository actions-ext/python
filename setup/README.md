# setup
An action to setup and configure caching for Python.

## Usage

The following example yaml code will setup Python 3.9 environment with pip caching against `setup.py` and `pyproject.toml` files.

```yaml
- name: Setup Python
  uses: actions-ext/python/setup@v1
  with:
    version: '3.9'
```
