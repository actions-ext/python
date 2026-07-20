# setup-cibuildwheel
An action to install and configure caching for [`cibuildwheel`](https://cibuildwheel.readthedocs.io/en/stable/)

## Usage

The following example yaml code will install cibuildwheel and configure caching.

```yaml
- name: Setup cibuildwheel
  uses: actions-ext/python/setup-cibuildwheel@14e52561e5f255ba52d2e04d3cc2f3dedb1065af
  with:
    version: '3.11'
```
