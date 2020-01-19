# Simple-Pyramid-Pattern

# Function to demonstrate printing pattern 
def pypart(n): 
	
	# outer loop to handle number of rows 

	for i in range(0, n): 
	
		# inner loop to handle number of columns 
		
		for j in range(0, i+1): 
		
			# printing stars 
			print("* ",end="") 
	
		# ending line after each row 
		print("\r") 


n = 5
pypart(n) 
