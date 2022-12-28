
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

 

 
Python 3 Tutorial for Beginners #6 - Standard Input

https://www.youtube.com/watch?v=CEO614YbQCY&list=PL4cUxeGkcC9idu6GZ8EU_5B6WpKTdYZbK&index=6

 

create python files.

 

Atom (Text Editor)

Area_calc.py

 

# comments

 

name = Input(‘Tell me you name, punk: ’)

print(‘hello ’ + name)

age = input(‘…and your age: ’)

print(name, ‘you are’, age)

 

 

# Calc the area of a circle

 

radius = input(‘Enter the radius of your circle (m): ’)

area = 3.142 * int(radius)**2

print(‘The area of your circle is:’, area)

 

ERROR because radius by input is String.

 

314.2

 

Command Line

Move to directory

 

Python area_calc.py



Python 3 Tutorial for Beginners #7 - String Formatting

https://www.youtube.com/watch?v=yVGSeRcQfyI&list=PL4cUxeGkcC9idu6GZ8EU_5B6WpKTdYZbK&index=7

 

 

Atom (Text Editor)

string_fortmat.py

 

num1 = 3.1425467389

num2 = 10.2903948

 

# print(‘num 1 is’, num1, ‘and num 2 is’, num2)

Print(‘num 1 is {0:.3f} and num 2 is {1:.3f}’.fortmat(num1, num2))

 

# f-string

 

Print(f‘num 1 is {num1} and num 2 is {num2}’)

 

Command Line

 

Python string_format.py

 

 

Python 3 Tutorial for Beginners #8 - If Statements

https://www.youtube.com/watch?v=t3c41sKJS20&list=PL4cUxeGkcC9idu6GZ8EU_5B6WpKTdYZbK&index=8

 

 

 

Atom (Text Editor)

If_elif.py

 

age = int(input(‘Enter your age: ’))

 

if age < 10:

            # code block, MUST be indented

            Print(‘you are young, strange one’)

 

elif age < 40:

            print(‘the fire in you is strong, strange one’)

 

else:

            print(‘you are wise beyond doubt, strange one’)

 

meaty = input(‘Do you eat meet? (y/n): ’)

 

if meaty == ‘y’:

            print(‘here is the meaty menu…’)

else:

            print(‘here is the veggie menu…’)

 

 

# OPERATORS

 

# >, <, ==, !=, =>, =<

 

Command Line

Python if elif.py

 

9

You are young, strange one

10

…

the fire in you is strong, strange one

45

you are wise beyond doubt, strange one’

6

You are young, strange one



Python 3 Tutorial for Beginners #9 - For Loops

https://www.youtube.com/watch?v=ENMCxQ9kNS4&list=PL4cUxeGkcC9idu6GZ8EU_5B6WpKTdYZbK&index=9

 

Atom (Text Editor)

loops.py

 

ninjas = [‘ryu’, ‘crystal’, ‘yoshi’, ‘ken’]

 

for ninja in ninjas:

            print(ninja)

 

for ninja in ninjas[1:3]:

            print(ninja)

 

for ninja in ninjas:

            if ninja == ‘yoshi’:

                        print(f‘{ninja} – black belt’)

            else:

                        print(ninja);

 

for ninja in ninjas:

            if ninja == ‘yoshi’:

                        print(f‘{ninja} – black belt’)

                        break

            else:

                        print(ninja);

 

 

Command Line

Python loops.py

 

 

ryu

crystal

yoshi

ken

 

crystal

yoshi

 

 

ryu

crystal

yoshi – black belt

ken

 

 

ryu

crystal

yoshi – black belt

 
Python 3 Tutorial for Beginners #10 - While Loops

https://www.youtube.com/watch?v=7p-BJ92aZp0&list=PL4cUxeGkcC9idu6GZ8EU_5B6WpKTdYZbK&index=10

 

Atom (Text Editor)

loops.py

 

age = 25

num = 0

 

while num < age:

            print(num)

num += 1

 

while num < age:

            if num == 0:

num += 1

                        continue

            if num % 2 == 0:

                        print(num)

if num > 10:

            break

num += 1

 

Command Line

Python loops.py

 

0 to 24

 

2

4

6

8

10

 
Python 3 Tutorial for Beginners #11 - Ranges

https://www.youtube.com/watch?v=GhrChSfaiu0&list=PL4cUxeGkcC9idu6GZ8EU_5B6WpKTdYZbK&index=11

 

 

Atom (Text Editor)

ranges.py

 

 

for n in range(5):

            print(n)

 

for n in range(3,10):

            print(n)

 

for n in range(0,20,4):

            print(n)

 

burgers = [‘beef’, ‘chicken’, ‘veg’, ‘supreme’, ‘double’]

 

for n in range(len(burgers)):

print(n, burgers[n])

 

for n in range(len(burgers) - 1, -1, -1)

print(n, burgers[n])

 

 

Command Line

Python ranges.py

 

0

1

2

3

4

 

3

4

5

6

7

8

9

 

0

4

8

12

16

 

0 Beef

1 Chicken

2 Veg

3 Supreme

4 Double

 

4 Double

3 Supreme

2 Veg

1 Chicken

0 Beef

 

Python 3 Tutorial for Beginners #12 - Functions

https://www.youtube.com/watch?v=l0E1tK-O8ew&list=PL4cUxeGkcC9idu6GZ8EU_5B6WpKTdYZbK&index=12

 

def = define

 

Atom (Text Editor)

functions.py

 

 

def greet():

            print(‘hello world’)

 

greet()

 

def greet(name, time):

            print(f‘Good {time} {name}, hope you are well’)

 

greet(‘shaun’, ‘morning’)

 

 

 

 

 

 

 

 

def greet(name, time):

            print(f‘Good {time} {name}, hope you are well’)

 

 

name = input(‘enter your name: ’)

time = input(‘enter the time of day: ’)

 

greet(name, time)

 

 

def greet(name = ‘ryu’, time = ‘morning’):

            print(f‘Good {time} {name}, hope you are well’)

 

 

name = input(‘enter your name: ’)

time = input(‘enter the time of day: ’)

 

greet(name, time)

 

def area (radius):

            print(3.142 * radius * radius)

 

area(5)

 

 

def area (radius):

            print(3.142 * radius * radius)

 

radius = int(input(‘enter a radius: ’))

 

area(radius)

 

 

def area (radius):

            print(3.142 * radius * radius)

 

def vol(area, length):

            print(area * length)

 

radius = int(input(‘enter a radius: ’))

length = int(input(‘enter a length: ’))

 

area_calc = area(radius)

 

vol(area_calc, length)

 

OR

 

vol(area(radius), length)

 

 

 

 

 

Command Line

Python functions.py

 

 

hello world

 

good morning shaun, hope you are well

 

= shaun

= morning

good morning shaun, hope you are well

 

=

=

ERROR

 

=

=

Googin morning ryu, hope you are well

 

78.55

 

=5

78.55

 

=7

=8

1231.664

 

 

 

 

 

 

 

 

 

 

 

 