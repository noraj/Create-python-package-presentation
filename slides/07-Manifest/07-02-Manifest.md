## Specifying additional files with a Manifest (2/2)

The Manifest file is called `MANIFEST.in`, placed in the project's root directory. This is not a python script. It allows to include or exclude files and directories.

```
include README.md
recursive-include docs *.html *.css
```

It maintains the directory structure.

Manifest [format](http://docs.python.org/3.1/distutils/sourcedist.html#manifest) and [commands](http://docs.python.org/3.1/distutils/commandref.html#sdist-cmd).
