# setup
An action to setup and configure caching for Python.

## Usage

The following example yaml code will setup Python 3.11 environment with pip caching against `setup.py` and `pyproject.toml` files and `uv`.

```yaml
- name: Setup Python
  uses: actions-ext/python/setup@v1
  with:
    version: '3.11'
```
