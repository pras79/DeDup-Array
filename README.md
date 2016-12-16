# DeDup-Array

# Method1 : 
Sorting an array to remove duplicates. quick sort approach to sort an array and removed duplicates over iterating the sorted array. 
Time complexity: O(n log(n)) * O(n)  
Space complexity: constant time as there is no auxiliary array 
This solution works well, less memory and big input data conditions 
again to compromise on perforance and array order. 

# Method 2: 
Set to remove the duplicates - order maintained but auxiliary array is used 
Time complexity O(n) 
Space complexity:  O(n) since auxiliary array is used.
We can use this approach if we have enough memory to consume.
This won’t be the ideal solution if the we have memory concerns 
performance  wise it is an ideal solution to choose.
# Method 3: 
 Using Java streams to remove the duplicates.concise and less code and easy to read but again not as fast  method 2. But it consumes les memory as no auxiliary data structure used
Space Complexity:  constant space

this is the ideal solution for big input data.choose this if you have large amount of data as strams are reallt works well with big data conditions

but performance wise slowern than method 2

