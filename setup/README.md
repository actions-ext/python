# setup
An action to setup and configure caching for Python.

## Usage

The following example yaml code will setup Python 3.11 environment with pip caching against `setup.py` and `pyproject.toml` files and `uv`.

```yaml
- name: Setup Python
  uses: actions-ext/python/setup@3327753a563b380e4efc5cb91a548301e68c2e64
  with:
    version: '3.11'
```
