# PBJ

Pure Bash JSON Formatter

# Why

- No dependencies required besides GNU/Bash
- Avoids the overhead of calling an external tool e.g. Python with import json
- I wanted to call something "PBJ"

# How To

Add this repository to your `$PATH`, or copy `pbj` to an existing scripts directory in your `$PATH`

```
$ pbj foo.json
```

```
$ echo '{"foo": [0, 1, 2]}' | pbj
{
  "foo": [
    0,
    1,
    2
  ]
}
```
