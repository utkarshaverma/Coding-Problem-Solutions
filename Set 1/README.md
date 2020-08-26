Profit Target: 
Given an array of n elements wgere each element gives the yearly profit of a corresponding stock, 
find the max number of distinct pairs (pairs differing in atleast one element) from the array that add up to the given profit target.

				* [1,3,46,1,3,9] sum = 47
					possible pairs are: (1,46), (46,1), (46,1), (1,46) 
							   indexes: [0][2]  [2][0]  [2][3]  [3][2]
						- four times due to repetetion of '1'
						- return only once - (46,1)
						- hence output = 1
				* [5,7,9,13,11,6,6,3,3] sum = 12
					possible pairs are: (5,7), (7,5), (9,3), (9,3), (3,9), (9,3), (6,6), (6,6)
					           indexes: [0][1] [1][0] [2][7] [2][8] [7][2] [8][2] [5][6] [6][5]
					return only distinct - (5,7),(9,3),(6,6)
					- hence output = 3
          
Solution fucntion wriiten in java in sol1.txt file. Write main function to read data.         
