# run-cibuildwheel
An action to download and run [`cibuildwheel`](https://cibuildwheel.readthedocs.io/en/stable/).

## Usage

The following example yaml code will build a `cp37` wheel for `manylinux-x86_64` on `Linux` runners, `amd64` on `Windows` runners, and `x86_64` and `arm64` on `Macos` runners.

```yaml
- name: Run cibuildwheel
  uses: actions-ext/python/run-cibuildwheel@v1
  with:
    version: '3.7'
    kind: 'cp'
```

**NOTE**: This is configured around the default GitHub Actions runners which support cross compilation, but `musllinux` and `win32` builds are disabled to conserve CI resources.
