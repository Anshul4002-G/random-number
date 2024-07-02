# guess the number

import random
n=random.randint(0,100)

a=-1
guesses=0
while(a!=n):
    
    a=int(input("guess the number "))
    if(a>n):
     print("lower guess please")
     guesses+=1
    elif(a<n):
       print("higher number please ")
       guesses+=1
    

print(f"you guessed the right number after {guesses} guesses")
    



