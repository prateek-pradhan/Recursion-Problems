# Recursion

## Pre-requisites: 

Knowledge of

●	Recursion

Q1. Re-implement selection sort using recursion

Q2.   Given 2 numbers, find GCD (greatest common divisor). Implement using recursion.  Example: GCD(10,15) = 5

Q3. Implement the tower of hanoi function but instead of implementing the actual move function, just print the movement along with count of movements. 

void tower_of_hanoi(int n, char from, char to, char aux){ <br />
   //add your code here <br />

} <br />
int main() { <br />
   tower_of_hanoi(3,'A','C','B'); <br />
} <br />

Expected output: 
A to C <br />
A to B <br />
C to B <br />
A to C <br />
B to A <br />
B to C <br />
A to C <br />
Total movements required = 7<br />

Q4. Print n times the every third element of the fibonacci series. (you can use iteration or recursion with memoization)

/*
Expected output: <br />
n = 3 : 2,8,44 <br />
Explanation: fib series is 1,1,2,3,5,8,13,21,44…. 3rd in this series is 2, 6th is 8 and 9th is 44. <br />

*/ <br />
void fib(int n) { <br />
     // your code <br />
} <br />

Q5. King has 1000 bottles of wine to be consumed in a party after 7 days. Palace guards found one of the bottles was poisoned by a spy. King wants rest 999 bottles in the party and for that the poisonous bottle has to be identified and discarded. King has given 10 prisoners whom you can test. You have to find a strategy to identify the poisonous bottles using these 10 prisoners. Below are a few key points to design a strategy. 

1.	Bottles are of infinite capacity - you can take out any amount for testing

2.	Even if you drink single drop of whole bottle you will die but in exactly 7 days

3.	You don't care about the lives of these 10 prisoners. 

