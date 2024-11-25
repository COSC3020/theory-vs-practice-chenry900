# Theory vs. Practice

- List 3 reasons why asymptotic analysis may be misleading with respect to
  actual performance in practice.

- Suppose finding a particular element in a binary search tree with 1,000
  elements takes 5 seconds. Given what you know about the asymptotic complexity
  of search in a binary search tree, how long would you guess finding the same
  element in a search tree with 10,000 elements takes? Explain your reasoning.

- You measure the time with 10,000 elements and it takes 100 seconds! List 3
  reasons why this could be the case, given that reasoning with the asymptotic
  complexity suggests a different time.

Add your answers to this markdown file.

1.since the run time has constants at low sizes a time complexity of $O(nlogn) could perform
worse than $n^2$ while large would show the opposite.
2.it doesn't take into account the limitations of the system that could delay the program.
3. since data input can vary quite a bit and it assumes average case you can see variation
on the run time even with the same input sizes.

assuming that the tree is balanced you can assume that and that the depth of the tree is 
2^n = 10000 and 2^n = 1000 the 10,000 is only 25% bigger so it should only take 25% more time
to get to the bottom of the tree thus the guess would be 6.25 seconds to get the new answer.
if the tree was unbalanced then worst case you could have a linked list or a few extreamly
long branches that would take more time to traverse you could end up with a search that takes
10x as long so 50 seconds and if the search is inefficent or is more complex it could increase the time even farther.

1.it would indicate that the tree is extreamly imbalanced.
2.it might iindicate an inefficient search algoithm
3.it might be caused by a system limitation

help recieved googled questions
