Getting keys
========================================
The `keys` function returns an array with the keys present in the input object.
For example Getting the keys of a simple object looks like:

    $ echo '{"a": 57, "b": "banana", "c": {}}' \
      | jq 'keys'
