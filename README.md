# CComp Tools

This is a script installer for OSX and Linux. It installs a command that can be used to compile C++ with G++ and tests it with CxxTest.

## Installation

Before installation you must have installed:
- G++ (often comes with Xcode for OSX)
- CXXTest

Run the installer with:
```
ruby install-tools.rb
```

## Usage

Unit test with a CxxText .h file:
```
ccomp test-file-name
```