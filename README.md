# Geeksforgeeks-question
I made use of hashmap to keep count of where am I , for example if i am trversing left part of root node i have decreased horizontal level, and if i have moved to right part 
i have increased the horizontal level. I have done it so that it is easily able to distinguish whether we are working on left side of root or right side of root. 
So I made map of vertical level and arraylist of items which are at this level and after i sorted each arraylist corresponding to  each key of map on the basis of hlevel
so that i can get my answer at 0 th index of my arraylist .
