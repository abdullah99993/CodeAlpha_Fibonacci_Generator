# CodeAlpha_Fibonacci_Generator

Fibonacci Generator:-
                     A Fibonacci generator is a function or an algorithm that generates numbers in the Fibonacci sequence. The Fibonacci sequence is a series of numbers where each number is the sum of the two preceding ones, usually starting with 0 and 1. The sequence typically looks like this: 0, 1, 1, 2, 3, 5, 8, 13, 21, 34, ...
Definition
The Fibonacci sequence is defined by the following recurrence relation:
F(n)=F(n−1)+F(n−2)F(n) = F(n-1) + F(n-2)F(n)=F(n−1)+F(n−2)
with initial conditions:
F(0)=0F(0) = 0F(0)=0 F(1)=1F(1) = 1F(1)=1
Explanation
1.Initial Conditions: The sequence starts with 0 and 1.
2.Recurrence Relation: Each subsequent number is the sum of the previous two numbers.
Example
Let's look at the first few numbers in the Fibonacci sequence:
F(0) = 0
F(1) = 1
F(2) = F(1) + F(0) = 1 + 0 = 1

CODE EXPLANATION:-
                    This Python code defines a generator function named fibo that produces an infinite sequence of Fibonacci numbers. A generator function allows you to iterate over a potentially large sequence of values without storing them all in memory at once. The fibo function initializes the first two Fibonacci numbers, 0 and 1, and then enters an infinite loop where it yields the current Fibonacci number and updates the variables to the next two numbers in the sequence. The generator is then used in a loop to print all Fibonacci numbers up to 10,000. After exiting the loop, it prints the next Fibonacci number in the sequence. The input to this code is implicit as it operates without external inputs other than the termination condition in the loop. The output consists of all Fibonacci numbers up to 10,000, followed by the next Fibonacci number after 10,000. The yield statement in the generator function is crucial for producing values one at a time, allowing the function to resume where it left off each time it is called. The for loop iterates over the generator, and the if statement within the loop serves as the stopping condition to terminate the loop once the Fibonacci number exceeds 10,000. The next(f) function call is used to retrieve the next value from the generator after the loop has stopped.
F(3) = F(2) + F(1) = 1 + 1 = 2
F(4) = F(3) + F(2) = 2 + 1 = 3
F(5) = F(4) + F(3) = 3 + 2 = 5
And so on...
