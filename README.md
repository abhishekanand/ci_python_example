# ci_python_example
Continuous Integration example for Python
```
.
├── LICENSE
├── README.md
└── codebase
    ├── __init__.py
    ├── codebase.py
    ├── data
    │   └── test.csv
    ├── tests
    │   ├── __init__.py
    │   └── test_codebase.py
    └── version.py
```

Install  Coverage 
```
conda install coverage
coverage run -m unitest discover
```