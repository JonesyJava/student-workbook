# C# Fundamentals


**1.** What is the purpose of a `namespace`?
<!-- enter you answer in the space below -->
```
A namespace is designed for providing a way to keep one set of names separate from another. The class names declared in one namespace does not conflict with the same class names declared in another.

There is no need to have a namespace. However developer studio expects you to be using a name space. For example, when you choose to add a class to a project developer studio will: Create a file for the class.
```
**2.** What is the difference between a `class` and a `struct`?
<!-- enter you answer in the space below -->
```
Structs are light versions of classes. Structs are value types and can be used to create objects that behave like built-in types.

Structs share many features with classes but with the following limitations as compared to classes.

Struct cannot have a default constructor (a constructor without parameters) or a destructor.
Structs are value types and are copied on assignment.
Structs are value types while classes are reference types.
Structs can be instantiated without using a new operator.
A struct cannot inherit from another struct or class, and it cannot be the base of a class. All structs inherit directly from System.ValueType, which inherits from System.Object.
Struct cannot be a base class. So, Struct types cannot abstract and are always implicitly sealed.
Abstract and sealed modifiers are not allowed and struct member cannot be protected or protected internals.
Function members in a struct cannot be abstract or virtual, and the override modifier is allowed only to the override methods inherited from System.ValueType.
Struct does not allow the instance field declarations to include variable initializers. But, static fields of a struct are allowed to include variable initializers.
A struct can implement interfaces.
A struct can be used as a nullable type and can be assigned a null value.
```
**3.** What is the method that returns an instance of a class, yet it has no return type?
<!-- enter you answer in the space below -->
```
Method Declaration which must be declared to return VOID.
```
## Example 1
```c#
abstract class Car
{
  ...
  public virtual string Start()
  {
    return "Vroooom";
  }
}
```
**5.** In the example what is the access modifier of the `Start()` method?
<!-- enter you answer in the space below -->
```
Public is the access modifier in the `Start()` method. 
```
**6.** In the example what is `string` an indication of?
<!-- enter you answer in the space below -->
```
String is an indication that Start() is a string and will return a string.
```
**7.** In the example what is `abstract` preventing?
<!-- enter you answer in the space below -->
```
An abstract class allows you to create functionality that subclasses can implement or override. An interface only allows you to define functionality, not implement it. And whereas a class can extend only one abstract class, it can take advantage of multiple interfaces.
```
**8.** In the example what is the purpose of `virtual`?
<!-- enter you answer in the space below -->
```
Virtual method is a method that can be redefined in derived classes. In C#, a virtual method has an implementation in a base class as well as derived the class. It is used when a method's basic functionality is the same but sometimes more functionality is needed in the derived class.
```
**9.** Name four access modifiers:
<!-- enter you answer in the space below -->
```
Public : The type or member can be accessed by any other code in the same assembly or another assembly that references it.

Private: The type or member can be accessed only by code in the same class or struct.

Protected: The type or member can be accessed only by code in the same class, or in a class that is derived from that class.

Internal: The type or member can be accessed by any code in the same assembly, but not from another assembly.
```
**10.** If you set a class or method to private, what can access it?
<!-- enter you answer in the space below -->
```
The type or member can be accessed only by code in the same class or struct.
```