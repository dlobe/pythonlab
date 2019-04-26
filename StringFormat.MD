# STRING FORMATING

## Old and deprecated way

greet_old = 'Hello %s'
a = greet_old % 'Modiks'

## Positional placeholders

greet_positional = 'Hello {} {}'

b = greet_positional.format('Dav', 'Modiks')

## Positional Placeholders using index

greet_positional_idx = 'This is {0}! {1} loves {0}!'

c = greet_positional_idx.format('Python', 'Fab')

d = greet_positional_idx.format('coffee', 'Fab')

## Keywords

keyword = 'Hello, my name is {name} {last_name}'

e = keyword.format(name='Dav', last_name='Ivy')

## formatted string literals

name = 'Dav'
age = 20
f = f"Hello my name is {name} and i am {age}"
