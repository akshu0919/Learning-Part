## **Notes on Data Structures and Algorithms in Java**

**Big O Notation:**
We use this to describe the performance of an algorithm. 
Helps us determine if an algorthim is scalable or not. Is this algorthm going to scale well if the input gets very large?
Certain operations an be more or less costly based on what data structure is used.
- O(1), O(2), and etc. means that the operation runs in constant time and that it doesnt matter what the input is.
- O(n) means that the operation is dependent on the input and that it scales linearly as the input increases. A linear search is an algorithm that works in linear/constant time. 
- O(n^2), O(n^3), and etc. means that the operation is running in quadratic time. An example if this is a nested for loop. These algorithm get slower as the input increases. 
- O(log n) is the logarithmic growth which slows down as the input size grows. These are more scalable and efficient than linear or quadratic. Binary search is an algorth that works in logarithmic time.
- O(2^n) is an exponential growth curve which grows faster and faster. It is the opposite of logarithmic growth. 

Space Complexity:
- O(1) space, O(2) space, and etc. only allocate a small amount of memory. An example is int i = 0 ina  for loop.
- O(n) space is when the memory is allocated based on the size. For example, if an array is 1000 element big then the space is 1000.

**Arrays:**
- Simplest data structures
- Used to store a list of items
- Get stored sequentially in memory
- Looking up an item by using the array index has a complexity of O(1).
- Arrays are static which means when making them, you have to specify their size and cannot change their size later on.
- Must know ahead of time how many items will be stored and if you don't know you must guess.
- Inserting in an array is O(n)
- Removing and item is O(1) if its the last item but for the worst case in which you are removing an item at the very beginning of the array the cost is O(n).
 

**Linked List:**
- Grow or shrink very quickly
- Accessing a link list base element is slow
