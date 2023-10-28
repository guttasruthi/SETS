SETS:


```python
* sets is nothing but group of elements.
* defined with {}
* no index and no order.

```

Set Methods:

add()
remove()
update()
pop()

define a set:
    


```python
a={1, 345, 244}
print(type(a))
```

    <class 'set'>
    


```python
a={1, 23, 56, 589,23,1,5,9}
print(a)
```

    {1, 5, 23, 56, 9, 589}
    

add():
The set add() method adds a given element 


```python
a.add(123)
print(a)
```

    {1, 5, 23, 56, 9, 123, 589}
    

update():
    the set update() method updates the elements in the set.


```python
a.update({7,56,88,99})
print(a)
```

    {1, 99, 5, 7, 88, 9, 589, 23, 56, 123}
    


```python
remove():
    the set remove() method removes the  elements in the set.
```


```python
a
```




    {1, 5, 7, 9, 23, 56, 88, 99, 123, 589}




```python
a.remove(9)
print(a)
```

    {1, 99, 5, 7, 88, 589, 23, 56, 123}
    

pop():
the set pop() method removes the random element in the set



```python
a
```




    {1, 5, 7, 23, 56, 88, 99, 123, 589}




```python
a.pop()
print(a)
```

    {99, 5, 7, 88, 589, 23, 56, 123}
    

Set operations:

union
intersection
difference
issubset
issuperset

union:
union () method returns a set that contains all items from the original set

![PythonSetOpUnion.png](attachment:PythonSetOpUnion.png)


```python
set1={1,2,3,4}
set2={5,6,7,8}
print(set1.union(set2))
```

    {1, 2, 3, 4, 5, 6, 7, 8}
    


```python
intersection:
     The intersection () method returns a set that contains the similarity between two 
```

![PythonSetOpIntersection.png](attachment:PythonSetOpIntersection.png)


```python
set1={1,2,3,4}
set2={4,5,6,7,8}
print(set1.intersection(set2))
```

    {4}
    

difference:
The difference() method returns a set that contains the difference between two sets

![PythonSetOpDifference.png](attachment:PythonSetOpDifference.png)


```python
set1={1,2,3,4}
set2={4,5,6,7,8}
print(set1.difference(set2))
```

    {1, 2, 3}
    

issuperset:.
         issuperset () method returns True if all elements of a set 2 are in set 1          
       
    

![superset.png](attachment:superset.png)


```python
set1={1,2,3,4}
set2={1,2,3}
print(set1.issuperset(set2))
```

    True
    


```python
issubset:
    issubset() method returns True if all elements of a set A are present in another set B
```

![OIP.jpg](attachment:OIP.jpg)


```python
set1={1,2,3,4}
set2={1,2,3}
print(set2.issubset(set1))
```

    True
    


```python
set1={1,2,3,4}
set2={1,2,3}
print(set1.issubset(set2))
```

    False
    


```python
Intersection_update:
    The intersection_update() method update exsiting set by keeping on;y common elements from both sets.
```

![OIP%20%281%29.jpg](attachment:OIP%20%281%29.jpg)


```python
a={'blue', 'red', 'green'}
b={'orange', 'red', 'yellow'}
a.intersection_update(b)
print(a)
```

    {'red'}
    


```python
 symmetric_difference():
        symmetric_difference () method returns all the items present in given sets, except the items in their intersections
```

![R.png](attachment:R.png)


```python
a={1,2,3,4,5}
b={4,5,6,7,8}
c=a.symmetric_difference(b)
print(c)
```

    {1, 2, 3, 6, 7, 8}
    


```python
Dictionary:
    a dictionary is a collection that allows us to store data in key-value pairs.


```


```python
Create a dictionary:
    
```


```python
a={'apple' : 'banana',
   'mango' : 'apple'
  }
print(a)
```

    {'apple': 'banana', 'mango': 'apple'}
    


```python
x= {1:[1,2,3],
   'hello':(4,5,6),
   'hello': ['hi']}

x
```




    {1: [1, 2, 3], 'hello': ['hi']}




```python

```
