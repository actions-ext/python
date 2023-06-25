# setup-cache
An action to setup caching for Python.

## Usage

The following example yaml code will setup pip caching against `setup.py` and `pyproject.toml` files.

```yaml
- name: Setup Python
  uses: actions-ext/python/setup-cache@v1
```
