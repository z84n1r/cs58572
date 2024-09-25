java c
MATH 136: HOMEWORK 3
Due Wednesday, September 25 at 11:59pm.
Remember that this is a math class, so every assertion requires justification (i.e. a proof).
On this homework, we will show that decimal expansions of various irrationals r ∈ R are primitive recursive. We will actually show the stronger and more base-agnostic fact that the map n → ⌊nr⌋ (the Beatty sequence) is primitive recursive. This immediately implies that the decimal expansion is primitive recursive as well, since the k-th decimal digit of r is the ones digit of ⌊10kr⌋.
Problem 1. The decimal expansion of √2
Show that the function N → N defined by n 7→ ⌊n√2⌋ is primitive recursive.
Problem 2. The decimal expansion of e
Recall Euler’s constant e = 2.71828..., which satisfies

Part a. Show that for every n ∈ N, we have

(Hint: Show first that ).
Part b. Show that the function N → N defined by n 7→ ⌊ne⌋ is primitive recursive.
Problem 3. The decimal expansion of π
Recall the alternating series for π:

Part a. Using the standard approximation for alternating series, show that there is a primitive recursive function f : N → Q such tha代 写MATH 136: HOMEWORK 3Web
代做程序编程语言t for all positive n ∈ N, we have |π − f(n)| < 1/n.
(By the standard approximation for alternating series, we mean the fact that if A = a0 − a1 + a2 − a3 + · · · , then |A − (a0 − a1 + a2 − a3 + · · · an−1)| < |an|).
Part b. It is a very nontrivial fact that the irrationality exponent of π is finite. In fact, it is known to be less than 8, which means that for cofinitely many positive integers q, the distance from π to the set  is greater than 1/q8(i.e. for every p ∈ Z, we have |π − p/q| > 1/q8).
Using this, show that the function N → N defined by n 7→ ⌊nπ⌋ is primitive recursive.
(Hint: The only issue with an approximation is that it can end with a string of 9s or 0s, since for instance, you could have a very good approximation of a real that ends in a string of 9s, like 2.4999, when the actual value is something like 2.5000003. So you need to do a minimization like “take the first approximation that doesn’t end in a string of 9s or a string of 0s”. To make this primitive recursive, you need to bound the minimization, which the irrationality exponent can help with.)







         
加QQ：99515681  WX：codinghelp
