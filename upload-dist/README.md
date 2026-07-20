# upload-dist
An action to upload a python `wheel` or `sdist`.

## Usage

The following example yaml code will upload `dist/*.tar.gz` as an asset called `sdist`.

```yaml
- name: Upload sdist
  uses: actions-ext/python/upload-dist@14e52561e5f255ba52d2e04d3cc2f3dedb1065af
  with:
    kind: 'sdist'
```

The following example yaml code will upload `dist/*.whl` as an asset called `wheel`.

```yaml
- name: Upload wheel
  uses: actions-ext/python/upload-dist@14e52561e5f255ba52d2e04d3cc2f3dedb1065af
  with:
    kind: 'wheel'
```
