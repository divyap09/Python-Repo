## List[]: 
- collection of items in a particular order

1. ordered
2. indexed
3. mutable i.e changeable
4. allows duplicates
5. can be of any data type.

### Methods:

.index(item) : returns the position of item, if not found, returns valueError

.append(item) : adds elements at the end of the list

.insert(index, item) : inserts item at given index

.pop() : removes elements from a specified position, if not declared removes last element.

.remove(item) : removes item present in the list, if not ValueError, if multiple items are present the first instance is removed.

.sort(reverse=True/False) : sorts items accordingly. We can't sort if the list has combination of numbers and strings. Sorts in ASCIIbetical order (upper followed by lower). To treat them all same without upper & lower use .sort(key=str.lower). It is permanentaly sorted.

sorted(list): it is sorted temporarily while retainig the original order

.clear() : removes all elements from the list

.copy() : copies one list to another

.reverse(): returns the list in reverse order

String is immutable, so we can't change the values. If we want to change then do slicing and add it to a new variable.


## Tuple()

1. ordered
2. indexed
3. immutable
4. allows duplicates

They can't be appended, modified or removed.
But the entire list can be overwritten or deleted using

```
del <tuple name>
```

Should put a comma after a single value else it will think a regular data is put in regular parenthesis.

### Methods:

.count() : no. of times a specified value occurred

.index() : first index of specified value


## set{}

1. unordered
2. unindexed
3. no duplicates

### Methods:

.add() : to add new elements in set

.update() : to update multiple elements in the set

.remove() : to remove elements from set, if not raises error

.discard() : it removes & doesn't raise error

.pop() : removes last element

.clear() : empties set

.del() : delete set

.union() : update can also be used

.intersection() : the common elements

.intersection_update() :

.symmentric_difference()

.difference() :

.difference_update() :

.isdisjoint() :

.issubset() :

.issuperset() :

.copy() : copies one set to another

.discard() : removes element from set

.update() :

<hline>
  
## Dictionary{:}

1. unordered
2. indexed
3. mutable
4. no duplicates

- indexed with key-pair values
- hashmaps

### Methods:

.update({key:value,..}) : inserts new elements

.keys() : shows list of keys

.values() : shows list of values

.get(key, [print something]) : gets the value from key, if key is not found 2nd argument gets printed. If you doesn't provide the 2nd argument, it shows None when key is not found.

.items() : gets both key & value

.pop() : removes wrt key

.popitem() : removes last inserted item

.clear() : empties

.copy() : copies elements
