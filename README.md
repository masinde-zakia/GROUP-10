# GROUP-10
	
#include<stdio.h>
 
int main() {
   int num1, num2, res;
 
   printf("\nEnter the two numbers : ");
   scanf("%d %d", &num1, &num2);
 
   //Call Function Sum With Two Parameters
   res = sum(num1, num2);
 
   printf("nAddition of two number is : ");
   return (0);
}
 
int sum(int num1, int num2) {
   int num3;
   num3 = num1 + num2;
   return (num3);
}
ABSTRACTION
Abstraction is a technique of hiding unnecessary details from the user. 
The user is only given access to the details that are relevant.
Example of absraction in the function above is <stdio.h>,The header file stdio.h stands for Standard Input Output. 
It has the information related to input/output functions. 

ENCAPSULATION
Encapsulation in Java is a process of wrapping code and data together into a single unit,
for example, a capsule which is mixed of several medicines.
Example of encapsulatio in above is return (num3) because 
it consist of two function which are num1 and num2.

INHERITANCE
Inheritance in Java is a concept that acquires the properties from one class to other classes;
for example, the relationship between father and son. In Java, a class can inherit attributes 
and methods from another class.

POLYMORPHISM
polymorphism refers to the ability of a class to provide different implementations of a method, 
depending on the type of object that is passed to the method. To put it simply, 
polymorphism in Java allows us to perform the same action in many different ways.
