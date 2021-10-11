# Project: Book2 Up

## Team
* *Karen Isabel Morgado Castillo A01027446 [CSF]*
* *Ana Paola Minchaca García A01026744 [CSF]*

## Problem description 
Managing inventory is a daunting task. Nowadays there are business that are not quite on track with today's technology and are still using manual inventory management procedures. With this come a lot of inconsistent tracking, innacurate data, overstocking, inventory loss, inefficient processes that can be challenging to overcome. 

## Language
- Elixir
 
## Topics used
1. Functional programming
        
        We are going to use Elixir to solve this problem, as it is a functional language designed to build scalable and maintainable applications.
2. Recursion
        
        Functional languages like elixir rely on recursion, a function is called recursively until a condition is reached that stops the recursive action from continuing. Elixir normally uses recursion for looping over data structures like lists. 
3. Lists
        
        Lists are particularly suitable for functional programming because they go well together with recursion, since they are like linked lists, modification and sharing is pretty easy.
4. File I/O
        
        File I/O is a very important part of any programming language as it allows the language to interact with files on a file system. Reading, writing and modifying the files are part of this. 

## Proposed solution
To solve the problem listed before, our project consist in simulating a bookstore inventory management system, we have seen this scenario being solved in multiple programming languages, in this case we are going to be using elixir as it was one of the languages we saw in class. 

First, we are planning to have a CSV file containing all the books with the following information: SKU, title, author, description, price and the quantity. We are going to open the file, as seen in class, modify it's contents depending on what the option to be done is like, adding a book, modifying books or deleting them.

As for lists, we will use them as a shopping cart, and with the help of recursion we will make the operations on the quantity, like decreasing and calculating the price. 

### Note:
These are the basic functionalities that we are thinking as of now, maybe later we will add some more, depending on the feedback we are receiving and how we manage to work with elixir. 
