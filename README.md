# ci_python_example
Continuous Integration example for Python

[![Build Status](https://travis-ci.org/abhishekanand/ci_python_example.svg?branch=master)](https://travis-ci.org/abhishekanand/ci_python_example)

[![Coverage Status](https://coveralls.io/repos/github/abhishekanand/ci_python_example/badge.svg?branch=master)](https://coveralls.io/github/abhishekanand/ci_python_example?branch=master)


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

* Install  Coverage 
```
conda install coverage
coverage run -m unitest discover
```

* Minimum enviroment to run Unit test 
- Create a fresh environment 
- Source activate enve 
- Wverify which Pip 
- pip install pandas 
- freeze  (Create requirment.txt) 
    pip freeze  > requirmnts.txt 

* Now add requirment.txt to git 

* Create .travis.yml
