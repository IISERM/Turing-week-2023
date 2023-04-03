

<center> <img src = ".assets/poster.png" >

<p style="margin-bottom: 4em"></p>

<p style="margin-bottom: 4em"></p>

<p style="margin-bottom: 4em"></p>

# <center> Welcome to "A Wannable Hackathon"

<p style="margin-bottom: 4em"></p>



### [ Click here for Rules ](./rules)

<hr color="pink">
<p style="margin-bottom: 2em"></p>


## Problem 1: Worst Sorting Algorithm ever!! `[30 marks]`
<p style="margin-bottom: 2em"></p>


<p>
Imagine yourself a nerd studying in Indian institute of Programming and Coding (IIPC). And you got your first internship in Microogle under Sundar Nadela and was asked to implement your favourite sorting algorithm. But since you are first year student, you are deemed to write a fuzzy and complex logical code whose execution time is damn high. 
</p>
<p style="margin-bottom: 2em"></p>

  <p> Define a function that take the list and return the sorted list (ascending order). </p>

<p> Note: There is euqals weightage for execution time and complex logic used. So, just don't google the worst sorting algorithm (actually check that as well!!). </p>
  
<p style="margin-bottom: 2em"></p>

*** 
<p style="margin-bottom: 2em"></p>

## Problem 2: Preprocessing of Natural Language processing! `[10 marks]`

Now, imagine because of your impeccable code above, you got your promotion to the ML/AI division. And here comes your another task. You are issued a list of character strings and the team need those list whose ${(n-1)}^{th}$ string is a proper substring of $n^{th}$ in a given list of strings and first string in the list would be "IISERM".


Example: `list = ['IISERM' , 'Director' , 'Src' , 'abSrc'] `



So, Write a code (or pseudo-code) to finish the above task and blow the head team's mind. Best of Luck.

Input: `l1 = ['IISERM' , 'Director' , 'Srmc' , 'abSrmc'] `

Output: `True`

Input: `l2 = ['IISERM' , 'Director' , 'Srmc' , 'abSrc'] `

Output: `False`

<hr color="black">
<p style="margin-bottom: 2em"></p>

## Problem 3: Nested list -> Square matrix: `30 marks`

Suppose you have a nested list (a list of a list with varying length). 

Example: `nested_list = [[1, 2, 3], [4, 5], [6]]`

Your job is to submit your code for including the padding of a nested list to make it a square matrix.

Example: `nested_list = [[1, 2, 3], [4, 5,0], [6,0,0]]`

<hr color="black">


## Problem 4: Prime Factors! `[20 marks]`

<p style="margin-bottom: 2em"></p>


Write a algorithm to obtain the list of prime factors of any input number taken from the user.

Input: `420`

Output: `[2,2,3,3,7]`




<p style="margin-bottom: 2em"></p>



<hr color="black">




## Problem 5: Convolution it is!! `30 marks`
<p style="margin-bottom: 2em"></p>

Problem: Let A be an n x m matrix with entries $a_{i,j}$ and let K be a k x k kernel with entries $k_{i,j}$. Define the convolution of A with K to be the n-k+1 x m-k+1 matrix C with entries

$$
c_{i,j} = \sum_{u=1}^k \sum_{v=1}^k a_{i+u-1,j+v-1} k_{u,v}
$$

Write a program that takes in a matrix A and a kernel K as input and returns their convolution C. Assume that A has dimensions greater than or equal to K.

Example:

Input: 
$$
\left(\begin{array}{cc} 
1 & 2 & 3 & 4 & 5 \\ 
6 & 7 & 8 & 9 & 10 \\
11 & 12 & 13 & 14 & 15 \\
16 & 17 & 18 & 19 & 20 \\
21 & 22 & 23 & 24 & 25
\end{array}\right)
$$ 

Kernel: 
$$
\left(\begin{array}{cc} 
1 & 0 & 1\\
0 & 1 & 0\\
1 & 0 & 1
\end{array}\right)
$$



Output:
$$
\left(\begin{array}{cc} 
37 & 50 & 53\\ 
72 & 85 & 88\\
107 & 120 & 123
\end{array}\right)
$$

<p style="margin-bottom: 2em"></p>


***

### Bonus Question: You need to code this! ;) `Special prize for this`





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


#### Your Job is to remember the theme of this hackathon and then, numerically integrate the above equation for the $ f(x) = 2x^2 + sin(x) $ and the value of a is $\pi$. 


{% include mathjax.html %}
