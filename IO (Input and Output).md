# I/O (Input and Output) 
#I/O

## Analogy
Imagine I wanted to show off a bit. I know all my 2's times tables and wanted to prove it to you. Heres the convo:

> 	Me: I can multiply any number times 2 in my head  
> 	  
> 	You: Prove it  
> 	  
> 	Me: Okay, give me a number and i'll multiple it by 2  
> 	  
> 	You: Okay, how about 6  
> 	  
> 	Me: 12, ask me another  
> 	  
> 	You: 19  
> 	  
> 	Me: 38  
>   
> 	You: Wow, your so smart.  

This was an example of I/O. I asked you for some input (the number) and then returned to you the output (2 * number).

This concept is important in computer science as well.

## How it works conceptually 

There are many different ways to get input. Here are a two:

1. Files
2. Console

We are going to focus on the console in this article.

Think of the console as your texting app. You can write some message and also receive some message back.

In this analogy, you are texting the computer, not another person.

## Syntax

### Get input

	std::cin >> n;
	
	 std:: - We must preface the cin (console in) function with std:: because cin is in the standard library 
	 Note: THIS IS NOT REQUIRED IF YOU USE using namespace std;
	
	 cin - Tells the program to wait until we get input from the console
	
	 >> - Tells the program to take what the user entered into the console and put it into the variable on the right
	
	 n - Any variable that will accept/become the input entered by the user (Does not need to be named n)
	

### Send output

	std::cout << n;
	
	 std:: - We must preface the cout (console out) function with std:: because cout is in the Standerd library 
	 Note: THIS IS NOT REQUIRED IF YOU USE using namespace std;
	
	 cout - Tells the program we want to print (display text) to the console
	
	 << - Tells the program where to get the info we want to display from
	
	 n - Any variable or constant (such as a string of text) that we want to display

## Basic Program

### Steps

Start program

1. Ask for number
2. Store/remember number 
3. Respond/Print 2 * number

### Code

``` c++
#include <iostream>


int main(void)
{

	int num;  /* Declare a variable to store user input */

	std:: cin >> num;  /* Get user input */
	std:: cout << 2 * num; /* Respond with 2 * the number */
}
```