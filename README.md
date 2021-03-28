# Pascals-Triangle
Creating a pascals triangle using c++

# what is a pascal triangle
Pascal’s triangle, in algebra, a triangular arrangement of numbers that gives the coefficients in the expansion of any binomial expression, such as (x + y)n.
  Below shown is a pascal triangle of 5 rows:
  
  1
  
  11
  
  121
  
  1331
  
  14641
  
  We are trying to construct it using cpp.
  ## code in cpp
  ``` int fact(int n)
{
	int factorial=1;
	for(int i=2;i<=n;i++)
	{
		factorial=factorial*i;
	}
	return factorial;
} 
```
this is the funtion return the factorial of the number passed in fact.
The main function consist of two loops.
1)for loop for accessing index in row.
2)nested for loop for accessing the index for column in given row.
3)the  formula for calculating the number of pascal triangle at desired position.
```
fact(i)/(fact(j)*fact(i-j))
 ```
 
 The input needed is n=no.of rows of the pascal triangle and it gives to the triangle.
 
 
 
 ***Thank You***
