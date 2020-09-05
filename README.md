# stable_matching_algorithm

The stable matching algorithm seeks to solve the problem of finding a stable match between two sets of equal size
given a list of preferences for each element. 
We can define "matching" and "stable" by the following definitions.
Matching: Mapping from the elements of one set to the elements of another set
Stable: No element A of the first set that prefers an element B of the second set over its current partner
		such that element B prefers element A over its current partner.
