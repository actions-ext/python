# download-python-dist
An action to download and install a python `wheel` or `sdist`.

## Usage

The following example yaml code will download and install a `cp311` wheel for `manylinux-x86_64` on `Linux` runners, `amd64` on `Windows` runners, and `x86_64` on `Macos` runners, in place on top of the current repo.

```yaml
- name: Download wheels
  uses: actions-ext/python/download-dist@v1
  with:
    version: '3.11'
    kind: 'wheel'
    install_path: '.'
```

**NOTE**: This is configured around the default GitHub Actions runners, which do not support e.g. arm.
