## Assignment Details

[16,21,11,8,12,22] -> Merge Sort  
  
Write the stages of the above array according to the sort type.  
Write the Big-O notation.  

### Solution

Given array: [16, 21, 11, 8, 12, 22]  

Step 1 (Divide):  
The array is divided into subarrays: [16, 21, 11] and [8, 12, 22]   

Step 2 (Divide):  
The first subarrays are further divided: [16], [21], [11]  

Step 3 (Merge):  
The first subarrays are merged: [16, 21, 11]  

Step 4 (Divide):  
The second subarrays are further divided: [8], [12], [22]  

Step 5 (Merge):  
The second subarrays are merged: [8, 12, 22]  

Step 6 (Merge):  
Finally, the two sorted subarrays are merged: [8, 11, 12, 16, 21, 22]  

Result:  
The array is now sorted: [8, 11, 12, 16, 21, 22]  
  
The Big-O notation for Merge Sort: O(n log n)  
