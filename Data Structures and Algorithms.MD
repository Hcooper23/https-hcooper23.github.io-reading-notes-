## Discussion Questions

- What is 1 of the more important things you should consider when deciding which data structure is best suited to solve a particular problem?

When choosing a data structure for a specific problem, it is crucial to consider several factors, and one of the most important ones is the Big O notation. The Big O notation provides an estimation of the efficiency or scalability of an algorithm, indicating how its performance will scale with the size of the input. Different data structures have varying strengths and weaknesses, and analyzing their Big O complexities can help identify the most suitable one for a given problem. By selecting a data structure with a low Big O factor, you can optimize the algorithm's performance.

- How can we ensure that we’ll avoid an infinite recursive call stack?

To avoid an infinite recursive call stack, it is essential to structure recursive functions properly. Recursive calls occur when a function invokes itself, and without appropriate control, this can lead to an infinite loop. To prevent such scenarios, it is important to divide the recursive function into two essential parts: the base case and the recursive case. The base case represents the condition that terminates the recursion, while the recursive case defines the action performed within the recursive loop. By incorporating conditional statements within the loop (such as if/else statements), you can handle the base case when the loop's exit conditions are met, and execute the recursive case to continue the iterative process.