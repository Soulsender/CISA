> **element** - any python data type; string, int, float, list, bool, etc.
> **iterable** - list, tuple, set, etc.
#### Strings
- `.upper()` - converts string to uppercase
- `.lower()` - converts string to lowercase
- `.strip()` - removes leading and trailing whitespace
- `.replace(old, new)` - replaces substring with substring
- `.split(seperator)` - splits string into ***list*** of substrings
- `.join(iterable)` - joins elements of iterable (list, set, etc.)
#### Lists
- `.append(element)` - appends element to end of list
- `.extend(element)` - extends list by appending elements from iterable
- `.pop(index)` - removes and returns element at index
- `.remove(element)` - removes element specified (can be string, int, etc.)
- `.index(element)` - returns index of element (if element is string; index of the first char in string)
- `.count(element)` - number of occurrences of element
- `.sort(reverse=True)` - sorts elements in ascending order (will change values of object it is being used on; can be reversed)
- `.reverse(element)` - reverses order of elements
#### Dictionary
- `.keys()` - returns all keys in dictionary
- `.values()` - returns all values in dictionary
- `.items()` - returns all key/value pairs in individual tuples in one tuple
- `get(key, default)` - returns value for key, or default if no key is present
- `.pop(key)` - removes and returns value for specified key
- `.update(other_dict)` - updates dict with key/value pairs from another dict