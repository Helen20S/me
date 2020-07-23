TODO: Reflect on what you learned this week and what is still unclear.
Learnt about Pets and that they can be friendly, if placed in a separate cage to the other pets.
DEFINE VARIABLES.  Why is it important to use list?  Learn Glossary Terms.
All about TRICKS.
Tricks, Slicing, Append and Extend, State, True Values.  Did I miss anything?
SLICING:  for i range 35[]; print ("\n[35:]"[pets[35:]).pets  some_pets = pets[4:10]; some_pets.  Data view button - COOL!.  eg. pets[:len(pets)-3]; eg. pets[2, 3].  OR  pets[1:4].  - ratio building. OR  pets[+2:]  (hedgehog, guppy).  OR  pets[-2].  Would it still recognise a value?
APPEND VS EXTEND.  PREPEND: Planning to Add. But, MORE SO IN COMPUTING: Add (something) to the beginning of something else.  You usually use Append in a LOOP.
COMPUTING: Attach (a piece of date) to the beginning of another.
STATE IN NOTEBOOK and STATE IN COMPUTING.
list 123.  nums = [1, 2, 3].  list abc.  letters = ["a, b, c"].  [].extend (nums).extend(letters).
newlist [].  newlist.extend(nums).  newlist.extend(letters).  newlist.  OR  nums.extend(letters).  nums.
State of notebook is persisted, top to bottom.  Represented by bunch of redefining list in a number list stare of modification process.
nums.append(letters) [1, 2, 3, 'a', 'b', 'c'].  
nums.append(letters). nums. [1, 2, 3, 'a', 'b', 'c'['a', 'b', 'c']'a', 'b', 'c'].
STATE: Preprogrammed.  ? values and variables into computer.
Each cell modifies the whole.
Python Script STATE changes when moving down the line.
ORDER YOU RUN YOUR CODE IN ACTUALLY MATTERS.
TRUE VALUES:   (you can use them as tricks or they can trick you up)
Thing = False.  If thing:.    print("you'll never see me").  Nothing.
Empty String gives you a false value.  ie.  If 0:0 = True.
If 5-4-1:.    print("I good at numbers").   (I was thinking in Reverse, silly ME!)
If []:.    print("hey!!").  Else:    print("nah mate").  nah mate.
If not True:.    print("hey!!").  Else:    print("nah mate").  nah mate.
thing = "hi".  If thing:.    print "Woah, look at me!".  "Woah, look at me!".

AT recording No. 2.    Listing Comprehensions.
Wraped in [] means it's a list comprehension.
["*", "*", "*", "*", "*", ].  [i for i in range(5).  OR  ["*" for i in range(5)].  OR  ["*" for i in range(10)].  OR  
[i for i in range(10) if i%2].
1%4 = 0  False.   To make it even.    [i for i in range(10) if not i%2].  OR  [i for i in range(10) if i%2 == 0].  OR
[i for i in range(0, 10, 2)].

list pets and o
Pull pets with o                        What is the structure of this composition?????

for p in pets               <- What are we missing here?
[p for p in pets]           -> Gives you list.

[pet_name for pet_name in pets if "org" in pet_name]
?
?
?

LAMDAS  (SEE PHOTO)
def get_2x_len(my_string):
    return len(my_string)* 2            map function across to list


INFORMATION MISSING HERE, DON'T FORGET TO CHECK WITH YOUR LECTURE VIDEOS TO SEE IF IT'S CORRECT!!!

Which is the best way of doing it?
BOAST way of doing
TERSE way of doing
MIDDLE way of doing

Count Characters to the String.

df["message_Length"] = df-apply(lamda ros:len(ro.message))


BUILT-IN'S

MAX = Maximum           MIN = Mininmum

When setting up graphs it is useful.  You can chain things up to make a bunch of stuff.

list(zip(range(len(pets)), pets)).  Gives you a range of TUPLES.

ENUMERATE CONCEPT                           Geometry Programming

for index, p in enumerate(pets):
    print(index, pet)

2 things allow you to control more things about it.

Where to put things                         Thinking

GENERATORS                                  For MAPS - waiting for you to call up the next thing.

Hard Core Python.  Python 3 is all about producing generators.

<enumerate at 0 x 18b382aacf0>

next(a)                                     (How to condense a file?)

(0, dog).  (1, cat).  (2, pig).  (3, sheep).                Too much data stored, creating a new generator.

YIELD A VALUE than return a value.  (See photo)

Numbers that increase in 3.                                 (NOT DATA VIEW FILE)


