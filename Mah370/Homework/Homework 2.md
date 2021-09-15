# Modern Algrebra 1 - Homework 2

**1)**

`GCD`

924 = 7*120 + 84 </br>
120 = 1*84 + 36 </br>
_**84 = 2*36 + 12**_ </br>
36 = 3*12 + 0 </br></br>
`Reverse`

84 = 924 - 2*36</br>
36 = 120 - 1*84</br>
12 = 84 - 2*36</br>

12 = 84 - 2(120 = 1*84)</br>
12 = 3*84 - 2*120</br>
12 = 3(924 - 7*120) - 2*120</br>
12 = 3*924 - 23*12</br>
</br>

___

</br>

**2)**

Let a,b be relatively prime and a,b,c be integers.

suppose a|c and b|c

Proof: ab|c means c = ab * j for some integer j.

Since gcd(a,b) = 1 by the GCD by LC Theorm there exists integers s,t such that 1 = as * bt. Hence cas + cbt = c.

Since a|c and b|c then there exists integers e,f such that c=ae and c=bf. Hence c=bfas+aebt.

c = bfas + aebt => c = ab(fs+et) => ab|c

Therefore ab|c by relative prime and GCD by LC Theorm.

</br>

___

**3)**

_a)_ A group is a set G with a binary operation * satisfying 3 properties: `associativity`,`identity`,`inverse`.

_b)_