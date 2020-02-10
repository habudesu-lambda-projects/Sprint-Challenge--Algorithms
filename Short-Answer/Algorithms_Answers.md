#### Please add your answers to the ***Analysis of  Algorithms*** exercises here.

## Exercise I

a) This algorithm runs in linear or O(n) time. You're adding n^2 to a until a is >= n^3. You have to add n^2 n times to get n^3 so the algorithm will always run n times.


b) The algorithm runs in log or O(log(n)) time. J doubles in size in every iteration so n would need to double to force an extra iteration. 


c) This algorithm runs in linear or O(n) time. If you increase bunnies by 1, the number of recursive calls also increases by 1.

## Exercise II

Start with the middle floor. If the egg cracks, check the floor in the midpoint between the middle floor and the bottom floor. If the egg does not crack, check the floor in the midpoint between the middle floor and the top floor. Repeat until you only have one possible floor.

This algorithm runs in log(n) time because it cuts the number of possible answers in half in each iteration.