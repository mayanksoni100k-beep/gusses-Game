# gusses-Game
import random
n = random.randint(1,100)
a = -1
guesses = 0
while(a!=n):
    guesses +=1
    a = int(input("entre number"))
    if ( a>n):
        print("entre lower number please")
        guesses+=1
    elif(a<n):
        
        print("entre higher number please")
        guesses+=1           

print(f"youre gussed right number {n} in {guesses} attempt ")
