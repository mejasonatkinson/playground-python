
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

 

 

Python 3 Tutorial for Beginners #13 - Variable Scope

https://www.youtube.com/watch?v=wueXfiVkw1I&list=PL4cUxeGkcC9idu6GZ8EU_5B6WpKTdYZbK&index=13

 

 

 

 

Atom (Text Editor)

functions.py

 

my_name = ‘ryu’ // global scope

 

def print_name():

            print (my_name)

 

print_name()

print (my_name)

 

 

 

def print_name():

my_name = ‘ryu’ // local scope

            print (my_name)

 

print_name()

print (my_name) // ERROR

 

 

my_name = ‘ryu’ // global scope

 

def print_name():

            my_name = ‘yoshi’ // local scope

            print (my_name)

 

print_name()

print (my_name)

 

 

my_name = ‘ryu’ // global scope

 

def print_name():

global my_name // change to global scope

            my_name = ‘yoshi’ // global scope

            print (my_name)

 

print_name()

print (my_name)

 

 

 

 

Command Line

Python scope.py

 

Ryu

 

ERROR

 

Yoshi

Ryu

 

Yoshi

Yoshi

 
 
Python 3 Tutorial for Beginners #14 - Dictionaries

https://www.youtube.com/watch?v=q8H5R6eP3zQ&list=PL4cUxeGkcC9idu6GZ8EU_5B6WpKTdYZbK&index=14

 

python

ninja_belts = {“crystal”: “red”, “ryu”: “black”}

ninja_belts[“crystal”]

red

ninja_belts[“ryu”]

black

‘yoshi’ in ninja_belts

False

‘ryu’ in ninja_belts

True

Ninja_belts.keys()

Dict_keys([‘crystal’, ‘ryu’])

List(ninja_belts.keys())

[‘crystal’, ‘ryu’]

Ninja_belts.values()

Dict_values([‘red’, black‘])

List(Ninja_belts.values())

[‘red’, black‘]

Vals = List(Ninja_belts.values())

Vals.count(‘black’)

1

Ninja_belts[‘yoshi’] = ‘red’

Ninja_belts

{“crystal”: “red”, “ryu”: “black” “yoshi”: “red”}

Person = dict(name=”shaun”, age=27, height=”6ft”)

Person

{‘name’:’shaun’,  ’age’:27,  ’height’:’6ft’}

 

 

 

Atom (Text Editor)

dictionaries.py

 

def ninja_intro(dictionary)

            for key, val in dictionary.items():

                        print(f’Iam {key} and I am a {val} belt’)

 

ninja_belts = {}

 

while True:

            ninja_name = input(‘enter a ninja name: ’)

ninja_belt = input(‘enter a belt colour: ’)

ninja_belts[ninja_name] = ninja_belt

 

            another = input(‘add another? (y/n)’)

            if another == ‘y’:

                        continue

            else:

                        break

                       

ninja_intro(ninja_belts)

 

Command Line

Python dictionaries.py

 

 

Python 3 Tutorial for Beginners #15 - Sorting & Sets

https://www.youtube.com/watch?v=UirJNoJ9KT8&list=PL4cUxeGkcC9idu6GZ8EU_5B6WpKTdYZbK&index=15

 

nums = [1,4,2,7,3,8,3,4,8,1]

sorted(nums)

[1,1,2,3,3,4,4,7,8,8]

Names = [‘shaun’, ‘ryu’, ‘abe’, ‘Apple’, ‘Brian’, ‘shaun’]

Sorted(names)

[‘Apple’, ‘Brian’, ‘abe’, ‘ryu’, ‘shaun’, ‘shaun’]

 

Capital Letters come first…

 

Set(nums)

{1, 2, 3, 4, 7, 8}

 

Sets do not preserve order.

 

Set(nums)

{‘ryu’, ‘Apple’, ‘abe’, ‘brian’, ‘shaun’}

 

Ninjas = {‘ryu’: ‘black’, ‘yoshi’: ‘red’, ‘crystal’: ‘black’}

Ninjas.values()

Dict_values([‘black’, ‘red’, ‘black’])

Set(ninjas_values())

{‘red’, ‘black’}

 

Atom:

.py

 

Def belt_count(dictionary):

Belts = list(dictionary.values())

For belt in set(belts):

                Num = belts.count(belt)

                Print(f’There are {num} {belt} belts’)

 

Belt_count(ninja_belts)

 

 

Command Line:
 

 

 

 
Python 3 Tutorial for Beginners #16 - Classes

https://www.youtube.com/watch?v=H--VDcDSHdg&list=PL4cUxeGkcC9idu6GZ8EU_5B6WpKTdYZbK&index=16

 

LOST…

 

name = ‘shaun’

age = 20

nums = [1,2,3,4]

type(name)

<class ‘str’>

 

name.upper()

 

class is a blueprint for how a object behaves

 

 

 

 

Atom

Classes.py

 

Class Planet:

 

                Def __init__(self): # Properities

                                Self.name = ‘Hoth’

Self.radius = 200000

                                Self.gravity = 5.5

                                Self.system = ‘Hoth System’

 

                Def orbit(self): # Method

                                Return f’{self.name is orbiting in the {self.system}}’

 

 

Hoth = Planet()

 

Print(f’Name is: {host.name}’)

Print(f’Radius is: {host.radius}’)

Print(f’Gravity is: {host.gravity}’)

Print(hoth.orbit())

 

 

Command Line

 

Python classes.py

 

 
Python 3 Tutorial for Beginners #17 - The init function

https://www.youtube.com/watch?v=TO1K8_BVCT4&list=PL4cUxeGkcC9idu6GZ8EU_5B6WpKTdYZbK&index=17

 

Atom

Classes.py

 

Class Planet:

 

                Def __init__(self, name, radius, gravity, system):

                                Self.name = name

Self.radius = radius

                                Self.gravity = gravity

                                Self.system = system

 

                Def orbit(self): # Method

                                Return f’{self.name is orbiting in the {self.system}}’

 

 

Hoth = Planet(‘Hoth’, 2000000, 5.5, ‘Hoth System’)

Naboo = Planet(‘Naboo’, 300000, 8, ‘Naboo System’)

 

Print(f’Name is: {hoth.name}’)

Print(f’Radius is: {hoth.radius}’)

Print(f’Gravity is: {hoth.gravity}’)

Print(hoth.orbit())

 

Print(f’Name is: {naboo.name}’)

Print(f’Radius is: {naboo.radius}’)

Print(f’Gravity is: {naboo.gravity}’)

Print(hoth.orbit())

 

Command Line

 

Python classes.py

 

 
Python 3 Tutorial for Beginners #18 - Methods & Attributes

https://www.youtube.com/watch?v=LwFnF9XoEfM&list=PL4cUxeGkcC9idu6GZ8EU_5B6WpKTdYZbK&index=18

 

instance attributes

Instance methods

 

Unique to the instance.

 

Class Planet:

 

                Shape = ‘round’ # class level attributes are the same for all instances

 

@classmethod # decorator

Def commons(cls):

                Return f’All planets are {cls.shape} because of gravity’

 

@staticmethod # decorator

Def spin(speed = ‘2000 miles per hour’):

                Return f’The planet spins and spins at {speed}’

               

 

Planet.shape = round

Naboo.shape = round

 

Planet.commons() = Al planets are round because of gravity

Naboo.commons() = Al planets are round because of gravity

 

Planet.spin(‘a very high speed’) = The planet spins and spins at a very high speed

naboo.spin(‘a very high speed’) = The planet spins and spins at a very high speed

 

 
Python 3 Tutorial for Beginners #19 - Modules & Packages

https://www.youtube.com/watch?v=f26nAmfJggw&list=PL4cUxeGkcC9idu6GZ8EU_5B6WpKTdYZbK&index=19

 

Import Modules,

 

Import Packages; a collection of Modules

 

From (file_name) import (function)

 

From classes import Planet

 

Atom

 

New folder

 

Space/

 

Space/__init__.py

 

To tell that this is a module

 

Space/planet.py

Space/calc.py

 

Classes.py

 

From (package).(file_name) import (function), (function)

 

From space.planet import Planet

From space.calc import planet_mass, planet_vol

 

 

 

 

Python 3 Tutorial for Beginners #20 - Bar Tab Calculator

https://www.youtube.com/watch?v=h4NetyxAhv4&list=PL4cUxeGkcC9idu6GZ8EU_5B6WpKTdYZbK&index=20

 

Atom

 

Project/bar_tab.py

 

Class Tab:

               

                Menu = {

                ‘wine’: 5,

                ‘Beer’: 3,

                ‘soft_drink’: 2,

                ‘chicken’: 10,

                ‘beef’: 15,

                ‘Veggie’: 12,

                ‘desert’: 6

}

Def __init__(self):

                Self.total = 0

                Self.items = []

Def add(self, item):

                Self.items.apend(item)

Self.total += self.menu[item]

                Def print_bill(self, tax, service):

                                Tax = (tax/100) * self.total

                                Service = (service/100) * self.total

                                Total = self.total + tax + service

 

                                For item in self.items:

                                                Print(f’{item:20} £{self.menu[item]}’)

                               

                                Print(f’{“Total”:20} £{total:2f}’)

 

:20 formats, makes it 20 characters long.

 

Command Line

 

Python

From bar_tab import Tab

 

Table1 = Tab()

 

Table1.add(‘soft_drink’)

Table1.add(‘chicken’)

Table1.add(‘desert’)

 

Table1.print_bill(10, 10)

 

=

soft_drink £2

chicken £10

desert £6

Total £21.60
 


 
Python 3 Tutorial for Beginners #21 - List Comprehensions

https://www.youtube.com/watch?v=7G0jqG_kiig&list=PL4cUxeGkcC9idu6GZ8EU_5B6WpKTdYZbK&index=21

 

prizes = [5, 10, 50, 100, 1000]

 

dbl_prizes = []

 

for prize in prizes:

dbl_prizes.append(prize*2)

print(dbl_prizes)

[10, 20, 100, 200, 2000]

 

 

# comprehension method

 

dbl_prizes = [prize*2 for prize in prizes]

print(dbl_prizes)

[10, 20, 100, 200, 2000]

 

# squaring numbers

Nums = [1,2,3,4,5,6,7,8,9,§0]

 

Squared_even_nums = []

For num in nums:

                If (num ** 2) % 2 == 0:

                                Squared_even_nums.append(num ** 2)

Print(Squared_even_nums)

[4,16,36,64,100]

 

# comprehension method

Squared_even_nums = [ num ** 2 for num in mums if (num ** 2) % 2 == 0 ]

 

Print(Squared_even_nums)

[4,16,36,64,100]

 

2 ways of doing the same thing…

 
Python 3 Tutorial for Beginners #22 - Maps

https://www.youtube.com/watch?v=3Da00hgQ834&list=PL4cUxeGkcC9idu6GZ8EU_5B6WpKTdYZbK&index=23

 

from random import shuffle

 

def jumble(word):

                anagram = list(word)

                shuffle(anagram)

return ‘’.join(anagram)

 

 

words = [‘beetroot’, ‘carrots’, ‘potatoes’]

anagrams = []

 

for word in words:

                anagrams.append(jumble(word))

print(anagrams)

 

# map(function, data)

 

Print(list(Map(jumble, words)))

 

# comprehension method

 

Print( [ jumble(word) for word in words ] )
 

Python 3 Tutorial for Beginners #23 - Filters

https://www.youtube.com/watch?v=jPoY--eTG5A&list=PL4cUxeGkcC9idu6GZ8EU_5B6WpKTdYZbK&index=24

 

grades = [‘A’, ‘B’, ‘F’, ‘C’, ‘F’, ‘A’]

 

def remove_fails(grade):

                return grade != ‘F’

 

# filter(testing_function, grades)

 

print(List(filter(remove_fails, grades)))

 

filtered_grades = []

for grade in grades:

                if grade != ‘F’:

                                filtered_grades.apend(grade)

print(filtered_grades)

 

# comprehension method

 

Print([grade for grade in grades if grade != ‘F’])




Python 3 Tutorial for Beginners #24 - Lambdas

https://www.youtube.com/watch?v=3waZGETmzjY&list=PL4cUxeGkcC9idu6GZ8EU_5B6WpKTdYZbK&index=24

 

anonymous functions

 

nums = [1,2,3,4,5,6]

 

def square(n):

                return n * n

 

print(list(map(square, nums)))

 

print(list(map(lambda n: n * n, nums)))


Python 3 Tutorial for Beginners #25 - Decorators

https://www.youtube.com/watch?v=mmiIjmo-GwQ&list=PL4cUxeGkcC9idu6GZ8EU_5B6WpKTdYZbK&index=25

 

LOST

 

@classmethod

@staticmethod

 

Used a lot in Django.

Extends the function BUT doesn’t modify the function

 

 

Def cough_dec(func):

                Def func_wrapper():

                                # code before function

Print(‘*cough*’)

                                Func()

                                # code after function

Print(‘*cough*’)

                Return func_wrapper

 

 

@cough_dec

De question():

                Print(‘can you give me a discount on that?’)

 

Question()
