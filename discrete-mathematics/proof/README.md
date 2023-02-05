# Proof
## Proof by induction
There are 3 steps to proof by induction

1. **BASE CASE** : where we show that P(1) is true.
2. **INDUCTION HYPOTHESIS** : we assume that P(k) is true.
3. **INDUCTION STEP** : we show P(k + 1) is also true.

## Example

  Question :

  > S(n) be the sum of the first n positive integers:    S(n) = 1 + 2 + 3 + … + n<br>
  > prove by induction that :   S(n) = 1 + 2 + 3 + … + n = n(n + 1) / 2

  Solution :

    1. BASIS CASE ;

       the basis step, S(1) = 1 = 1(1 + 1) / 2. (TRUE)

    2. INDUCTION HYPOTHESIS ;

       Assume that for n = k, S(k) = k(k + 1) / 2

    3. INDUCTION STEP ;

       show that for n = k + 1

       S(k + 1) = (k + 1)((k+1)+1) / 2 = (k + 1)(k + 2) / 2

       S(k + 1) = 1 + 2 + 3 + … + k + (k + 1)

       S(k + 1) = S(k)+ (k + 1)

       S(k + 1) = k(k + 1) / 2 + (k + 1)

       S(k + 1) = (k(k + 1) + 2(k + 1)) / 2

       S(k + 1) =  (k + 1)(k + 2) / 2

       Hence, the formula holds for S(k + 1)

