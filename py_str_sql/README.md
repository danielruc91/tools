# Highlighting SQL in Python Strings

Adds syntax highlight support for python multiline SQL strings in VS Code. This is inspired by https://github.com/ptweir/python-string-sql

To tailor to my personal usage:

1. Remove support for html
2. No need for `--sql` kind of key word. Treate all python string as SQL

## Usage

### Package

You need to have vsce installed.

```shell
cd py_str_sql
vsce package
```

### Install

```shell
code --install-extension <vsix file generated above>
```
