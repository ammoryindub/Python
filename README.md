# Python
PythoPractice

#### Python Skills
- Split into a list

- Using variables in a code

- nested lists

- difference between a tuple and a list


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
