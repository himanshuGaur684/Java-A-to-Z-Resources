# Bitwise Operator


These operators are used to perform manipulation of individual bits of a number. They can be used with any of the integer types. They are used when performing update and query operations of Binary indexed tree.


* __Bitwise AND ' & '  operator__: returns bit by bit AND of input values.


* __Bitwise OR ' | ' operator__: returns bit by bit OR of input values.

 * __Bitwise XOR ' ^ ' operator__: returns bit by bit XOR of input values.

* __Bitwise Complement ' ~ ' Operator__:
 This is a unary operator which returns the one’s compliment 
 representation of the input value, i.e. with all bits inversed.

## Example

 // Java program to illustrate

// bitwise operators

public class operators {

	public static void main(String[] args) 
	{

		// if int a = 010 
		// Java considers it as octal value 
		// of 8 as number starts with 0. 
		int a = 0x0005; 
		int b = 0x0007; 

		// bitwise and 
		// 0101 & 0111=0101 
		System.out.println("a&b = " + (a & b)); 

		// bitwise and 
		// 0101 | 0111=0111 
		System.out.println("a|b = " + (a | b)); 

		// bitwise xor 
		// 0101 ^ 0111=0010 
		System.out.println("a^b = " + (a ^ b)); 

		// bitwise and 
		// ~0101=1010 
		System.out.println("~a = " + ~a); 

		// can also be combined with 
		// assignment operator to provide shorthand 
		// assignment 
		// a=a&b 
		a &= b; 
		System.out.println("a= " + a); 
	} 
} 

Output:

a&b = 5   
a|b = 7   
a^b = 2   
~a = -6   
a= 5