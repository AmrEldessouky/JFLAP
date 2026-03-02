# JFLAP
JFLAP Assignment 

# 1. 
What gave me the most trouble was problems number 12 and 8. I avoided the problem number 16 because of its lengthy string s description. I also asked AI how to create a .md file and how to add images to it. 

# 2. 
For NFA 08 I assumed the string 010 would be accepted, so I made a computation tree showing the branching of the computation. The next state I didn't account for when reading the symbol 1 it would go for also the state q3
and not just q2 as well. If the non-determenistic automaton went to state q2 it would be a dead state and it would terminate. So it would determine state q4 and accept once it reads 0. To make sure to avoid this error
I must use my fingers to follow closely the transitions and to also account the self loops. 

# 3. 
There are certain DFA's that are also the same as it's respective NFA, why is that
