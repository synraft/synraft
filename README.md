# synraft
PowerShell:
```
cd pypi
py -m pip install --upgrade build twine
py -m build
py -m twine check dist/*
py -m twine upload dist/*
```
