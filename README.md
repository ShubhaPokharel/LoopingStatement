# LOOPS


# What is looping statements in java?

  Looping statements are used to repeat the same code multiple times until the condition is failed. Using loops is better than writing the same code multiple times. 

For example, if you want to print a message 10 times, rather than typing the same code 10 times again and again, you can use loop!



Types of Loops:

   1 - for loop

   2 - for each loop

   3 - while loop

   4 - do while loop



# For loop:

For loop is a loop that prints data from starting to end. For loop has 3 parts.

a - Initialization

b - Condition

c - Increment / Decrement 
       

          1         2,  5        4, 7
	   
for(initialization; condition; inc/dec)
{
	  
	logics / body part

              3, 6
}

The initialization is the starting point. The condition is the ending point or where we need to stop. The increment or decrement is how much stepping value. The logic to be executed inside the curley braces is called body part.
Example:

for( int  i= 0; i <= 10; i++){
	System.out.println(“Hello World”);
}

In the example above, “Hello World” will get printed 10 times.


# .length method():
.length() is used to take all the elements( increasing or decreasing). Java int class has provided this method. It is good to use because we dont need to worry about the size of the array. The loop will repeat until the condition fails.
Example:

int num = 200;

for(int i = 0; i <= num.length; i++){

	System.out.println("Shubha!");

}

Note: If we want to get the specific index of an array, you will use the index number in square brackets.

Example:

number[4]

# For each loop:

For each loop is another looping statement. It does not have condition. It will print print the data from start to end.  It will take all the records from starting to end. 



Example:

int[] number = {100, 200, 300};

for(int num: number){
	System.out.println(num);
}

# For loop vs For each loop:

For loop is used if you want to print a specific range. For example between one to one hundred, you can go from 45 - 89 if you use the for loop. 45 -
89 is a specific range.

For each loop is condition based. It is used to print the data from starting to ending value. It is also used to print the data from arrays.

# Break and Continue:

  We can use break and continue in all loops. We use break to stop the loop, but continue is used to skip the particular iteration(loop).

Example using break:

 Class Test{
 
	public static void main(String[] args){
	
		for(int i = 0; i <= 10; i++){
		
			if(i == 5){
			
				break;    // Once the loop reaches number 5, it will stop the loop and it will not go more than 5
				
			}
			
			System.out.println(i);
			
		}
		

	}
	

}


Example using continue:

Class Test{

	public static void main(String[] args){
	
		for(int i = 0; i <= 10; i++){
		
			if(i == 3){
			
				continue;         // Once the loop reaches 3, it will skip 3 but it will keep printing until it reaches 10
				
			}
			
			System.out.println(i);
			
		}
		

	}
	

}

# Unreachable Statement and Infinite Loop:

If we dont apply any condition to the for loop we will get true condition by default. The loop will run forever. 

To make it stop in the terminal we use ctrl + c.

Example 1:

        no condition
	
for(int i = 0; ; i++){         

	System.out.println(i);
	
}

Example 2:

This is unreachable! We cannot print Hello World beause we have no condition in the for loop.

for(int i = 0; true ; i++){

	System.out.println(i);
	
}
System.out.println("Hello World");   //This line 145 is unreachable

So, unreachable statement is when the control cannot reach an area. The difference between an unreachable statement and an infinite loop is that an

infinite loop runs forever and an unreachable statement is we have an infinite loop but we have code outside of that loop. Because of true condition

the loop always iterates infinite times and outside the loop code is not executed which is unreachable.

# What is an array?

Array is a group of elements which are of homogeneous types. Homogeneous means same data types. Array takes the group of elements or characters which are of same data types. It takes the data in index form. The index will always start from 0.

 int[] numbers = {10,20,30,40,50};           // int[] can take multiple values which are int type only

	





