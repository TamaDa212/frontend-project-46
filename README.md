### Hexlet tests and linter status:
[![Actions Status](https://github.com/TamaDa212/frontend-project-46/actions/workflows/hexlet-check.yml/badge.svg)](https://github.com/TamaDa212/frontend-project-46/actions)

[![Actions Status](https://github.com/TamaDa212/frontend-project-46/actions/workflows/node-check.yml/badge.svg)](https://github.com/TamaDa212/frontend-project-46/actions)

[![Maintainability](https://api.codeclimate.com/v1/badges/c0078dcdf12489a7339c/maintainability)](https://codeclimate.com/github/TamaDa212/frontend-project-46/maintainability)

[![Test Coverage](https://api.codeclimate.com/v1/badges/c0078dcdf12489a7339c/test_coverage)](https://codeclimate.com/github/TamaDa212/frontend-project-46/test_coverage)

# Вычислитель отличий
Учебный проект. Сравнивает два файла в формате **json** или **yaml** и выводит разницу между ними в различных форматах.
``` bash
$ gendiff -h
Usage: gendiff [options] <filepath1> <filepath2>

Compares two configuration files and shows a difference.

Options:
  -V, --version        output the version number
  -f, --format [type]  output format (choices: "stylish", "plain", "json")
  -h, --help           display help for command
```