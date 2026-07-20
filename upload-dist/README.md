# upload-dist
An action to upload a python `wheel` or `sdist`.

## Usage

The following example yaml code will upload `dist/*.tar.gz` as an asset called `sdist`.

```yaml
- name: Upload sdist
  uses: actions-ext/python/upload-dist@5f78fa2cadf4dad2a7cded3c72655bcdd3dda735
  with:
    kind: 'sdist'
```

The following example yaml code will upload `dist/*.whl` as an asset called `wheel`.

```yaml
- name: Upload wheel
  uses: actions-ext/python/upload-dist@5f78fa2cadf4dad2a7cded3c72655bcdd3dda735
  with:
    kind: 'wheel'
```
