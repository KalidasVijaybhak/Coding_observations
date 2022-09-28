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
 				
