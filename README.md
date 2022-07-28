# numbers
arrangement of numbers with you choosing your starting and ending point
num1 = float(input("starting point:"))
num2 = float(input("end point:"))

if num1>num2:
	while num1>=num2:
		print(num1)
		num1=num1-1
else:
	while num1<=num2:
		print(num1)
		num1=num1+1
