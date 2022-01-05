# C# Fundamentals


**1.** What is the purpose of a `namespace`?
<!-- enter you answer in the space below -->
```
to scope what parts you want in your project
```
**2.** What is the difference between a `class` and a `struct`?
<!-- enter you answer in the space below -->
```
structs are value types and class is reference type
```
**3.** What is the method that returns an instance of a class, yet it has no return type?
<!-- enter you answer in the space below -->
```
I think you are refering to return type void which would look like 

public void Coolio()
{

}
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
public? I thnk that is what you are asking, this way anyone who has access to the class can use it
```
**6.** In the example what is `string` an indication of?
<!-- enter you answer in the space below -->
```
it refers to the type of data that will be returned
```
**7.** In the example what is `abstract` preventing?
<!-- enter you answer in the space below -->
```
it sets it up to set rules for what it implements
```
**8.** In the example what is the purpose of `virtual`?
<!-- enter you answer in the space below -->
```
it allows it to be overridden
```
**9.** Name four access modifiers:
<!-- enter you answer in the space below -->
```
private, public, protected, internal
```
**10.** If you set a class or method to private, what can access it?
<!-- enter you answer in the space below -->
```
only things in that class, so no one can import it and use it they have to use a method that calls to it from that class itself
```