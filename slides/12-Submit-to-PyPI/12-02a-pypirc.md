## Create a `.pypirc` configuration file (1/2)

To make life easier when uploading packages, create a `~/.pypirc` file:

```ini
[distutils]
index-servers =
  pypi
  pypitest

[pypi]
repository=https://pypi.python.org/pypi
username=your_username
password=your_password

[pypitest]
repository=https://testpypi.python.org/pypi
username=your_username
password=your_password
```
