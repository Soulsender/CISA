## Dictionaries
##### Accessing and changing dictionaries
```python
dict[key] # index value of key
dict[key] = value # adds entry or modifies if it already exists
del dict[key] # deletes key
key in dict # tests to see if key exists
```
##### Dictionary Syntax
> first field is `key`, second is `value`
```python
dict = {
		'John': '1',
		'Alan': 67,
		30: 5.0
}
```
##### Dictionary Methods
- `.keys()` - returns all keys in dictionary
- `.values()` - returns all values in dictionary
- `.items()` - returns all key/value pairs in individual tuples in one tuple
- `get(key, default)` - returns value for key, or default if no key is present
- `.pop(key)` - removes and returns value for specified key
- `.update(other_dict)` - updates dict with key/value pairs from another dict

##