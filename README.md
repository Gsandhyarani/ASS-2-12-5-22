# ASS-2-12-5-22
GIVEN  NUMBER IS ARMSTRONG  OR NOT USING METHOD
num = int(input("Enter a number: "))
sum = 0
temp = num
while temp > 0:
   digit = temp % 10
   sum += digit ** 3
   temp //= 10
if num == sum:
   print(num,"is an Armstrong number")
else:
   print(num,"is not an Armstrong number")
OUTPUT:
 enter a number:489
 489 is not a armstrong number
