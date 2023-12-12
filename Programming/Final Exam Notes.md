## Order of Operations
> from top down where top is done first
1. exponents
2. dividing, multiplying, modulo
3. addition, subtraction
4. relational (`==, >=, <=, >`)
5. `not`
6. `and`
7. `or`
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

## Loops
```python
# starts at 0
# goes to 1
# executed twice
for i in range(0, 2):
    print(i)
    for a in range_char('a', 'b'):
        print(a)
```
will output
```
0
	a
	b
1
	a
	b
```
