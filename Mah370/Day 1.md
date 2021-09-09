# Modern Algrebra 1 - Day 1

1. Forms of Algebra
    * Numbers: Integers (ℤ) vs. The Real Numbers (ℝ)
    * Vectors
    * Polynomials - Functions
    * Composition - f ∘ g
    * Matrices - AB ≠ BA
1. Ways of using Algebra/Arithmatic
    * R<sub>i</sub> x R<sub>j</sub>
    * Multiplication Tabls
</br>
</br>

---

</br>

> Rotating and flipping toasty

| G | a | b | c | d |
|---|---|---|---|---|
| a | a x b | a x b | a x c | a x d |
| b | b x b | b x b | b x c | b x d |
| c | c x b | c x b | c x c | c x d |
| d | d x b | d x b | d x c | d x d |

| T | R<sub>0</sub> | R<sub>1</sub> | R<sub>2</sub> | R<sub>3</sub> |
|---|---|---|---|---|
| R<sub>0</sub> | R<sub>0</sub> | R<sub>1</sub> | R<sub>2</sub> | R<sub>3</sub> |
| R<sub>1</sub> | R<sub>1</sub> | R<sub>2</sub> | R<sub>3</sub> | R<sub>0</sub> |
| R<sub>2</sub> | R<sub>2</sub> | R<sub>3</sub> | R<sub>0</sub> | R<sub>1</sub> |
| R<sub>3</sub> | R<sub>3</sub> | R<sub>0</sub> | R<sub>1</sub> | R<sub>2</sub> |

`Homework`
| G | R<sub>0</sub> | R<sub>1</sub> | R<sub>2</sub> | R<sub>3</sub> | F |R<sub>1</sub>F |  R<sub>2</sub>F | R<sub>3</sub>F |
|---|---|---|---|---|---|---|---|---|
| R<sub>0</sub> | R<sub>0</sub> | R<sub>1</sub> | R<sub>2</sub> | R<sub>3</sub> | F | R<sub>1</sub>F | R<sub>2</sub>F | R<sub>3</sub>F |
| R<sub>1</sub> | R<sub>1</sub>| | | | | | | |
| R<sub>2</sub> | R<sub>2</sub>| | | | | | | |
| R<sub>3</sub> | R<sub>3</sub>| | | | R<sub>3</sub>F | | | |
| F | F | | | | | | | |
| R<sub>1</sub>F | R<sub>1</sub>F | | | R<sub>1</sub>F | | | | |
| R<sub>2</sub>F | R<sub>2</sub>F| | | | | | | |
| R<sub>3</sub>F | R<sub>4</sub>F| | | | | | | |

`_`
1. Ahead:
    * Group - Set of "numbers" & one operation (* or +)
    * Ring - two operations (+ or *)
        * Ex/context: Clock math / modular arithmetic (%)
            * ℤ<sub>12</sub> = {0, 1, 2, ... , 11}
            * Start over at 12 where 12 = 0
        * ℤ<sub>4</sub> = "ℤ mod 4" : "4 = 0"
        * "Same" and "Isomorphic"

`Group`  
|ℤ<sub>4</sub> , + | 0 | 1 | 2 | 3 |
|---|---|---|---|---|
| 0 | 0 | 1 | 2 | 3 |
| 1 | 1 | 2 | 3 | 0 |
| 2 | 2 | 3 | 0 | 1 |
| 3 | 3 | 0 | 1 | 2 |

`Ring`
|ℤ<sub>4</sub> , * | 0 | 1 | 2 | 3 |
|---|---|---|---|---|
| 0 | 0 | 0 | 0 | 0 |
| 1 | 0 | 1 | 2 | 3 |
| 2 | 0 | 2 | 0 | 2 |
| 3 | 0 | 3 | 2 | 1 |

    
