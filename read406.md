# Object-Oriented Programming Concepts

# Inheritance

 - different objects have share some common characteristics, object oriented programming allows classes to inherit commonly used state and behavior from other classes.

 - each class is allowed to have one one direct superclass, and each superclass is allowed to have unlimited number of subclasses.
 - subclass:  is derived from another class
 - superclass: The class from which the subclass is derived.

 ### The syntax for creating a subclass:

 
 class MountainBike extends Bicycle {

    // new fields and methods defining 
    // a mountain bike would go here

} 

# Interface

- Blueprint of a class. It has static constants and abstract methods.

- Is a mechanism to achieve abstraction. and it  can be only abstract methods in the Java interface not method body.
- It is used to achieve abstraction and multiple inheritance in Java.
( you can say that interfaces can have abstract methods and variables and  cannot have a method body)

### Example 

interface printable{  
void print();  
}  
class A6 implements printable{  
public void print(){System.out.println("Hello");}  
  
public static void main(String args[]){  
A6 obj = new A6();  
obj.print();  
 }  
}  

` 