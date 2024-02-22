# CSC229 PAL Session Plan - Week 5

2/22 and 2/23

# Creating Classes and Objects

- Syntax for creating classes in Java

```java
    public class MyClass {
        // Class members and methods go here
    }


public class MyClass: This line declares a new class named MyClass. The public keyword indicates that the class is accessible from other classes.
{}: This curly braces define the scope of the class. Everything related to the class, including its members and methods, is contained within these braces.
```

- Instantiating objects from classes

```java
    MyClass myObject = new MyClass();

MyClass myObject: This line declares a variable named myObject of type MyClass, which is a class we've defined earlier.
new MyClass(): This part of the line creates a new instance of the MyClass class using the new keyword. It calls the class constructor to initialize the object.
=: This assigns the newly created object to the variable myObject.
```

- Access modifiers (public, private, protected)

```java
    public class MyClass {
        public int publicVariable;
        private int privateVariable;
        protected int protectedVariable;

        // Methods can also have access modifiers
        public void publicMethod() {
            // Method implementation
        }

        private void privateMethod() {
            // Method implementation
        }

        protected void protectedMethod() {
            // Method implementation
        }
    }
```

`public int publicVariable;`: This line declares a public integer variable named publicVariable that can be accessed from any class.
`private int privateVariable;`: This line declares a private integer variable named privateVariable that can only be accessed within the same class.
`protected int protectedVariable;`: This line declares a protected integer variable named protectedVariable that can be accessed within the same package or by subclasses.

```java
public void publicMethod() { ... }
This line declares a public method named publicMethod() that can be accessed from any class.

private void privateMethod() { ... }:

This line declares a private method named privateMethod() that can only be accessed within the same class.

protected void protectedMethod() { ... }:

This line declares a protected method named protectedMethod() that can be accessed within the same package or by subclasses.
```

## Class Members and Methods

- Instance variables vs. Class variables

```java
    public class MyClass {
        // Instance variable
        private int instanceVariable;

        // Class variable
        public static int classVariable;
    }

private int instanceVariable;

This line declares a private instance variable named instanceVariable, which is specific to each instance of the class.

public static int classVariable;

This line declares a public static class variable named classVariable, which is shared among all instances of the class.
```

- Methods: Syntax and declaration

```java
    public class MyClass {
        // Method declaration
        public void myMethod() {
            // Method implementation
        }
    }
```

- Accessing class members and methods

```java
    MyClass myObject = new MyClass();
    myObject.myMethod(); // Accessing method
    int instanceVarValue = myObject.instanceVariable;
    // Accessing instance variable
    int classVarValue = MyClass.classVariable;
    // Accessing class variable
```

- Constructors and Overloading
- Constructor basics: Default constructor parameterized constructor

  - Constructor overloading
    The role of constructors in object initialization

    ```java
        public class MyClass {
            private int value;

            // Default constructor
            public MyClass() {
                value = 0;
            }

            // Parameterized constructor
            public MyClass(int val) {
                value = val;
            }
        }
    ```

    ```java
    public class MyClass {
        private int value;

        // Default constructor
        public MyClass() {
            value = 0;
        }

        // Parameterized constructor
        public MyClass(int val) {
            value = val;
        }

        // Constructor overloading
        public MyClass(int val1, int val2) {
            value = val1 + val2;
        }
    }
    ```
