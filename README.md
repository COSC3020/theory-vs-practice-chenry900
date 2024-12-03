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

1.since the run time has constants, when the n is smaller a time complexity of $O(nlogn)$ could perform worse than $n^2$ while large n's would show the opposite.
2.it doesn't take into account the limitations of the system that could delay the program.
3.When dealing with a certain size of code a more specalized code could run better than a general one but the general one would out perform the specalized one if given a different size.

assuming that the tree is balanced you can assume that and that the depth of the tree is 
2^n = 10000 and 2^n = 1000 the 10,000 is only 25% bigger so it should only take 25% more time
to get to the bottom of the tree thus the guess would be 6.25 seconds to get the new answer.
if the tree was unbalanced then worst case you could have a linked list or a few extreamly
long branches that would take more time to traverse you could end up with a search that takes
10x as long so 50 seconds and if the search is inefficent or is more complex it could increase the time even farther.

1.it could have un-nessary recursive calls that take extra time to process.
2.the algoritum might be specalized to move faster for the 1000 size and runs inefficiently at larger n numbers
3.the larger search could have equal elements that cause the resolution of the problem that causes the alorithm to check already checked branches

help recieved googled questions
