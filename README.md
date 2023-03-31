# Assignment 2
1. Given a string `a` and a string `b`, return `true` if `a` is an anagram of `b`. That is, can you reorder the characters of `a` to get `b` or vice-versa?
	* Solve the problem in O(n^2) time.
	* Solve the problem in O(nlogn) time.
	* Solve the problem in O(n) time.
	* Examples:
		* `fried` and `fired` returns `true`.
		* `cheese` and `cheers` returns `false`.
		* `dormitory` and `dirty room` returns `true`.
2. Given an integer, x, and an array of integers, find two indices of the array which correspond to elemenths that add up to x. You are guaranteed that there will be an answer. 
	* Solve the problem in O(n^2) time.
	* Solve the problem in O(n) time.
	* Examples:
		* `[3, 5, 4, 16, 6]` and `10` returns `[2,4]`.
		* `[5, 10, 15, 20, 25, 30, 35]` and `55` returns `[4,5]`.
3. Given an integer array, duplicates are present in it in a way that all duplicates appear an even number of times except one which appears an odd number of times. Find that odd appearing element in linear time and without using any extra memory.
	* Examples:
		* `[1, 2, 3, 4, 5, 4, 3, 2, 1]` returns `5`.
		* `[60,5,60,4,5,60,4]` returns `60`. 
4. Parts of each array may or may not have a section that when added together has a sum of 0. Return true if it does have a section that adds to 0 and false if not.
 	* Examples:
 		* `[3, 7, 8, -4, 5, -3, -5, -2, 2, 2, 5, -6]` returns `true`.
 		* `[-2, 5, 6, 1, -3, 4, -1, 8, -7, -4]` returns `false`.
5. Return all pairs of integers that are reverses of each other from an array. Reverse pairs are defined as containing the same values at opposite indices, for example (3,9) and (9,3)
	* Examples:
		* `[[1,3],[8,3],[3,2],[2,3],[5,6],[3,1]]` returns `[[1,3],[3,1],[3,2],[2,3]]`
		* `[[1,3],[2,4],[3,5],[5,2],[2,4],[2,3],[3,1]]` returns `[[1,3],[3,1]]`
6. Given an unsorted array, reorder the array so that all occurrences of the same value are together. Clusters of elements should appear in the order that they are first seen in the array.
	* Examples:
		* `[2,5,1,2,3,3,1,5]` returns `[2,2,5,5,1,1,3,3]`.
		* `[5,4,5,5,3,4,8]` returns `[5,5,5,4,4,3,8]`.
7. Given a string `a` and a string `b`, return `true` if you can replace all occurrences of each character in `a` with another character to get `b`. Return `false` otherwise.
	* Examples: 
		* `WCGW` and `ABCA` returns `true`.
		* `WCGW` and `AABC` returns `false`.
