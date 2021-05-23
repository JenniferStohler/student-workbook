1. What is the purpose of a namespace?

To organize the app's classes.

2. What is the difference between a class and a struct?

Structs are value types and classes are reference types.

3. What is the method that returns an instance of a class, yet it has no return type? 

The void method.


Example 1
abstract class Car
{
  ...
  public virtual string Start()
  {
    return "Vroooom";
  }
}
5. In the example what is the access modifier of the Start() method?

public

6. In the example what is string an indication of?

It is a Type string that refers to Start() and returns "Vroooom".

7. In the example what is abstract preventing?

It's preventing the method from being instantiated.

8. In the example what is the purpose of virtual? 

Virtual allows the method to be overidden/modified.

9. Name four access modifiers:

public
private
protected
internal

10. If you set a class or method to private, what can access it?

Only the type in the class/struct can access it.