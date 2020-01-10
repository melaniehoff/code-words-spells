# Code Words Spells: Variables & Functions in Python & Javascript

![](https://github.com/melaniehoff/code-words-spells/blob/master/1.png)

## Javascript vs. Python
To read a great article on the difference between Javascript and Python, [check here](https://skillcrush.com/2019/03/15/python-vs-javascript/)! 
- My top-level distinction is Javascript is for making dynamic websites. Javascript lives and breathes in _the Browser_. - Python, is way more of an all-purpose programming language for millions of computational uses including on the web (in servers but not in the browser).

## Variables

- variables are named containers that hold information. When we name something we can refer to it later. Naming is powerful. 
- words in laguage are like variables. They are named containers that hold meaning. To name something is declare the existance of the thing we are naming. names for words and variables don't emerge from the ether, they are collectively constructed and reaffirmed by people. what are the social histories of the words you speak?

Example Variables in Python:
```
dog = "woof"
my_fav_number = 7

```

Example Variables in Javascript:
```
var dog = "woof";
var myFavNumber = 7
```

- Notice the quotations for a variable that contains a line of text (variable type is called a string). Notice that for a variable type of number, there are no quations. Why do you think that is?
- Notice that in python vs. there are different naming conventions. snake_case vs. camelCase. Why do you think this is? (hint there's not a clear hard and fast answer, it's really just differnet naming conventions for different languages!)

**Variable types**

Python:
```
dog = "woof"
my_fav_number = 7

type(dog)
type(my_fav_number)
```

Javascript:
```
var dog = "woof";
var myFavNumber = 7;

console.log(typeof dog);

console.log(typeof myFavNumber);

```

## Functions
- A function is a block of reusable code (like a shortcut!) that is used to perform an action. Functions provide modularity for your project and the ability to easily reuse and repurpose code. Technically, any piece of code (from your website to the code that runs Facebook) can be written without using functions but you wouldnt want to do this because your code would then be so long!

- Lanhguages like Python and Javascript gives you many built-in functions like print(), etc. but you can also create your own functions. These functions are called user-defined functions.

Function in Python:
```
dog = "woof"

def print_me( my_var ):
   print (my_var)
   return

print_me(dog)
```

Function in Javascript:
```
var dog = "woof";

function printMe(my_var){
  console.log(my_var);
}

printMe(dog);
```

**If Statements**

Python:

```
dog = "woof"
my_fav_number = 7

if type(dog) == type(my_fav_number):
  print("they are the same data type")
elif:
  print("they are different data types!")
```

Javascript:

```
var dog = "woof";
var myFavNumber = 7;

if (typeof dog == typeof myFavNumber) {
  console.log("they are the SAME data type!");
} else {
  console.log("they are DIFFERENT data types!");
};
```

<blockquote class="twitter-tweet"><p lang="en" dir="ltr">words have power to make things so.<br>code has power to make things so.<br>spells have power to make things so.<br><br>when we write code for ourselves and our friends, code that this is written with care, with intention and with intimacy, this literally the stuff of magic</p>&mdash; ⟴ ↭ ⥉ ⬼ ↯ ↬ (@melanieh0ff) <a href="https://twitter.com/melanieh0ff/status/1215728556346691584?ref_src=twsrc%5Etfw">January 10, 2020</a></blockquote> 


![](https://github.com/melaniehoff/code-words-spells/blob/master/2.png)


