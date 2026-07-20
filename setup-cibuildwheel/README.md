# setup-cibuildwheel
An action to install and configure caching for [`cibuildwheel`](https://cibuildwheel.readthedocs.io/en/stable/)

## Usage

The following example yaml code will install cibuildwheel and configure caching.

```yaml
- name: Setup cibuildwheel
  uses: actions-ext/python/setup-cibuildwheel@3327753a563b380e4efc5cb91a548301e68c2e64
  with:
    version: '3.11'
```
