# Need for performance Analysis #
To achieve  user friendliness, modularity, security, maintainability, speed etc performance should be taken care of. Performance of a program is directly proportional to scale. 

Asymptotic analysis : it is analysis of behaviour of a function when it is about to approach infinity or a defined limit value, this can be considered as determining limiting behaviour of a function. 
Asymptotic analysis in algorithms : 
In algorithms asymptotic analysis is done by evaluating input size vs the size/time taken by the algorithm to run. The idea of asymptotic analysis of algorithm is measure of efficiency of a algorithm which is independent of machine performance. 
We can have three cases to analyze an algorithm:
- Worst Case
- Average Case
- Best Case

Worst Case :  In worst case the complexity of algorithm is calculated using upper bound, the constraint which will cause maximum number of operations execution need. 
For eg : a array of “n” elements needs O(n) time complexity because it has to process total n elements. 

Average Case : This case depends on the discrete uniform distribution which is a symmetric probability distribution according to which if there are total n number of values, every value has 1/n probability of occurrence and each value is equally likely to be observed. In this case we must know or predict the mathematical distribution of all inputs.
For eg : In average case if there is a array of size n we will calculate computing time for all n inputs followed by division with sum of total number of input. 

Best Case: Complexity of algorithm in Best case is calculated using the lower bound.
We need to find the case in which minimum number of operations has to be executed. 
For eg : while doing linear search we find the element on the first position. 


# ASYMPTOTIC NOTATIONS #
Asymptotic notations are mathematical tools for representing time complexity of algorithms according to asymptotic analysis. 
Following are three notations mostly used to represent time complexity of algorithms: 
- Θ Notation : theta notation bounds the function from above and lower bounds.
- Big O Notation : bounds function only from upper boundary.
- Ω Notation  : bounds function only from lower bounds. 
