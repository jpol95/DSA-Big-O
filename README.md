# DSA-Big-O

1.O(1). Assuming everyone is in range and can hear you, it doesn't matter how many people are in the room, all you have to do is yell once thing and if someone has your dog type they will respond. 

2. O(n). You are asking everyone, so the time is a function of how many people are in the room. 

3. O(1). There is only one input and you are only doing one operation on it.

4. O(n * m), where n is the size of array 1 and m is the size of array 2. For every element in array n, you are doing m comparisons, so the run time is a function of the product of n and m. 

5. O(n), where n is the size of the array. You are going through each element in the array and doing an operation, so the run time is depenedent on the number of items in the array. 

6. O(n), where n is the size of the array. You are going through each element in the array and doing an operation, so the run time is depenedent on the number of items in the array. Tecnically, the for loop can end early if the match is found, so the average run time is probably O(n/2), but the asymptotic run time is O(n). 

7. O(n^2), where n is the size of the array. You are going through n elements and then, for each of those elements, you are going through an average of n/2 elements. So, the average time complexity is O(n^2/2), giving an asymptotic run time of O(n^2). 

8. The algorithm produces the fibonacci sequence iteratively. The run time is O(n), since you are looping through the size of the number you are inputting and then performing different array operations, each with time complexities of O(1). 

9. This is a binary search and has a time complexity of O(logn), since the time complexity is proportional to how many times you can half the size of the array. 

10. O(1). None of the operations is depenedent on the size of the input. 

11. The algorithm checks if a number is prime, very inefficiently I might add. The current run time is O(n), but the efficient version of the algorithm should be O(sqrt(n)) because you only need to check up the numbers up to the square root to see if a number is prime. You can never have a number with two factors that are both above the square root of said number. 
