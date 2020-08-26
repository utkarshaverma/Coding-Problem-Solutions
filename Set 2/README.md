Simple Max Difference : 

Given an array of size n where elements are closing prices of a particular stocks on n days in order, 
find the maximum profit spread of the stock. Profit spread it the difference between the closing price of a day and the closing price on any of the previous days in history. 
If the prices remain flat or are continuously decreasing, return -1.

Sample inputr 1: 
[7,1,2,5]  

    1<7 -> continue;

    2>1 -> 2-1 = 1 : diff

    5>2 -> 5-2 = 3

           5-1 = 4 : maximum diff = output

Sample input 2:
[7,5,2,1]

5<7 , 2<5 , 1<2 -> continuously decreasing : return -1;
    
Solution function in sol2.txt file. Write main function to read data and call function.
