# wp cache replace

Replace a value in the object cache, if the value already exists.

Errors if the value can't be replaced.

### OPTIONS

&lt;key&gt;
: Cache key.

&lt;value&gt;
: Value to replace.

[&lt;group&gt;]
: Method for grouping data within the cache which allows the same key to be used across groups.
\---
default: default
\---

[&lt;expiration&gt;]
: Define how long to keep the value, in seconds. `0` means as long as possible.
\---
default: 0
\---

### EXAMPLES

    # Replace cache.
    $ wp cache replace my_key new_value my_group
    Success: Replaced object 'my_key' in group 'my_group'.


