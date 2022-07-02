# lottery1

# set double digits 

#if your number is absolutely correct, you'll accept 100$

#if your number is correct with one of the double digits , you'll accept 50$

import random

x=int(input("set double digits : "))

y= random.randint(0,99)

print(" lottery number is ",str(y))

if x==y:

  print(" 100 $")

elif (x//10)==(y//10) or (x%10)==(y%10) :

  print("50$")

else :

  print("0$")
  
