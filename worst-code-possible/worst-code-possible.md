<style>
body {
  font-family: Arial, sans-serif;
  background-color: ;
}

h1, h2, h3 {
  color: white;
}

a {
  color: white;
  text-decoration: none;
}
/* other styling rules */
  .poster {
    max-height: 100vh;
  }
</style>
# <center> Welcome to "Worst-code Possible"
### [ Click here for Rules ](./rules)

<hr color="black">

## Problem 1: Worst Sorting Algorithm ever!! `[30 marks]`
Imagine yourself a nerd studying in Indian institute of Programming and Coding (IIPC). And you got your first internship in Microogle under Sundar Nadela and was asked to implement your favourite sorting algorithm. But since you are first year student, you are deemed to write a fuzzy and complex logical code whose execution time is damn high. 
<hr color="black">

### Define a function that take the list and return the sorted list (ascending order).

### Note: There is euqals weightage for execution time and complex logic used. So, just don't google the worst sorting algorithm (actually check that as well!!).

*** 

## Problem 2: Preprocessing of Natural Language processing! `[20 marks]`

Now, imagine because of your impeccable code above, you got your promotion to the ML/AI division. And here comes your another task. You are issued a list of character strings and the team need those list whose ${(n-1)}^{th}$ string is a proper substring of $n^{th}$ in a given list of strings and first string in the list would be "IISERM".


Example: `list = ['IISERM' , 'Director' , 'Src' , 'abSrc'] `


So, Write a pseudo-code to check if the ${(n-1)}^{th}$ string is a proper substring of $n^{th}$ in a given list of strings and first string in the list would be "IISERM".

<hr color="black">



## Problem 3: Prime Factors! `[20 marks]`
Write a algorithm to obtain the list of prime factors of any input number taken from the user.

Input: `420`

Output: `[2,2,3,3,7]`


<hr color="black">

## Problem 4: Nested list -> Square matrix:

Suppose you have a nested list (a list of a list with varying length). 

Example: `nested_list = [[1, 2, 3], [4, 5], [6]]`

Your job is to submit your code for including the padding of a nested list to make it a square matrix.

Example: `nested_list = [[1, 2, 3], [4, 5,0], [6,0,0]]`





<hr color="black">

## Problem 5: Matrix Multiplication!!

Matrix multiplication can be expensive. 

## Bonus Question: You need to code this! ;) `Special prize for this`
***
## The Dirac Delta Function

The Dirac delta function, denoted by $\delta(x)$, is a mathematical function that is defined as:

$$
\delta(x) = \begin{cases} 
      \infty, & x = 0 \\
      0, & \text{otherwise} 
   \end{cases}
$$

Despite this definition, the Dirac delta function is not actually a function in the usual sense, as it is not well-defined at $x = 0$. Instead, it is a distribution, or generalized function, that is used to model certain physical phenomena.


$$
\int_{-\infty}^{\infty}f(x)\delta(x-a)dx = f(a)
$$

where $f(x)$ is a well-behaved function, and $a$ is a constant.


#### Your Job is to remember the theme of this hackathon and then, numerically integrate the above equation for the $ f(x) = 2x^2 + sin(x)$ and the value of a is $\pi$. 


{% include mathjax.html %}