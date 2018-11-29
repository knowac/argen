# argen

Author rights generator

## Description

Script for generation of author rights reports. The generated reports will be placed inside ar_reports/ directory.

## Options

List of possible actions can be displayed with:

```
./argen --help
```

## Defaults

By default report will be generated for user name from global .gitconfig file and for the current month.

### Usage example

```
./argen --author "AUTHOR" --since "2018-01-01" --depth 3
```

## License

MIT
