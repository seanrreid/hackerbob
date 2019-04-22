# Bob Knows Basic

## Fighting demo(gorgon)dogs in Python

Bob Newby (_get it? "newbie!"_) used BASIC to find the four-digit security code to "hack" into the Hawkins' lab computer systems. 

The code is comprised of four different `for` loops. Each loops checks a digit of the combination. 

The four loops are:
* `loop i`
* `loop j`
* `loop k`
* `loop l`

The each do the following:

* `loop i` will check each digit from 0-9 until it finds a match for the first digit.
* `loop j` will do the same for the second digit.
* `loop k` will do the same for the third digit.
* `loop l` will do the same for the fourth digits.

(explanation cribbed from: https://www.reddit.com/r/geek/comments/79pxs5/stranger_things_basic_code_rewritten_in_python/dp49zky)

----

## How do I help Bob???

* The code we are editing is in the `src/` directory. 
* Images of Bob's BASIC code are in the `assets/` directory.
* We're going to edit the code to find the proper access combination!

### The example on its own is fairly silly. 

The nested FOR loops just make sure you entered four digits, 0-9. 
THEN, that four digit password is compared to a password in a function we don't see.S

We want to "brute force" password check. So, we're going to change this a
lot!

See task.md for instructions on the process


#### FORKED BY: Sean Reid on April 22nd 2019