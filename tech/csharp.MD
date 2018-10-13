<h1 align="center">
C# Interview Questions & Answers
</h1>
<p align="center">
    <img src="https://github.com/monkey3310/full-stack-interview/blob/master/assets/csharp.png" alt="C# Interview Questions & Answers" height="200"/>
    <i>Logo by Chris McKee</i>
</p>

_Note: Keep in mind that many of these questions are open-ended and could lead to interesting discussions that tell you more about the person's capabilities than a straight answer would._

### 1. What is an Object and a Class? :star:

<details>
    <summary>
        Answer
    </summary>

**Class** is an encapsulation of properties and methods that are used to represent a real-time entity. It is a data structure that brings all the instances together in a single unit.

**Object** in an instance of a Class.

</details>

### 2. What is Managed and Unmanaged code? :star:

<details>
    <summary>
        Answer
    </summary>

**Managed** code is a code being executed by **Common Language Runtime** i.e. all applications based on .NET Platform.
**Unmanaged** code is any code being executed by other frameworks and handled by the .NET platform.

</details>

### 3. What is interface? :star:

<details>
    <summary>
        Answer
    </summary>

It contains is the declaration of methods, properties, and events. Interfaces don't contain any implementations.

</details>

### 4. What are the different types of classes in C#? :star:

<details>
    <summary>
        Answer
    </summary>

- **Partial class** – Allows its members to be divided or shared with multiple .cs files. It is denoted by the keyword `partial`.
- **Sealed class** – It is a class which cannot be inherited. To access the members of a sealed class, we need to create the object of the class. It is denoted by the keyword `sealed`.
- **Abstract class** – It is a class whose object cannot be instantiated. The class can only be inherited. It should contain at least one method. It is denoted by the keyword `abstract`.
- **Static class** – It is a class which does not allow inheritance. The members of the class are also static. It is denoted by the keyword `static`. This keyword tells the compiler to check for any accidental instances of the static class.

</details>

### 5. What are the differences between a Class and a Struct? :star:

<details>
    <summary>
        Answer
    </summary>


| Class                              | Struct                        |
| ---------------------------------- | ----------------------------- |
| Supports Inheritance               | Does not support Inheritance  |
| Pass by reference (reference type) | Pass by Copy (Value type)     |
| Members are private by default     | Members are public by default |

</details>

### 6. What is the difference between Virtual method and Abstract method? :star:

<details>
    <summary>
        Answer
    </summary>


**Virtual method** must always have a default implementation. However, it can be overridden in the derived class, though not mandatory. It can be overridden using `override` keyword. `virtual` modifier is used.

**Abstract method** does not have an implementation. It resides in the abstract class. It is mandatory that the derived class implements the abstract method. An override keyword is not necessary here though it can be used. An abstract method is implicitly a virtual method. `abstract` modifier is used.

</details>

### 7. Namespaces in C#?  :star:

<details>
    <summary>
        Answer
    </summary>


A scope that contains a set of related objects. You can use a namespace to organize code elements and to create globally unique types. The `namespace` keyword is used to declare them.

</details>

### 8. What is “using” statement in C#? :star:

<details>
    <summary>
        Answer
    </summary>


It's an import. It declares that a particular namespace is being used by the program.

</details>

### 9. What are the commonly used I/O Classes? :star:

<details>
    <summary>
        Answer
    </summary>


- `File` – Helps in manipulating a file.
- `StreamWriter` – Used for writing characters to a stream.
- `StreamReader` – Used for reading characters to a stream.
- `StringWriter` – Used for reading a string buffer.
- `StringReader` – Used for writing a string buffer.
- `Path` – Used for performing operations related to path information.

</details>

### 10. What is an Abstract Class? :star:

<details>
    <summary>
        Answer
    </summary>


Class with the `abstract` modifier in class declaration indicate that the class is intended to be only used as a base class of other classes. An instance of the class itself cannot be created. Members marked as abstract, or included in an abstract class, must be implemented by classes that derive from the abstract class.

</details>

### 11. What are Boxing and Unboxing? :star::star:

<details>
    <summary>
        Answer
    </summary>


Conversion between a value and a reference type:

**Boxing:** value -> reference type

**Unboxing:** reference type -> value

</details>

### 12. What is the difference between `continue` and `break` statement? :star:

<details>
    <summary>
        Answer
    </summary>


`break` statement breaks the loop and makes the program exit the loop.
`continue` statement doesn't break the loop, it breaks the current iteration of the loop.

</details>

### 13. What is an Array? :star:

<details>
    <summary>
        Answer
    </summary>


Array are used to store multiple values of the same type. Collection is stored in a contiguous memory location.

```cs
var numbers = new double[10];
var withDefaultValues = new int[4] {1, 2, 3, 4}

var moreThanOneDimension = new int[3,2] { {1, 11}, {2, 21}, {3, 31}} 
```

</details>

### 14. What is a Jagged Array? :star:

<details>
    <summary>
        Answer
    </summary>


Jagged array is an array whose elements are arrays. Array of arrays.

</details>
