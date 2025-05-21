# string-list

**Tiny but powerful string <-> list manipulation utilities for Python.**

This package provides smart, minimal utilities to convert strings to lists, lists to strings, or coerce arbitrary values (like `"1,2,3"` or `123`) into clean, typed lists.

### ✨ Features

- Cleanly split strings to lists with optional stripping
- Convert lists/sets into delimited or quoted strings
- Handle mixed input types robustly (`str`, `int`, `list`)
- Case-insensitive set merging with title-case preference
- Enumerate inputs into string-keyed dictionaries

### 🔧 Example

```python
from string_list import list_from_string, string_from_list

list_from_string("a, b, c")                # ['a', 'b', 'c']
string_from_list(['x', 'y'], quoted=True)  # "'x','y'"
```

MIT Licensed.


---
