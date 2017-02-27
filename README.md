#Python Cheatsheet

###List

A **list** is the most versatile data type in Python. A list can hold *different types of data* and is written using brackets []. Lists are perfect for when you need an ordered *list* of items and can be changed (mutable) after they are created.

list = []  
list = ["words", "are", "strings"]  
list = [1, 2, 3]  
list = ["string", 2]  
lovely_list = list()

To read the items in a list, you can either specify the index or iterate over the entire list. 

list = ["all", "is", "well", "that", "ends", "well"]

```>>list[2]
"well"```

```for item in list: print(item)
all is well that ends well``


###Dictionary

A **dictionary** holds *key and value pairs* and is written using braces {}. The value of a key can also be a string, number, or list []. Dictionaries are perfect for when you just need to remember keys and can be changed (mutable) after they are created.

dictionary = {}  
dictionary = {'key': 'value'}  
dictionary = {'key': 1}  
dictionary = {'name': 'abby', 'school': 'NSS', 'languages': ['javascript', 'angular', 'python', 'django']}  
lovely_dictionary = dict()  

To read the items in a list, you just need to remember the key. 

```>>> print(dictionary['school'])
NSS```


###Set 

A **set** is similar to a list, but each item must be unique and cannot repeat. Sets are unordered and can be changed (mutable) after they are created.  

lovely_set = [1, 1, 2, 2, 2, 2, 2, 3, 3]  
```>> set(lovely_set) 
{1, 2, 3}```


###Tuple

A **tuple** is also similar to a list in that it can hold different types of data. However, a tuple is immutable (cannot change) after it is created and uses parenthesis instead. A tuple containing a single item requires a trailing comma.

lovely_tuple = tuple()  
lovely_tuple = ('Abby', 'NSS', 'Nashville')  
another_tuple = ('Abby',)  

```>>> print(lovely_tuple)
('Abby', 'NSS', 'Nashville')```


####Resources
[https://tutorial.djangogirls.org/en/python_introduction/]
[https://github.com/nashville-software-school/bangazon-llc/blob/master/orientation/FND_03_TYPES.md]
[http://stackoverflow.com/questions/15181867/understanding-the-set-function]
[https://www.tutorialspoint.com/python/python_tuples.htm]

