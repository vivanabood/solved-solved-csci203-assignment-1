Download Link: https://assignmentchef.com/product/solved-solved-csci203-assignment-1
<br>
1. Prove that x log y = y log x

2. Let g(n) be the number of ways to write a string of n zeros and ones so that there are never two successive zeros. Show that g(n) = fib(n+2). (Hint: try induction.)

3. Which of the following statements are true? Prove your answers. a. n2  O(n3 ) b. n2  Ω(n3 ) c. 2n  Θ(2n+1) d. n!  Θ((n+1)!)

4. An alternative proof that there are an infinite number of primes begins as follows. Assume that the set of prime numbers is finite. Let P be the largest prime. Consider X=P! and Y=X+1. Complete the proof and construct an algorithm bigprime(P) based on the proof. It should be clear from the algorithm that it terminates with a new prime larger than P. (Note: this algorithm should not involve brute-force testing of candidate primes by exhaustive division.)

5. Suppose A and B are two finite sets. Show that  where denotes the number of elements in set A. What is the equivalent equation for three sets, A, B and C?

6. Two algorithms take n^2 days and n^3 seconds to solve an instance of size n. Which is the better algorithm? What is the break-even value for n? How long will the algorithms take at this value of n?

7. A function f (x) such that f (a) and f (b) have different signs must have at least one root (value where the function is zero) between a and

b. Devise an algorithm based on finding the value of x at which the line joining the points (a, f(a)) and (b, f(b)) crosses the x-axis and then determining the sign of the function at this point.

8. Use the secant method of question 7 to perform three iterations with f(x) = x3 – 4x + 1, a = 1 and b = 2. Tabulate the values of all variables at each stage.

9. Give two functions f(n) and g(n) such that neither f(n) nor g(n) tends to a limit as n tends to infinity, but both f(n)+g(n) and f(n)/g(n) do tend to a limit.

10. A certain algorithm takes 0.0001 x 2n seconds to solve an instance of size n. Show that it just solves an instance of size 38 in a year. What size problem could be solved in a year on a machine 100 times as fast? A second algorithm takes 0.01 x n3 seconds to solve an instance of size n. What size problem could it solve in a year? With a machine 100 times as fast? For what range of n is the first algorithm better? Assignments should be typed into a text file called ass1.txt and submitted via the submit program in Unix. submit -u user -c csci203 -a 1 ass1.txt where your unix userid should appear instead of user.