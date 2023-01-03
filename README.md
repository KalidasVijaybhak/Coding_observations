# Coding_observations

 ## Observation 1 (Modulus operator)
 
 
   > 0%11 = 0
   
   > 11%11 = 0
   
   > 1%11 = 1

   > 12%11 = 1

   > 10%11 = 10

## Prime no. solution 
   Case 1 If asked to find prime between 1 - 100
	
		for i in range(1,100)
			if i == 2 or i==3 or  i== 5 or i==7 : 
				print(i)
 			elif i%2!=0 and i%3!=0 and i%5!=0 and i%7!=0:
 				print(i)
 				

## Call by reference call by value
![image](https://github.com/KalidasVijaybhak/Coding_observations/blob/master/resources/pass-by-reference-vs-pass-by-value-.gif)

## Wildcards

	Alternatively referred to as a wild character or wildcard character, a
	wildcard is a symbol used to replace or represent one or more characters.
	The most common wildcards are the asterisk (*), which represents one or more characters 

## Prefix Postfix
x++
> value first used and then incremented

++x 
> value incremented and then used

## Multidimensional 

# Nested Loops

		#include <iostream>
		using namespace std;
			int main()
	
		{
		    int i,j ;
			for(i = 0;i<2;i++){
			  cout<<"\nWeek: "<<i+1<<endl;
				 for(j = 0;j<7;j++){
					cout<<"Day: "<<j+1<<endl;
			 }


		}
}

> Output

![image](https://user-images.githubusercontent.com/70281178/194557338-c8016a1f-38b5-4af9-9e9a-266455960b68.png)


# Terminologies

## Variable

A variable is a named memory location which temporarily stores data that can change while the program is running. A constant is a named memory location which temporarily stores data that remains the same throughout the execution of the program. The type of a variable indicates what kind of value it will store.

## Identifiers

"Identifiers" or "symbols" are the names you supply for variables, types, functions, and labels in your program. Identifier names must differ in spelling and case from any keywords.


## Literals

Literals or constants are the values we write in a conventional form whose value is obvious. In contrast to variables, literals (123, 4.3, "hi") do not change in value. These are also called explicit constants or manifest constants.
For example, const int =10; is a constant integer expression in which 10 is an integer literal.

## Arguments and Parameters

![image](https://user-images.githubusercontent.com/70281178/194724628-58b389bb-9d30-4f5c-bb4e-8259c2b49729.png)

## Data Types

A data type, in programming, is a classification that specifies which type of value a variable has and what type of mathematical, relational or logical operations can be applied to it without causing an error.

![image](https://user-images.githubusercontent.com/70281178/194724724-a61de399-5c63-4d2e-8861-c6094f04bd4f.png)

## Is void a data type or keyword?

Void is considered a data type (for organizational purposes), but it is basically a keyword to use as a placeholder where you would put a data type, to represent "no data".

## NULL

null means it doesn't have a value but still you are bound to put a value which is equivalent to nothing.

Let's suppose you have a variable ‘X' which stores the number of coins you have in your pocket.

If X=4 , means you have 4 coins

If X=0 , means you don't have any coins

If X= null, means you haven't checked your pocket yet and you don't know how many coins you have, so you have made it null. It means you just don't know.

If you check null==0 it will return false.

Lastly, null is typically a keyword to indicate the space in memory is a pointer (reference), and that pointer is pointing to an invalid memory address (usually 0x0).

## what is recursion

Recursion is a programming technique in which a function calls itself with a simpler version of the original problem, typically as a way to solve the original problem.

To use recursion, the function must have a base case, which is a condition that stops the recursion, and a recursive case, which is the function calling itself with a simplified version of the original problem. When the base case is reached, the recursion stops and the function returns a result.

Here is an example of a recursive function that calculates the factorial of a number:

 
			def factorial(n):
			    if n == 0:
				return 1
			    else:
				return n * factorial(n - 1)

			print(factorial(5))  # prints 120
			
In this example, the base case is n == 0, and the recursive case is n * factorial(n - 1). When the function is called with n == 5, it will compute 5 * factorial(4), which in turn will compute 4 * factorial(3), and so on, until it reaches the base case of n == 0, at which point the recursion stops and the final result is returned.
