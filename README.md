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

it assumes that the code is written efficently so that the growth of size in relative to
time is $O(nlogn). it assumes that the data isperfectly blanced so average is the same and
with how log growth works it would mean that something 10x its size is only a difference of
about 1/3 longer

assuming that the tree is balanced you can assume that and that the depth of the tree is 
2^n = 10000 and 2^n = 1000 the 10,000 is only 25% bigger so it should only take 25% more time
to get to the bottom of the tree thus the guess would be 6.25 seconds to get the new answer.
if the tree was unbalanced then worst case you could have a linked list or a few extreamly
long branches that would take more time to traverse you could end up with a search that takes
10x as long so 50 seconds.

well the tree could not be balanced correctly so one branch could be significantly longer than the others,
the item from the frist test could be near the root of the tree while the second was near the leaf or
it could be how the search looks for the data 
