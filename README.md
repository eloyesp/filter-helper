# Filter Helper

Make a filter in JavaScript without much noise.

This is a simple module done for learning so I would thank any feedback.

## Usage

It should help making very simple filters in JavaScript just defining
a function:

```
#!/usr/bin/env node

var fh = require('filter-helper');

// this script will prepend something to every line

fh(function (line) {
  return process.argv[2] + " " + line;
});
```
