# binary-testing
Download and test PyPy nightly against popular libraries' test suites

The jobs run once-a-week via gihub actions

As can be seen in the [actions tab](https://github.com/pypy/binary-testing/actions) this currently runs

- Cython
- nanobind
- Numpy
- pybind11
- PyO3
- pytest-html (as an attempt to figure out why coverage is so slow)
- Pythran
