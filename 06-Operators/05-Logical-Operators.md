# Logical Operators

These operators are used to perform “logical AND” and “logical OR” operation, i.e. the function similar to AND gate and OR gate in digital electronics. One thing to keep in mind is the second condition is not evaluated if the first one is false, i.e. it has a short-circuiting effect. Used extensively to test for several conditions for making a decision.

Conditional operators are-

&&, Logical AND : returns true when both conditions are true.
||, Logical OR : returns true if at least one condition is true.

## Example:

// Java program to illustrate 
// logical operators 

import java.util.*; 

public class operators {   

	public static void main(String[] args) 
	{

		String x = "Sher"; 
		String y = "Locked"; 

		Scanner s = new Scanner(System.in); 
		System.out.print("Enter username:"); 
		String uuid = s.next(); 
		System.out.print("Enter password:"); 
		String upwd = s.next(); 

		// Check if user-name and password match or not. 
		if ((uuid.equals(x) && upwd.equals(y)) 
			|| (uuid.equals(y) && upwd.equals(x))) { 
			System.out.println("Welcome user."); 
		} 
		else { 
			System.out.println("Wrong uid or password"); 
		} 
	} 
} 

## Output:

Enter username:Sher   
Enter password:Locked   
Welcome user.

