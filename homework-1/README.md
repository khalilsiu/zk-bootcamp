# Homework 1

## Maths Introduction

### 1. Working with the following set of Integers S = {0,1,2,3,4,5,6}

What is 

a) 4 + 4

Answer: (4 + 4) mod 7 = 1

b) 3 x 5

Answer: (3 x 5) mod 7 =  1

c) What is the inverse of 3

Answer: a^-1 = a^p-2 (mod p)

= 3^5 (mod 7)

= 243 mod 7

= 5
### 2. For S = {0,1,2,3,4,5,6}
### Can we consider 'S' and the operation '+' to be a group?

For S to be considered a group, it has to satisfy the following
1. Closure: For all a, b in G, the result of the operation, a + b, is also in G

    This satisfies as all (a + b) mod 7 is in the group

2. Associativity: For all a,b and c in G, (a + b) + c = a + (b + c)
    It satisfies
    For example: 3, 4, 6
    LHS: (3 + 4) mod 7 + 6 mod 7
    = 7 mod 7 + 6 mod 7
    = 6
    RHS: (3 + 6) mod 7 + 4 mod 7
    = 9 mod 7 + 4 mod 7
    = 6

3.  Identity element
    There exists a unique element G, such that a + e = e + a = a
    it satisfies with 0 being the identity element

4. Inverse element
    It satisfies as each element has an inverse element
    For example: (0 + 1) mod 7 = 1 = the identity element

### 3. What is -13 mod 5
Since it is operation is anti-clockwise, -13 mod 5 

= -3 mod 5 

= 2