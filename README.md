# Insert filter plugin for Embulk

TODO: Write short description here and embulk-filter-insert.gemspec file.

## Overview

* **Plugin type**: filter

## Configuration

- **property1**: description (string, required)
- **property2**: description (integer, default: default-value)

## Example

```yaml
filters:
  - type: insert
    property1: example1
    property2: example2
```


## Build

```
$ rake
```