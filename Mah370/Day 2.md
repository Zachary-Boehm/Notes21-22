# Modern Algrebra 1 - Day 2
```
The GCD as LC Theorm:
    Given non-zero (positive) integers a, b, there exists integers s,t, such that
    gcd(a,b)=s*a+t*b. Moreover, gcd(a,b) is the least positive linear combination 
    of aθb

    e.g. Have gcd(250,1210)=10
    claim: There are no integers s,t with 5=5*250+t*1210 because 5<10

    Consequence: suppose a,b are positive integers and 1 = 217*a - 392*b.
    What is gcd(a,b)? gcd(a,b) = 1

    Since 1 is the least positive integer.
    *This can be a way to tell when two numbers are relatively prime. (Theoretical)
```

```
Euclid's Lemma: 
    Let p be a prime number (Integer).
    and let a,b be positive integers.

    suppose p|ab, then p|b or p|b or both

    Proof: p|ab means ab=p*q for some integer q.
    consider p+a+divisibility.
    case 1: p|a or case 2: p∤a
    Then we must show p|b.

    If p∤a, what is gcd(p,a)? 1 i.e, pθa are rel. prime
    What divides p? only pθ1, but p∤a.

    By the GCD as LC Theorm, there exist integers s,t such that 1 = s*a + t*p
    multiply both sides by b. 
    b = bsa+btp => b = s*ab + btp => b = s*pq + bt*p => b = p(sq+bt) => p|b
```
