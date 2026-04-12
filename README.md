# python

Helper actions for Python projects

| Name                                                   | Action Reference                              | Description                                                                        |
| :----------------------------------------------------- | :-------------------------------------------- | :--------------------------------------------------------------------------------- |
| [setup](./setup)                                       | `actions-ext/python/setup`                    | Setup Python with `pip` caching and `uv`                                           |
| [setup-cibuildwheel](./setup-cibuildwheel)             | `actions-ext/python/setup-cibuildwheel`       | Setup [`cibuildwheel`](https://cibuildwheel.readthedocs.io/en/stable/) and caching |
| [setup-cibuildwheel-cache](./setup-cibuildwheel-cache) | `actions-ext/python/setup-cibuildwheel-cache` | Setup [`cibuildwheel`](https://cibuildwheel.readthedocs.io/en/stable/) caching     |
| [run-cibuildwheel](./run-cibuildwheel)                 | `actions-ext/python/run-cibuildwheel`         | Run [`cibuildwheel`](https://cibuildwheel.readthedocs.io/en/stable/)               |
| [upload-dist](./upload-dist)                           | `actions-ext/python/upload-dist`              | Upload a python sdist or wheel                                                     |
| [download-dist](./download-dist)                       | `actions-ext/python/download-dist`            | Download and install a python sdist or wheel                                       |
| [test-wheel](./test-wheel)                             | `actions-ext/python/test-wheel`               | Install a wheel in a fresh venv and verify module import                           |
| [test-sdist](./test-sdist)                             | `actions-ext/python/test-sdist`               | Install an sdist in a fresh venv and verify module import                          |
