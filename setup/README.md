# setup
An action to setup and configure caching for Python.

## Usage

The following example yaml code will setup Python 3.11 environment with pip caching against `setup.py` and `pyproject.toml` files and `uv`.

```yaml
- name: Setup Python
  uses: actions-ext/python/setup@14e52561e5f255ba52d2e04d3cc2f3dedb1065af
  with:
    version: '3.11'
```
