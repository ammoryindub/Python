# Python
PythoPractice

#### Python Skills
Have few challenges that we will approach to solve with Python code!.

X to the power of n
t = 120 ** 8
print (t)
42998169600000000
4 ** 4
256
using a string and split it into list
t = "Hello World!"
t.split()
['Hello', 'World!']
Using given variables into a code using .format
# varibales  are :

E = "Energy" 
m = "mass"
c = "speed of light"
print ('To explain the meaning of E = mc**2, where {} = {} X {} squared'.format(E,m,c))
To explain the meaning of E = mc**2, where Energy = mass X speed of light squared
Given this nested list, use indexing to grab the word "hello"
# different value lists nested in one list

# note that we break it down to show code steps, usually we can use the last code directly to locate 'hello'!

lst = [1,2,[30,40],[100,[1000,2000,['hello']],300,400,500],5,6]
lst[3]
[100, [1000, 2000, ['hello']], 300, 400]
lst[3][1]
[1000, 2000, ['hello']]
lst[3][1][2]
['hello']
Given this nested dictionary grab the word "hello"
# this time we have a dictionary with various values

# note that we break it down to show code steps, usually we can use the last code directly to locate 'hello'!

d = {'k1':[1,2,3,{'k2':['oh','my','gosh',{'k3':[1,2,3,'hello']}]}]}
d['k1']
[1, 2, 3, {'k2': ['oh', 'my', 'gosh', {'k3': [1, 2, 3, 'hello']}]}]
d['k1'][3]
{'k2': ['oh', 'my', 'gosh', {'k3': [1, 2, 3, 'hello']}]}
d['k1'][3]['k2']
['oh', 'my', 'gosh', {'k3': [1, 2, 3, 'hello']}]
d['k1'][3]['k2'][3]
{'k3': [1, 2, 3, 'hello']}
d['k1'][3]['k2'][3]['k3']
[1, 2, 3, 'hello']
d['k1'][3]['k2'][3]['k3'][3]
'hello'
the main difference between a tuple and a list
# list is mutable  while a tuple is immutable 
A function that grabs the website domain from an email
def get(email):
    return email.split('@')[1]
get('test@test.com')
'test.com'
A function finds me if a certain word is in a string
def find(s):
    return 'hello' in s.lower().split()
s = 'Hello there anyone home?'
s.lower()
'hello there anyone home?'
s.split()
['Hello', 'there', 'anyone', 'home?']
find ('Hello there anyone home?')
True
A function counts how many times a word occurs in a string
def count(w):
    count = 0
    for word in w.lower().split():
        if word == 'he':
            count = count+1
    return count
count ('he loves me becasue after our date he bought me flowers')
2
Use lambda expressions and the filter() function to filter out words from a list that start with the letter 'o'
seq =['apple','orange','onion','grapes','potato']
filter (lambda word: word[0]=='o',seq)
<filter at 0x7fcb7cf19370>
list(filter(lambda word: word[0]=='o', seq))
['orange', 'onion']
Write a function to return one of 3 possible results: If your speed is 60 or less, the result is "No Ticket". If speed is between 61 and 80 inclusive, the result is "Small Ticket". If the speed is 81 or more, the result is "Big Ticket".
def ticket(speed):
    if speed > 80:
        return 'Big Ticket'
    elif speed > 60:
        return 'Small Ticket'
    else:
        return 'No Ticekt'
ticket (50)
'No Ticekt'
ticket (70)
'Small Ticket'
ticket (100)
'Big Ticket'
- - - - The end - - - -
