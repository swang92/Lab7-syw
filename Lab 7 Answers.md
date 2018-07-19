###Lab 7 Answers###

**Question 1**

We house our recursions in these methods so that we can call on them in other methods. This allows us to keep things "under the hood" because the user who is interacting with these methods (such as passing information to printReverse) doesn't need to know the inner workings of the methods, just the required data and the expected outcome. 


**Question 2**

These methods need arguments because they are being passed information from the method that uses them (e.g. asList passes a node and list to populateList). populateFifo and populateList essentially are the same method, we are just changing the order of how nodes populate in the list. PrintReverse is slightly different because it's combining: 1) print user input in the order it is input 2) reverse printing the entire input when we have noted EOF. 


**Question 3**

printReverse is O(n) because we are searching through the array list that is being populated as the user inputs. The number of times printReverse runs in the else statement is dependent on the number of inputs for this method. The remaining recursion methods populateList and populateFifo are also O(n) because the method called upon itself has to keep running until we run out of inputs (or our List = null). The asList methods are also O(n) because we calling our recursion methods within asList to populate a list and the population depends on the number of Nodes. 


**Question 4**

All the methods can use while loop instead of recursion (we used a while loop for asList population in Lab 5).  