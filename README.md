# flip-number-of-coins-and-show-how-many-heads-and-tails
import random   

heads = 0
tails = 0
number_of_flips = input("Enter the number of coins you want to flip :")

# i is a changeable value
for i in range (int(number_of_flips)):

# c is a value of the random result
    c = random.randint(0, 1)
    if c == 0:
        heads += 1         
        print("heads")
        
    else:
        tails +=1         
        print("tails") 

print("number of tailes is " + str(tails)), print("number of heads is " + str(heads))
