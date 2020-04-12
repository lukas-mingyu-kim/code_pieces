
#### functools.reduce() 

<pre><code>
import collections

print collections.Counter(['a', 'b', 'c', 'a', 'b', 'b'])
print collections.Counter({'a':2, 'b':3, 'c':1})
print collections.Counter(a=2, b=3, c=1)
</pre></code>

###### output:
Counter({'b': 3, 'a': 2, 'c': 1})  
Counter({'b': 3, 'a': 2, 'c': 1})  
Counter({'b': 3, 'a': 2, 'c': 1})
  
  
  


#### functools.reduce() 

<pre><code>
import functools 
lis = [ 1 , 3, 5, 6, 2, ]

# using reduce to compute sum of list 
print ("The sum of the list elements is : ",end="") 
print (functools.reduce(lambda a,b : a+b,lis)) 
  
# using reduce to compute maximum element from list 
print ("The maximum element of the list is : ",end="") 
print (functools.reduce(lambda a,b : a if a > b else b,lis))
</pre></code>

###### output:  
The sum of the list elements is : 17  
The maximum element of the list is : 6
