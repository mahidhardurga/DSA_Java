# DSA_Java

**Data Structures**
1.It is a way to organize data
2.After organizing data it becomes easy to process the data

**Types of Data Structures**
1.Linear - 
	Data elements are arranged in sequential manner
	Traversal is single level as they are connected sequentially
	Ex: Array, linked list, stack and queue
2.Non-Linear - 
	Data elements are not arranged in sequence
	They are connected in different paths i.e multi level connection between data elements
	Ex: Tree, Graph

**Algorithms**
An algorithm is a set of instructions to perform a task or to solve a given problem
For Example - A recipe book is a collection of recipes in which each recipe provides an step by step instruction to prepare food.

**Analysis of Algorithms**
An Algorithm is a set of instructions to perform a task or to solve a given problem.
There are several different algorithms to solve a given problem.
**Analysis of algorithm deals in finding best algorithm which runs fast and takes in less memory**
Ideally there are two factors two identify the best algorithm
1.Time Complexity
2.Space Complexity

**Time Complexity**
it is amount of time taken by algorithm to run.
The input processed by an algorithm helps in determining the time complexity

**Space Complexity**
it is an amount of of memory or space taken by an algorithm to run
The memory required to process the input by an algorithm helps in determining the space complexity

**Asymptotic Analysis**
asymptotic analysis helps in evaluating performance of an algorithm in terms of input size and its increase.
Using asymptotic analysis we don't measure actual running time of algorithm.
it helps in determining how time and space taken by algorithm increases with input size

**Asymptotic Notations**
Asymptotic Notations are the mathematical tools used to describe the running time of an algorithm in terms of input size
Asymptotic Notations help us in determining
1.Best case
2.Average Case
3.Worst Case

**Types of Asymptotic Notations**
There are three notations for performing runtime analysis of an algorithm
1.Omega notation
2.Big O Notation
3.Theta Notation

**Omega notation**
it is the formal way to express the lower bound of an algorithm's running time, this will provide the info of minimum time required to complete
Lower bound means for any given input this notation determines best amount of time an algorithm can take to complete
For Ex:- if we say certain algorithm takes 100 secs as best amount of time so, 100 secs will be lower bound of that algorithm. The algorithm can take more than 100 secs but will not take less than 100 secs

**Big O Notation**
it is the formal way to express the upper bound of an algorithm's running time.
Upper bound means for any given input this notatin determines longest amount of time an algorithm can take to complete.
For Ex:- if we say certain algorithm takes 100 secs as longest amount of time so, 100 secs will be upper bound of that algorithm. The algorithm can take less than 100 secs but will not take more than 100 secs

**Note:-** This is the mostly used Notation to find the time complexity as we are more interested in finding the maximum time takes to run so that we can optimize the algorithm to which ever time we want
So here the Big O Notation provides us the worst case analysis of an algorithm 


**Theta Notation**
it is the formal way to express both the upper and lower bound of an algorithm's running time
By Lower and upper bound means for any given input this notation determines average amount of time an algorithm can take to complete

For Ex:- if we run certainalgorithm and takes 100 secs for sirst time run, 120 secs for second run, 110 for third run and so on. so, theta notations gives an average of running time of that algorithm
This notation is also leastly used because there are very rare use cases where we actually determine average time taken by algorithm to complete
