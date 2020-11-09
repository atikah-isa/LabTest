# LabTest
#Question 1
def remainder(num1):
    
    while num1!= 0:
        bal= num1 % 2
        num1 = int (num1/2)
        print(bal)
    if bal == 1:
        bit= bal+ bal
        print(bit)

remainder(24)

#Question 2
def noOfWord(sentence):
    word =len(sentence)
    output =[0]*word
    
    count =[0]*10
    
    for i in range(0, size):
        count[sentence[i]] +=1
    for i in range(1, 10):
        count[i] += count[i-1]
        
    i = size-1
    while i>=0:
        output[count[sentence[i]]-1] = array[i]
        count[array[i]] -=1
        i-=1
        
    for i in range(0, size):
        array[i] = output[i]

data =[4, 2, 3]
noOfWord(data)

#Question 4
def print_arguments(function):
    return new()

def new(x):
    return x*2

new(1)
       
