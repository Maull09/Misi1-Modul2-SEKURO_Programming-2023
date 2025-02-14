Bitwise Operator di C
~~~
1.	The & (bitwise AND) in C or C++ takes two numbers as operands and does AND on every bit of two numbers. The result of AND is 1 only if both bits are 1.  
Contoh :
// a = 5(00000101), b = 9(00001001)
   	unsigned char a = 5, b = 9;

The result is 00000001
    	printf("a = %d, b = %d\n", a, b);
    	printf("a&b = %d\n", a & b);

	hasil :

	a = 5, b = 9
	a & b = 1
~~~

~~~
2.	The | (bitwise OR) in C or C++ takes two numbers as operands and does OR on every bit of two numbers. The result of OR is 1 if any of the two bits is 1. 
Contoh :
// a = 5(00000101), b = 9(00001001)
    	unsigned char a = 5, b = 9;

// The result is 00001101
    	printf("a|b = %d\n", a | b);

	hasil :
	a = 5, b = 9
	a | b = 13
~~~

~~~
3.	The ^ (bitwise XOR) in C or C++ takes two numbers as operands and does XOR on every bit of two numbers. The result of XOR is 1 if the two bits are different. 
Contoh :
// a = 5(00000101), b = 9(00001001)
    	unsigned char a = 5, b = 9;

// The result is 00001100
    	printf("a^b = %d\n", a ^ b);
	
	hasil :
	a = 5, b = 9
	a ^ b = 12
~~~

~~~
4.	The << (left shift) in C or C++ takes two numbers, left shifts the bits of the first operand, the second operand decides the number of places to shift. 
Contoh :
// a = 5(00000101), b = 9(00001001)
    	unsigned char a = 5, b = 9;

// The result is 00010010
    	printf("b<<1 = %d\n", b << 1);

	hasil :
	a = 5, b = 9
	b << 1 = 18
~~~

~~~
5.	The >> (right shift) in C or C++ takes two numbers, right shifts the bits of the first operand, the second operand decides the number of places to shift. 
Contoh :
// a = 5(00000101), b = 9(00001001)
    	unsigned char a = 5, b = 9;

// The result is 00000100
    	printf("b>>1 = %d\n", b >> 1);

	hasil :
	a = 5, b = 9
	b >> 1 = 4
~~~

~~~
6.	The ~ (bitwise NOT) in C or C++ takes one number and inverts all bits of it. 
Contoh :
// a = 5(00000101), b = 9(00001001)
    	unsigned char a = 5, b = 9;

// The result is 11111010
    	printf("~a = %d\n", a = ~a);

	hasil :
	a = 5, b = 9
	~a = -6
~~~



