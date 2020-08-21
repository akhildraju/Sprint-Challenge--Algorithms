#### Please add your answers to the ***Analysis of  Algorithms*** exercises here.

## Exercise I

a) O(n^3)


b) n * (n/2 + n/4 + n/8 ....)  = O(nLogn)


c) The bunnyEars gets executed based on the value of bunnies with simple recursion. So the answer is O(n)

## Exercise II

#start from  top floor and throw an egg off each floor until  you  find the one that breaks the egg.

def is_broken(f):

def throw_egg():

max_floor = n
current_floor = max_floor
num_eggs = 0

while current_floor >= 0:
    throw_egg()
    if is_broken():
        return num_eggs, (max_floor-current_floor)
    num_eggs += 1
    current_floor -= 1

The runtime complexity of the solution is O(n)
