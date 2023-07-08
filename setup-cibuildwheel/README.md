# setup-cibuildwheel
An action to install and configure caching for [`cibuildwheel`](https://cibuildwheel.readthedocs.io/en/stable/) 

## Usage

The following example yaml code will install cibuildwheel and configure caching.

```yaml
- name: Setup cibuildwheel
  uses: actions-ext/python/setup-cibuildwheel@v1
  with:
    version: '3.9'
```
