## Setup.cfg

`setup.cfg` is a powerful tool that can [do a lot](https://docs.python.org/3/distutils/configfile.html)  but here we only need it because we're using a markdown readme file. Because Distutils only check for `README` and `README.txt`.

```
[metadata]
description-file = README.md
```
