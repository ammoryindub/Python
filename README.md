# Python
PythoPractice

#### Python Skills
- Split into a list

- Using variables in a code

- nested lists

- the difference between a tuple and a list



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
