## Creating a source distribution

The minimum is too build a source distribution containing the source code, the setup script, the README file and additional files that come with the MANIFEST.

```
python3 setup.py sdist
```

This will create a `dist/` folder in your project directory and a `package_name.tar.gz` archive inside it (or a `.zip` for Windows users).
