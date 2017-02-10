### PyZ3950

This is a fork of the [PyZ3950] (https://github.com/asl2/PyZ3950) library with modifications.

See the original [README] (https://github.com/asl2/PyZ3950/blob/master/README.txt) for license information.

See https://github.com/asl2/PyZ3950/network for history.

- pip uninstall PyZ3950   # or if not supported manually remove older version dist-packages/PyZ3950
- python setup.py sdist   # will create dist/ folder
- pip install mypackage --no-index --no-cache-dir --find-links file:///home/.../dist/
