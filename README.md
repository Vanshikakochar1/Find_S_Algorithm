# Find_S_Algorithm
Find S Algorithm for finding the most specific hypothesis based on a given set of training data samples. 

Applications of Machine Learning In Industries 

**Algorithm**: -
1.	Start with the most specific hypothesis. 
h = {ϕ, ϕ, ϕ, ϕ, ϕ, ϕ}
2.	Take the next example and if it is negative, then no changes occur to the hypothesis.
3.	If the example is positive and we find that our initial hypothesis is too specific then we update our current hypothesis to a general condition.
4.	Keep repeating the above steps till all the training examples are complete.
5.	After we have completed all the training examples, we will have the final hypothesis when can use to classify the new examples.

**Important Representation**: 
 
1.	? indicates that any value is acceptable for the attribute.
2.	specify a single required value (e.g., Cold) for the attribute.
3.	Φ indicates that no value is acceptable.
4.	The most general hypothesis is represented by: {?, ?, ?, ?, ?, ?}
5.	The most specific hypothesis is represented by: {ϕ, ϕ, ϕ, ϕ, ϕ, ϕ}
