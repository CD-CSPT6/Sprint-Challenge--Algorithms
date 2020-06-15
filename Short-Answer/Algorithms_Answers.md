#### Please add your answers to the ***Analysis of  Algorithms*** exercises here.

## Exercise I

a) The runtime is O(n) because the number of operations this while loop will perform is linear to the given information.


b) This runtime is O(n*log(n)). The for loop would run O(n) and the while loop would e running O(log(n)) due to it doubling while it is less than j and incrementing the sum. 


c) This is O(n) because the steps are relative the the amount of given information.

## Exercise II
We need to intake a range of floors in the building and then go through the range of floors looking for where the eggs will start not to break. We can tackle this by dividing the given range in half and then looking to see if the eggs are still breaking at the middle. From there look to see where eggs are breaking and throw away that half and continue the same process to find the perfect number where the eggs won't break. This solution would run in O(log(n)) time. 

