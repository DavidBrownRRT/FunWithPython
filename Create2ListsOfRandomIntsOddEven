#Author David A Brown
#Create two lists of 10 random integers in the range from 1-300
#One containing odd numbers and one even numbers
import random
numOdd = []
numEven = []

while True:
    rand = random.randint(1,300)
    if len(numOdd) == 10 and len(numEven) == 10:
        print('Odd List:',numOdd)
        print('Even List:',numEven)
        break
    elif len(numOdd) < 10 and (rand % 2):
        numOdd.append(rand)
    elif len(numEven) < 10 and rand%2 == False:
        numEven.append(rand)
