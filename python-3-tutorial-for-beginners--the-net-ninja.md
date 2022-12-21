
Python 3 Tutorial for Beginners #1 - Why Learn Python?

https://www.youtube.com/watch?v=Ozrduu2W9B8&list=PL4cUxeGkcC9idu6GZ8EU_5B6WpKTdYZbK

Used:

Create websites

Run scientific apps

Control Robots

A general purpose programming language

Can be used for many different things

A high-level programming language

Fun and easy to learn

Types

Classes

Interact with files on your computer

Mini projects

https://github.com/iamshaunjp/python-3-playlist

atom.io

cmder


Python 3 Tutorial for Beginners #2 - Installing Python 3

https://www.youtube.com/watch?v=SbQAAuom-GA&list=PL4cUxeGkcC9idu6GZ8EU_5B6WpKTdYZbK&index=2

 

(Windows)

 

python -V

 

Python.org

Downloads, windows.

Install

Add Python 3.6 to PATH (so you can use it anywhere)

Install Now

 

python -V

 

python

 

will put you in the python shell

 

>>> 

 

Ctrl+Z.

Enter.

To exit out of the python shell

 

python filename.py




Python 3 Tutorial for Beginners #3 - Numbers

https://www.youtube.com/watch?v=Gqby4v5JOu4&list=PL4cUxeGkcC9idu6GZ8EU_5B6WpKTdYZbK&index=3

 

python

 

everything is an object.

Every object has attributes and methods (functions)

 

Int 1,2,3,4 whole number

Floats 1.2,1.3,1.4 decimal number

 

type(5)

type(1.23)

 

5 + 5 = 10

 

5 - 5 = 0

 

5 * 5 = 25

 

5 / 5 = 1.0 (quirk of the programming language)

 

5 // 5 = 1

 

5 ** 5 = 3125

 

10 % 3 = 1

 

5 + 5 * 3 =  20

 

BIDMAS

 

age = 25

age

25

age + 5

30

age

25

age = age + 5

30

age

30

age += 5

35

age

35

 

-=

/=

 

wages = 1000

bills = 200

rent = 500

food = 200

savings = wages – bills – rent – food

savings

 
Python 3 Tutorial for Beginners #4 - Strings

https://www.youtube.com/watch?v=---_iWTjtB4&list=PL4cUxeGkcC9idu6GZ8EU_5B6WpKTdYZbK&index=4

 

 

“hello”

‘hello’

‘he’s a mad man’ ERROR

“he’s a mad man”

‘he\’s a mad man’

 

Indexed from 0

 

greet = ‘hello’

greet

greet[0] = h

greet[-5] = h

greet[0:3] = hel

greet[-1:2] = ‘ ’

greent[2:-1] = ll

 

greet = greet[-:3]

greet = ‘hello’

str2 = ‘dudes’

greet + str2 = ‘hellodudes’

greet + ‘ ’ + str2 = ‘hello dudes’

greet * 3 = ‘hellohellohello’

 

greet.upper() = HELLO

greet = greet.upper()

 

cheeses = “brie, chedder, stilton”

cheeses.split(‘,’)

[‘brie’, ‘chedder’, ‘stilton’]

 

Len(greet) = 5




Python 3 Tutorial for Beginners #5 - Lists

https://www.youtube.com/watch?v=cl0R4Tbf2v0&list=PL4cUxeGkcC9idu6GZ8EU_5B6WpKTdYZbK&index=5

 

 

python

 

str = “hello there dudes”

str.split(‘ ’)

[‘hello’, ‘there’, ‘dudes’]

fib1 = [1,1,2,3,5,8,13]

fib1[2] = 2

fib1[0:4]

[1,1,2,3]

fib2 = [21,34,55]

fib1+fib2

[1,1,2,3,5,8,13,21,34,55]

Fib1[0] =  9

[9,1,2,3,5,8,13]

Fib = fib1+fib2

Fib.append(89)

Fib.pop()

Fib.remove(89)

del(fib[10])

nums = [[1,23,4],[3,4,5,6],[7,8,90,45]]

nums[1][1]

4

 

 
