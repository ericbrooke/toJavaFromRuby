##Naming
**Ruby**
 * Use snake_case for symbols, methods, filenames and variables
 * Use CamelCase for classes and modules
 * SCREAMING_SNAKE_CASE for other constants.

**Java**

All variables and method names will be in camel case, constants will be in all caps with underscores, and classes will be in caps case.

##Declaring Varibales
**Ruby**
Dynamically typed, so you do not have to declare the type of the variable
```
 foo = 1
 ```
 
 **Java**
 Is statically typed so you do have to declare the type of the variable
 
```
int foo = 1;
```

##Method Defination 

**Ruby**
```
def foo_name(a, b)
  # stuff
end
```
**Java**
```
public static int fooName(int a, int b) {
  // stuff
}
```
1. public static : modifier.
1. int: return type or void (no return)
1. fooName: name of the method
1. a, b: formal parameters
1. int a, int b: list of parameters

##Inheritance
**Ruby**
```
class ElvenSword < Sword  
  def attack  
    puts "Slash"  
  end  
end 
```

**Java**
```
class ElvenSword extends Sword {

    // new fields and methods defining 
    // a ElvenSword would go here

}
```
##Casting
Convert a variable or object to another "type". For objects, it only works if the other type is part of the inheritance tree.
**Ruby**
```
foo = 2
foo_float = foo.to_f
```
**Java**
```
int foo = 2;
float fooFloat = (float) foo;
```
##Getters and Setters

**Java**
```
class Vehicle {
 int speed = 0;
 int gear = 1;
 
 // Start of getters and setters
  public int getSpeed() {
         return speed;
  }
  public void setSpeed(int s) {
         speed = s;
  }
  public int getGear() {
         return gear;
  }
  public void setGear(int g) {
         gear = g;
  }
}
```
##Interfaces
An interface is a contract between a class and the outside world. When a class implements an interface, it must provide the behavior specified by that interface.
```
public interface IVehicle {
       void changeGear(int newValue);
       void speedUp(int increment);
 }

```
Then the Vehicle class implements the IVehicle interface
```
class Vehicle implements IVehicle { int speed = 0;
 int gear = 1;

 public void changeGear(int newValue) {
        gear = newValue;
 }
 public void speedUp(int increment) {
       speed = speed + increment; 
 }
 void printStates() {
  System.out.println(" speed:" + speed + " gear:" + gear);
 } 
}
```
