## Specifying additional files with a Manifest (1/2)

By default, Distutils will only include the following files in the release package:
- README.txt
- setup.py
- files listed in `packages` or `py_modules` parameters

So to include a `LICENCE` file, a `NOTICE` file, use a different file extension like a `README.md` or `docs/` documentation folder, a Manifest file will be needed.
