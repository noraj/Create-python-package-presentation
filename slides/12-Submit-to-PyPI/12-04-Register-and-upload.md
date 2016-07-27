## Register the project and upload the distribution

Register the package project:
```
python setup.py register -r pypi
```
Upload the package distribution:
```
python setup.py sdist upload -r pypi
```

To make sure the package is set up correctly, package can be upload on PyPI's test server first:
```
python setup.py register -r pypitest
python setup.py sdist upload -r pypitest
```
