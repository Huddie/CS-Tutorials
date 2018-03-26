# Variables
Variables are **essential** in computer science.

Definition: A variable is a symbol which represents a given value that is subject to change.

Let’s break that down.

A variable is a **symbol**. A symbol can be the letter _a_, the word _name_ or the phrase _max_Number_.

Which represents a **value**. Let’s pretend I took the symbol _name_ and said _name_ represents Bob. That means for now on, whenever I say _name_ I mean Bob. 

**Subject to change**. Remember how a few seconds ago whenever I said _name_ it meant Bob? Now I’m changing my mind. Whenever I say _name_ I mean Tim. A variable has to be able to change (Hence the name).

Whenever we give a variable a new representation, we call it assignment.

In the example above, I first assigned Bob to _name_ and then assigned Tim to _name_.

### Shipping and Types
So you have a general sense of a variable but maybe we can use an analogy to further that understanding and introduce a new and key concept in variables, types. 

Heres the analogy. Amazon, the company, is looking to be efficient. They ship tons (and tons?) of packages each and every day and therefore the packaging they use is key. They have a _big box_, and _medium box_, a _small box_ and an _envelope_. 

Each package before anything is placed inside of it is empty. Once a package receives its item we consider it occupied. The important thing is that _big boxes_ contain big items, _medium boxes_ contain medium items…etc. 

Now we can hopefully use this knowledge to understand types.

Every programming language comes with its built in types.
Heres a list of a few of the basic ones that all languages (for the most part) share:

1. int - A number
2. char - A single letter
3. string -  A word/sentence
4. bool - True or False

We can think of these as our boxes. You cannot put a small item in a _big box_ and you cannot put a number into a string. You can only put a small item into a small box or a number into an int (short for integer). 

What if we want to change the item inside the box? Easy, take one item out, put a new one (of the same size) inside.

What if we want to change a variable? Easy, switch the old with a new one **of the same type**.

## Syntax
The format to **declaring** a new variable is like this:

`type name = value;`

type - The type of the variable (int, char, string … ) 
name - The name of the variable (a, name, maxNumber … )
value - The value (the item) you want to store inside the variable

Heres an example:

`int number = 5;`

And another

`int myWeight = 170`

Now I’ve been working out a bit and so I lost some weight. I now weight 165 pounds. Here’s how to change my weight.

`myWeight = 165`

**NOTICE: You only declare the type (int) the first time you create the variable. After that, the program will remember it on its own.** 






