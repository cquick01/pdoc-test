1. Create virtualenv

```
python -m venv venv
```

2. Activate virtualenv

```
source ./venv/bin/activate
```

3. Install pdoc and GitPython

```
pip install pdoc GitPython
```

4. Install package

```
pip install -e .
```

5. See error when running pdoc against test_package

```
python -m pdoc test_package
```

6. No error when running pdoc directly against module outside of package

```
python -m pdoc ./test.py
```
