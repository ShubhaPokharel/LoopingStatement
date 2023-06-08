LOOPS


What is looping statements in java?

  Looping statements are used to repeat the same code multiple times until the condition is failed.Using loops is better than writing the same code multiple times. 

For example, if you want to print a message 10 times, rather than typing the same code 10 times again and again, you can use loop!



Types of Loops:

   1 - for loop

   2 - for each loop

   3 - while loop

   4 - do while loop



For loop:

For loop is a loop that prints data from starting to end. For loop has 3 parts.

a - Initialization

b - Condition

c - Increment / Decrement 
       

          1         2,  5        4, 7
	   
for(initialization; condition; inc/dec)
{

	  3, 6
	  
	logics / body part
}

The initialization is the starting point. The condition is the ending point or where we need to stop. The increment or decrement is how much stepping value. The logic is the code to be executed.
Example:

for( int  i= 0; i <= 10; i++){
	System.out.println(“Hello World”);
}

In the example above, “Hello World” will get printed 10 times. 



For each loop:

For each loop is another looping statement. It does not have condition. It will print print the data from start to end.  It will take all the records from starting to end. 

Example:

int[] number = {100, 200, 300};

for(int num: number){
	System.out.println(num);
}



Break and Continue:
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


What is an array?

Array is a group of elements which are of homogeneous types. Homogeneous means same data types. Array takes the group of elements or characters which are of same data types. It takes the data in index form. The index will always start from 0.

 int[] numbers = {10,20,30,40,50};           // int[] can take multiple values which are int type only

	





