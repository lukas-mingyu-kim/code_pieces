python code to demonstrate working of reduce() 

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

output:  
&nbsp;&nbsp;&nbsp;&nbsp;The sum of the list elements is : 17  
&nbsp;&nbsp;&nbsp;&nbsp;The maximum element of the list is : 6
