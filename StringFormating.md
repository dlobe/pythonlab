greet_old = 'Hello %s'
a = greet_old % 'Modiks'
s

#kkkk
greet_positional = 'Hello {} {}'

b = greet_positional.format('Dav', 'Modiks')

greet_positional_idx = 'This is {0}! {1} loves {0}!'

c = greet_positional_idx.format('Python', 'Fab')

d = greet_positional_idx.format('coffee', 'Fab')

keyword = 'Hello, my name is {name} {last_name}'

e = keyword.format(name='Dav', last_name='Ivy')