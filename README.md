import random

ainum = random.randint(1,10)
ainum2 = random.randint(5,20)



useransw = int(input("pick a number between: 1 - 10\n" ))

useransw2 = int(input("pick a number between: 5 - 20\n"))
if ainum == useransw:
    print("you have won")


    
    if ainum2 == useransw2:
        print("correct, again")
    
elif ainum2 == useransw2:
  print("incorrect, again")

else:
    print("incorrect")
