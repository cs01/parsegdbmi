# pygdbmi release history

## 0.7.4.2
* Improved buffering of incomplete gdb mi output (@trapito)
* Remove support of Python 3.2

## 0.7.4.1
* Preserve leading and trailing spaces in gdb/mi output (plus unit tests)
* Add unit test for buffering of gdb/mi output
* Documentation updates
* Refactoring

## 0.7.4.0
* Add more exception types (`NoGdbProcessError`, `GdbTimeoutError`)
* Add logic fixes for Windows (@johncf)
* Use codecs.open() to open the readme.rst, to prevent locale related bugs (@mariusmue)

## 0.7.3.3
* Add alternate pipe implementation for Windows

## 0.7.3.2
* Replace `epoll` with `select` for osx compatibility (@felipesere)

## 0.7.3.1
* Fix README

## 0.7.3.0
* Add support for gdb/mi (optional) tokens (@mariusmue)
