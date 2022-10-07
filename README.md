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
