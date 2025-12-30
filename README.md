# java-interview-questions

Frequently asked Java Interview questions

### Table of Contents

<!-- TOC_START -->
| No. | Questions |
| --- | --------- |
| 1 | [What are the differences between JVM, JRE and JDK?](#what-are-the-differences-between-jvm-jre-and-jdk) |
| 2 | [Why Java is platform-independent language](#why-java-is-platform-independent-language) |
| 3 | [How does JVM works](#how-does-jvm-works) |
| 4 | [What are the main features of Java](#what-are-the-main-features-of-java) |
| 5 | [What is public static void main?](#what-is-public-static-void-main) |
| 6 | [What is string constant pool](#what-is-string-constant-pool) |
| 7 | [Why strings are immutable](#why-strings-are-immutable) |
| 8 | [What is the difference between StringBuffer and StringBuilder](#what-is-the-difference-between-stringbuffer-and-stringbuilder) |
| 9 | [What is the importance of hashCode() and equals() methods](#what-is-the-importance-of-hashcode-and-equals-methods) |
| 10 | [What is the difference between checked and unchecked expceptions](#what-is-the-difference-between-checked-and-unchecked-expceptions) |
| 11 | [What are wrapper classes](#what-are-wrapper-classes) |
| 12 | [Why java is not pure object oriented language](#why-java-is-not-pure-object-oriented-language) |
| 13 | [What is the difference between abstract class and interface](#what-is-the-difference-between-abstract-class-and-interface) |
| 14 | [What are marker interfaces](#what-are-marker-interfaces) |
| 15 | [What are collections in Java?](#what-are-collections-in-java) |
| 16 | [What are the differences between arraylist and vector?](#what-are-the-differences-between-arraylist-and-vector) |
| 17 | [What is finalize method? How do you override it?](#what-is-finalize-method-how-do-you-override-it) |
| 18 | [What Is the Difference Between the Comparable and Comparator Interfaces](#what-is-the-difference-between-the-comparable-and-comparator-interfaces) |
| 19 | [What Is an inner class](#what-is-an-inner-class) |
| 20 | [What is the difference between final, finally, and finalize() in Java?](#what-is-the-difference-between-final-finally-and-finalize-in-java) |
| 21 | [What is the difference between '==' and equals() method?](#what-is-the-difference-between--and-equals-method) |
| 22 | [What is method overloading and method overriding?](#what-is-method-overloading-and-method-overriding) |
| 23 | [What is the difference between HashMap and Hashtable?](#what-is-the-difference-between-hashmap-and-hashtable) |
| 24 | [What is the difference between ArrayList and LinkedList?](#what-is-the-difference-between-arraylist-and-linkedlist) |
| 25 | [What is Java Reflection API?](#what-is-java-reflection-api) |
| 26 | [What are the different types of memory areas allocated by JVM?](#what-are-the-different-types-of-memory-areas-allocated-by-jvm) |
| 27 | [What is the difference between throw and throws?](#what-is-the-difference-between-throw-and-throws) |
| 28 | [What is a singleton class and how to create one?](#what-is-a-singleton-class-and-how-to-create-one) |
| 29 | [What are Java 8 Stream API features?](#what-are-java-8-stream-api-features) |
| 30 | [What is the difference between fail-fast and fail-safe iterators?](#what-is-the-difference-between-fail-fast-and-fail-safe-iterators) |
| 31 | [What is the difference between process and thread?](#what-is-the-difference-between-process-and-thread) |
| 32 | [What are the different ways to create a thread in Java?](#what-are-the-different-ways-to-create-a-thread-in-java) |
| 33 | [What is synchronization in Java?](#what-is-synchronization-in-java) |
| 34 | [What is deadlock and how to avoid it?](#what-is-deadlock-and-how-to-avoid-it) |
| 35 | [What is the volatile keyword in Java?](#what-is-the-volatile-keyword-in-java) |
| 36 | [What is the transient keyword in Java?](#what-is-the-transient-keyword-in-java) |
| 37 | [What is serialization and deserialization?](#what-is-serialization-and-deserialization) |
| 38 | [What are functional interfaces in Java?](#what-are-functional-interfaces-in-java) |
| 39 | [What are lambda expressions in Java?](#what-are-lambda-expressions-in-java) |
| 40 | [What is Optional class in Java 8?](#what-is-optional-class-in-java-8) |
| 41 | [What is the difference between Collection and Collections?](#what-is-the-difference-between-collection-and-collections) |
| 42 | [What is the difference between Set and List?](#what-is-the-difference-between-set-and-list) |
| 43 | [What is the difference between HashSet and TreeSet?](#what-is-the-difference-between-hashset-and-treeset) |
| 44 | [What is the diamond problem in Java?](#what-is-the-diamond-problem-in-java) |
| 45 | [What is dependency injection?](#what-is-dependency-injection) |
| 46 | [What is the difference between shallow copy and deep copy?](#what-is-the-difference-between-shallow-copy-and-deep-copy) |
| 47 | [What are design patterns in Java?](#what-are-design-patterns-in-java) |
| 48 | [What is the factory design pattern?](#what-is-the-factory-design-pattern) |
| 49 | [What is the builder design pattern?](#what-is-the-builder-design-pattern) |
| 50 | [What is the difference between Heap and Stack memory?](#what-is-the-difference-between-heap-and-stack-memory) |
| 51 | [What is garbage collection in Java?](#what-is-garbage-collection-in-java) |
| 52 | [What are the different types of garbage collectors in Java?](#what-are-the-different-types-of-garbage-collectors-in-java) |
| 53 | [What is the difference between wait() and sleep() methods?](#what-is-the-difference-between-wait-and-sleep-methods) |
| 54 | [What is the difference between notify() and notifyAll()?](#what-is-the-difference-between-notify-and-notifyall) |
| 55 | [What is an immutable class and how to create one?](#what-is-an-immutable-class-and-how-to-create-one) |
| 56 | [What is the difference between String, StringBuilder, and StringBuffer?](#what-is-the-difference-between-string-stringbuilder-and-stringbuffer) |
| 57 | [What is the difference between static and instance variables?](#what-is-the-difference-between-static-and-instance-variables) |
| 58 | [What is the purpose of the super keyword?](#what-is-the-purpose-of-the-super-keyword) |
| 59 | [What is the purpose of the this keyword?](#what-is-the-purpose-of-the-this-keyword) |
| 60 | [What are generics in Java?](#what-are-generics-in-java) |
| 61 | [What is type erasure in Java generics?](#what-is-type-erasure-in-java-generics) |
<!-- TOC_END -->

<!-- QUESTIONS_START -->

1. ### What are the differences between JVM, JRE and JDK?

   The main differences between JVM, JRE and JDK are listed below,

   **JVM:** Java Virtual Machine(JVM) is an abstract machine that provides a runtime environment for the execution of Java ByteCode. i.e, It is part of Java Runtime Environment(JRE) and responsible for converting bytecode into machine-readable code. JVM is platform dependent but it interprets the bytecode which is platform independent. As a result, Java applications to run on different platforms and operating systems.

   **JRE:** Java Runtime Environment (JRE) is an installation package that provides Java Virtual Machine (JVM), class libraries and other components to run the Java program or application on any machine.

   **JDK:** Java Development Kit (JDK) is a software development kit used to develop and execute Java programs. It includes tools for developing, monitoring and debugging java programs, along with JRE to execute those respective programs.

   The pictorial representation of these three components looks as follows,

   <img src="images/JVM_JRE_JDK.png" width="400" height="400" />

   **[⬆ Back to Top](#table-of-contents)**

2. ### Why Java is platform-independent language

   Java is platform-independent language because java programs are compiled to a bytecode that can be run on any device or OS which has a Java Virtual Machine(JVM). This is possible due to JVM's "Write Once, Run Anywhere"(WORA) capability. Due to this reason, you can write a Java program on one platform such as Windows machine and then run it on a different platform such as macOS or Linux machine without making any modifications to the code.

   Below diagram explains the platform independence feature of Java,

   ![Screenshot](images/JavaIndependent.png)

   **[⬆ Back to Top](#table-of-contents)**

3. ### How does JVM works

   JVM(Java Virtual Machine) is an abstract runtime engine to run java applications. It is part of Java Runtime Environment(JRE) to execute the bytecode generated by java compilers. JVM brings WORA(Write Once Read Anywhere) behavior in which you can write java program on one system and expected to run on any java enabled systems without any modifications. Upon compiling .java file to .class file(contains byte code), .class file goes into several steps described by JVM.

   JVM consists of three main components:

   1. Class Loader subsystem
   2. Runtime data area/ memory area
   3. Execution engine

   Let's understand the JVM architecture which includes the above three components,

   ![Screenshot](images/JVMArchitecture.png)

   1. **Class Loader Subsystem:** The class loaders are responsible to load the class files dynamically into JVM during the runtime. The first class that loaded into the memory is usually the class that contains `main` method.This subsystem performs three main activities.

      1. **Loading:** As part of this step, the class loader will read the .class file and generate the corresponding bytecode. The following important information of the class file will be saved in method area of JVM.

         1. The Fully Qualified Class Name(FQCN) of the loaded class.
         2. Immediate parent class.
         3. Variables, method and modifier information
         4. Whether .class is related to Class, Interface or Enum.

         JVM also creates an object of **Class** type(available from **java.lang** package) to represent the file in the heap memory. But it will be created only on the very first time when the class file is loaded into JVM. This object is helpful for the developers to get class level information.

      2. **Linking:** Linking is the process of taking a class or interface and combining it into the runtime state of the Java virtual machine, preparing it for execution. It involves the following steps:

         1. **Verification:** This phase ensure the correctness of `.class` file by checking whether the file is properly formatted or not, and the code generated by a valid compiler or not. If the validation is failed, you will receive `java.lang.VerifyError` through **ByteCodeVerifier**.

         2. **Preparation:** In this step, JVM allocates memory for all static variables within classes/interfaces and assign them with default values.

         3. **Resolution:** In this step, all symbolic references to classes or interfaces are replaced with their actual memory locations. This transformation is known as **Dynamic Linking**.

      3. **Initialization:** This is the last phase of class loading, where all static variables are replaced with their original values and static block gets executed.

   There are three built-in classloaders available in Java:

   1. **Bootstrap ClassLoader:** This is a root class loader and typically represented as null. It loads the core java libraries located in <JAVA_HOME>/jmods folder like `java.lang`, `java.util` etc. This class loader is written in native code unlike other class loaders.

   2. **Platform ClassLoader:** This class loader is responsible for loading platform classes such as Java SE platform APIs, their implementation classes and JDK-specific run-time classes. For example, the platform classes such as `java.net.http`, `java.sql`, `org.graalvm.compile`(JDK Specific).

   3. **System/Application classLoader:** This class loader is responsible for loading all the classes configured from the classpath. The classpath can contain classes from directories, JAR files etc.

   The above class loaders follows a class loader hierarchy ensuring a delegation mechanism. That means, if the class is loaded and its not found by application classloader, the request is delegated upwards to the platform application class loader. But even it is not found by platform class loader then further delegate upwards to Bootstrap class loader.

   **Note:** Apart from the above built-in class loaders, you can also create your own user defined class loader for ensuring application independence. For example, Tomcat webserver use this approach(WebAppClassLoader) to ensure that different web applications to load and isolate classes/jars.

   2. **Runtime data area/ memory area:**

      The runtime data areas are mainly divided into five components,

      1. **Method:** The method area stores below class level information,

         1. ClassLoader reference
         2. Runtime constant pool
         3. Field data such as name, type, modifiers, attributes etc of each field.
         4. Method data such as name, return type, modifiers, attributes, parameter types etc of each field.
         5. Constructor data such as parameter types and their order for each constructor.

      This is a shared resource and only one method area is available per JVM.

      2. **Heap:** This is the runtime data area in which all the objects and their respective instance variables are stored. The heap is created upon JVM startup and there is only one heap per JVM.

      3. **Stack:** Each thread which is created in JVM, a separate runtime-stack is also created at the same time. The local variables, method calls and intermediate results are stored in this stack area. But if the thread requires a larger stack size than what is available, JVM throws `StackOverflow` error.

      For each method call, a stack frame is created in the stack memory area and it is going to be destroyed upon method execution gets completed. Each stack frame is further divided into three sections.

      1. **Local variables:** For each frame, all the local variables and their values are stored in an array format.
      2. **Operand stack:** In each frame, the variables and operators required for mathematical operations are stored in LIFO stack.
      3. **Frame data:** This area holds all symbolic references related to constant pool resolution and method returned data. It is also used to store a reference to the exception table which has all the information related to catch block in case of exceptions.

      **Note:** Stack area is not a shared resource.

      4. **PC Registers:** JVM supports multiple threads at the same time and each thread has separate PC registers. These registers are used to store address of the currently executed JVM instruction. After completion of current instruction, PC register is going to be updated with next instruction.

      5. **Native method stack:** This stack is used to hold the information related to native methods written in C, C++ and Assembly.

   3. **Execution engine:** The execution engine is responsible for executing the bytecode that is loaded into the JVM. It communicates with various runtime data memories of JVM during the execution. Once the program is finished executing, the memory in the runtime data area will be released.

      It contains three main components for executing the class files.

      1. **Interpreter:** The interpreter reads and executes the bytecode instructions line by line to convert into respective machine language instructions. The main advantage of interpreter is that it is very quick to load and execute the code in a faster pace. But whenever it executes the same code blocks again and again, the interpreter executes repeatedly. So the interpreter cannot be optimized the runtime in case of repeated code execution.

      2. **JIT compiler:** Just-In-Time Compiler(JIT Compiler) is introduced to overcome the disadvantages of interpreter, especially with repeated code execution. JIT compiler can remember the repeated code block segments and they will stored as native code in the cache. Whenever JIT compiler reads the same code block again, it will use the native code stored in the cache.

      JIT compiler has further divided into the following components,

      1. **Intermediate Code Generator:** It generates intermediate code.
      2. **Code Optimizer:** It optimizes the intermediate code for better performance.
      3. **Target Code Generator:** It converts intermediate code into native machine code.
      4. **Profiler:** This is used to identify Hotspots(i.e, repeatedly executing methods) and replace hotspots with respective native code.

      5. **Garbage Collector:** Garbage Collector(GC) is responsible to collect and remove unreferenced objects from the heap area. This memory management feature is used to reclaim the unused memory and makes free space for newer objects. This happens in two phases:

         1. **Mark:** In this step, GC identifies the unused objects in memory
         2. **Sweep:** As part of this step, GC removes the objects identified in the previous phase.

   4. **Java Native Interface (JNI) :** JNI is used as a bridge between java method calls and native libraries written in C, C++ etc. Sometimes it is required to invoke native code for specific underlined hardeware.
   5. **Native Method Libraries :** These are collection of native libraries(C/C++/Assembly) which are required by execution engine. These libraries loaded through JNI and represented in the form of `.dll` or `.so` files.

   **[⬆ Back to Top](#table-of-contents)**

4. ### What are the main features of Java

   Java has many important features which makes it unique among the popular programming languages. Some of those features are:

   1. **Simple:** Java is a simple programming language and easy to understand without any complexities unlike in the prior programming languages.
      Some of the reasons for simplicity are: 1. It is based on C++ which makes it easy for new developers to learn it quickly. 2. Java doens't support pointers(unlike C or C++) considering its complexity and security vulnerabilities. Also, operator overloading doesn't exist in Java. 3. There is no need to remove unreferenced objects because it will be taken care by Automatic Garbage Collection.

   2. **Object-oriented:** Java is an Object Oriented programming(OOPS) language, which means everything in Java is represented with different types of classes and objects. This OOPS is a methodology that simplifies software development and maintenance by following the below features.

      1. Abstraction
      2. Encapsulation
      3. Inheritance
      4. Polymorphism

   3. **Portable:** Java is portable because the bytecode generated on one machine can be taken to any platform for the execution.

   4. **Platform Independent:** The java compiler converts the source code to bytecode and then JVM executes the bytecode to produce the output. If you compile a java program on specific operating system(let's say Windows), it can run on any other platform(Windows, Linux or Mac) with that platform specific JVM. This is the reason why we call Java as a platform-independent language.

   5. **Robust:** Java is robust with many safe guards to ensure reliable code. It has the below safe guards,

      1. It is capable of handling unexpected termination of a program through exception handling feature.
      2. It provides strong memory management through Garbage Collector from JVM, which collects all the unused variables and objects to free up the memory space. Whereas in prior programming languages, programmers are solely responsible for allocating and deallocating memory spaces.

   6. **Secured:** Java is extremely safe due to various features listed below,

      1. There are no explicit pointers. So you cannot access out-of-bound array. If you still try to access an array, it will show an `ArrayIndexOutOfBound` Exception. So it is impossible to exploit in Java with security flaws like stack corruption or buffer overflow.
      2. The programs runs in an secured environment(JVM) that is independent of operating system(OS).
      3. Java has bytecode verifier that checks the code blocks for any illegal code that violates the access right to objects.

   7. **Distributed:** Java supports the creation of distributed applications by using Remote Method Invocation(RMI) and Enterprise Java Beans. The java programs are easily distributed on one or more systems through internet connection.

   8. **Multi-threaded:** Java supports multithreading feature, which allows concurrent execution of several parts of a program for maximum utilization of the CPU. This is possible through multiple threads running the program simultaneously.

   9. **Compiled and Interpreted:** It provides both compilation and interpretation of programs. The programs are compiled by compiler first and the generated bytecode is going to be interpreted.

   10. **High performance:** Java bytecode is close to native code, so it runs more quickly than other conventionally interpreted programming languages. Ofcourse, it is not as fast as compiled languages like C or C++. JVM also uses JIT compiler which enables high performance through below features.
   11. Method inlining
   12. Dead code elimination
   13. Null check elimination
   14. Constant folding

   **[⬆ Back to Top](#table-of-contents)**

5. ### What is public static void main?

   The `main()` method acts as a starting point for JVM to start the execution of a Java program. i.e, JVM doesn't execute the code if there is no main method in the code. The signature of main method should follow specific pattern for the JVM to recognize it as a entry point. Since it is an important method of Java, you need to have proper understanding of its signature in detail.

   The signature of main method for displaying "Hello World" looks like below,

   ```java
   public static void main(String[] args) {
        System.out.println("Hello World");
   }
   ```

   When `java.exe` parses the command line, it generates a new String array and invokes the main() method. Let's describe each word in the statement,

   1. Public: The public access modifier is accessible everywhere and it enables JVM can invoke it from outside the class as it is not present in the current class. Otherwise, you will receive an error saying "Main method not found in class".

   2. Static: This static keyword is used to make `main()` method as a class related method so that JVM can invoke it without instantiating the class. It is also helpful to avoid unnecessary memory usage with object just for calling main method.

   3. Void: The void keyword is used to specify that a method doesn’t return anything. Since main() method doesn't return anything, its return type is void. Once the main method terminates, the java program terminates as well.

   4. Main: The "main" method name is an identifier that the JVM looks for as the starting point of the Java program.

   5. String[] args: This is an array of strings which stores arguments passed by command line while starting a program.

   **Note:** You can create any number of main methods through overloading features. i.e, Multiple main methods can be created with different parameters.

   **[⬆ Back to Top](#table-of-contents)**

6. ### What is string constant pool

   String constant pool is a special storage space inside the heap memory area where string literals are stored. It is also known as **String pool** or **String Intern Pool**. This is privately maintained by String class and it is empty by default. Whenever you create a new string object, JVM checks for presence of string object in the string pool. If the string value is already present, the same object reference is shared with the variable, else a new string is created in the pool with the variable reference stored in stack area.

   **[⬆ Back to Top](#table-of-contents)**

7. ### Why strings are immutable

   Strings are immutable, that means the contents of string objects can't be modified after their creation. i.e, When you try to alter the string, it creates a new string. Due to this behavior, the internal state of a string remains the same throughout the execution of the program. This characteristic of immutability helps with the benefits of caching, security, synchronization, and performance.

   **[⬆ Back to Top](#table-of-contents)**

8. ### What is the difference between StringBuffer and StringBuilder

   String is an immutable class to represent sequence of characters. Java also provided mutable version of String class through StringBuffer and StringBuilder. Even though both these classes are mutable, there are many differences between StringBuffer and StringBuilder.

   Some of the major differences in a tabular form:

   | StringBuffer                                                                                                                     | StringBuilder                                                                                                                            |
   | -------------------------------------------------------------------------------------------------------------------------------- | ---------------------------------------------------------------------------------------------------------------------------------------- |
   | StringBuffer was introduced in Java 1.0 version                                                                                  | StringBuilder was introduced in Java 1.5 version                                                                                         |
   | StringBuffer is synchronized(thread safe). That means two or more threads cannot call the methods of StringBuffer simultaneously | StringBuilder is non-synchronized(not thread safe). That means two or more threads can call the methods of StringBuilder simultaneously. |
   | Due to Synchronization, StringBuffer is slower than StringBuilder                                                                | StringBuilder is faster than StringBuffer because there won't be any preliminary checks for multiple threads                             |

   **[⬆ Back to Top](#table-of-contents)**

9. ### What is the importance of hashCode() and equals() methods

   Since both `equals()` and `hashCode()` methods are available in Object class(i.e, Java.lang.object), every java class gets the default implementation of equals and hashCode methods. These methods work together to verify if two objects have the same value or not.

   **1. equals:** The `equals()` method is used to compare equality of two Objects. By default their implementation compares the identities of the object. The Object class defined `equals()` method as follows,

   ```java
   public boolean equals(Object obj) {
       return (this == obj);
   }
   ```

   There are some rules need to be followed to use equals method:

   1. **Reflexive:** For any object x, `x.equals(x)` should return `true`.
   2. **Symmetric:** For any two objects x and y, `x.equals(y)` should return `true` if and only if `y.equals(x)` returns `true`.
   3. **Transitive:** For multiple objects x, y, and z, `if x.equals(y)` returns `true` and `y.equals(z)` returns `true`, then `x.equals(z)` should return `true`.
   4. **Consistent:** For any two objects x and y, multiple invocations of `x.equals(y)` should return same result(`true` or `false`), unless any of the object properties is modified that is being used in the equals() method implementation.

   **2. hashCode:** The `hashCode()` method returns the integer hash code value of the object. This method must be overridden in every class which overrides `equals()` method. The general contract of hashCode is:

   1. While execution of the application, the multiple invocations of `hashCode()` on the object should return the same integer value, unless the object property used in the `equals()` method is being modified.
   2. During the multiple executions of the application, the object's hashCode can change.
   3. If two objects are equal based on `equals()` method, then their object's hash code must be same.
   4. If two objects are unequal based on `equals()` method, their hash code value may or may not be equal.

   Together, the implementation of `equals()` and `hashCode()` should follow these rules.

   1. If `x.equals(y)` is true, then `x.hashCode() === y.hashCode()` should always be true.
   2. If `x.hashCode() === y.hashCode()` is true, then it doesn't required to be `x.equals(y)` always true.

   **[⬆ Back to Top](#table-of-contents)**

10. ### What is the difference between checked and unchecked expceptions

    An exception is an event that interrupts the normal flow the program execution. There are two types of exceptions,

    1. Checked exceptions
    2. Unchecked exceptions

    The hierarchical structure of exceptions is categorized as shown below,

    ![Screenshot](images/CheckedVsUncheckedException.png)

    The exceptions which are checked at compile time are known as checked exceptions. If some code inside a method throws this checked exception, then either you need to handle(or caught) the exception using **try/catch** block or declare in the method signature using **thows** keyword.

    Some of the common checked exceptions are,

    1. IOException
    2. FileNotFoundException
    3. ClassNotFoundException
    4. InterruptedException
    5. SQLException
    6. ParseException

    For example, the following class has two methods which throws checked(`FileNotFoundException`) exceptions from FileInputStream constructor. This is due to accessing input file which doesn't exist. You can handle them either using try/catch block or declaring thows keyword in the method signature.

    ```java
        import java.io.*;

        class MyCheckedExceptions {

            private void methodWithTryCatch() {
                    File file = new File("non_existing_file.txt");
                    try {
                        FileInputStream stream = new FileInputStream(file);
                    } catch (FileNotFoundException e) {
                        e.printStackTrace();
                    }
            }

            private void methodWithThrows() throws FileNotFoundException {
                    File file = new File("non_existing_file.txt");
                    FileInputStream stream = new FileInputStream(file);
            }

        }
    ```

    Whereas the exceptions which are not checked at compile time are known as unchecked exceptions. All the exceptions under Error and RuntimeException comes under unchecked exceptions.

    Some of the common unchecked exceptions are,

    1. NullPointerException
    2. ArrayIndexOutOfBoundsException
    3. ArithmeticException
    4. NumberFormatException
    5. IllegalThreadStateException

    For example, the following method doesn't have any errors during compile time. But it will throw `ArithmeticException` during runtime because of division by zero.

    ```java
    class MyUncheckedException {

        private void divideByZero() {
    	    int a = 1;
    	    int b = 0;
    	    int result = a / b;
        }

    }
    ```

    **[⬆ Back to Top](#table-of-contents)**

11. ### What are wrapper classes

    Wrapper classes provides the mechanism to convert primitive types into object types and vice versa. Since Java is an object-oriented programming language, and many APIs and libraries in Java require objects instead primitive types. For example, data structures in collection framework, utility classes from `java.utils.*`,cloning process, Serialization, Synchronization etc require object type.

    The following table represent primitives and their respective wrapper classes.

    | Primitive data type | Wrapper class |
    | ------------------- | ------------- |
    | byte                | Byte          |
    | short               | Short         |
    | int                 | Integer       |
    | float               | Float         |
    | double              | Double        |
    | long                | Long          |
    | boolean             | Boolean       |
    | char                | Character     |

    You can use `.valueOf` methods from wrapper classes to convert primitive to object type, and the same way wrapper class methods like `intValue`, `doubleValue` etc used to convert wrapper class to primitive type. But this manual process can be automated.

    1. **autoboxing**

    The automatic conversion of primitive to object(corresponding wrapper class) is known as **autoboxing**. The following example demonstrate how the conversion works,

    ```java
    public class AutoboxingDemo{
        public static void main(String args[]){
            int num = 10;
            Integer x = Integer.valueOf(num); // Converting primitive int into Integer explicitly
            Integer y = num; // Autoboxing without explicit conversion

            System.out.println("x = "+ x + " y " + y);
        }
    }
    ```

    2. **unboxing**
       The automatic conversion of wrapper class to primitive is known as **unboxing**. The following example demonstrate both manual and automatic conversion,

    ```java
    public class UnboxingDemo{
       public static void main(String args[]){
           Integer num = new Integer(3);
           int x = num.intValue(); //Converting Integer to int explicitly
           int y = num; //Unboxing without manual conversion

           System.out.println("x ="+ x + "y = "+y);
       }
    }
    ```

    **Note:** These autoboxing and unboxing features are available from JDK1.5 version onwards.

    **[⬆ Back to Top](#table-of-contents)**

12. ### Why java is not pure object oriented language

    Java is not a fully object-oriented programming language because of two main reasons.

    1. It supports primitive data types like int, byte, long, short, etc., which are not objects. Even though you can convert primitive data types to objects using wrapper classes, it does not make Java a pure object-oriented language. Because these objects are not originally associated with Java and internally it uses operations like Unboxing and Autoboxing. That means even you use wrapper classes, under the hood it uses primitive types for the calculation.

    2. Both static variables and methods can be accessed without using an object. Instead, they are associated with classes, which is against to the object-oriented principle where everything should be an object.

    **[⬆ Back to Top](#table-of-contents)**

13. ### What is the difference between abstract class and interface

    Both Abstract class and interface are used to define contracts in object-oriented programming. But there are some key differences between them as shown below,

    | Abstract class                                                                                          | Interface                                                                                                          |
    | ------------------------------------------------------------------------------------------------------- | ------------------------------------------------------------------------------------------------------------------ |
    | The `abstract` keyword is used to declare abstract class and it can be extended using `extends` keyword | The `interface` keyword is used to declare interface and it can extend another interface only.                     |
    | The abstract class contains abstract and non-abstract methods                                           | Interface can have abstract methods only. But it is possible to have default and static methods from Java8 onwards |
    | It supports final, non-final, static and non-static variables                                           | It supports only final and static variables.                                                                       |
    | It doens't support multiple inheritance                                                                 | Interface supports multiple inheritance                                                                            |
    | It can have access modifiers such as public, protected, and private for their methods and properties    | It can only have public access                                                                                     |

    **Note:** Both Abstract class and interfaces cannot be instantiated.

    **[⬆ Back to Top](#table-of-contents)**

14. ### What are marker interfaces

    Marker interfaces are interfaces that don't have any fields, methods, or constants inside of it. They are also known as empty interfaces or tag interfaces. Examples of marker interface are Serializable, Cloneable and Remote interface. The purpose of marker interfaces are to provide run-time type information about an object to JVM and Compiler. They are mainly used in API development and in frameworks like Spring to provide additional information to the class.

    Some of the commonly used built-in marker interfaces are:

    1. **Cloneable:** It is available in `java.lang` package. If we try to clone an object that doesn’t implement this marker interface, the JVM throws a `CloneNotSupportedException`. i.e, This marker interface is used as a signal/indicator to the JVM that it is legal to call the `Object.clone()` method.
    2. **Serializable:** It is available in `java.io` package. When we try to write an object to output stream using `ObjectOutputStream.writeObject()` method without implementing this marker interface, JVM throws an exception named `NotSerializableException`.
    3. **Remote:** It is available in `java.rmi` package. A remote object can be accessed from another machine if and only if the class has implemented this marker interface. Otherwise, it is going to throw exception named `RemoteException`.

    For example, the cloneable marker interface looks like below,

    ```java
    public interface Cloneable {
       // nothing here
    }
    ```

    and the following student class implements Cloneable interface to make a copy of student's object.

    ```java
    import java.lang.*;

    class Student implements cloneable {

        String name = null;
        int age = 0;

        Student(String name, int age) {
            this.name = name;
            this.age = age;
        }

        @Override
        protected Object clone() throws CloneNotSupportedException {
            return super.clone();
        }

        public static void main(String[] args) {

            Student s1 = new Student("Sudheer", 30);
            //Create clone of s1 object
            try {
                Student s2 = s1.clone();
            } catch (Exception e) {
                System.out.println(s2.toString());
            }
        }
    }

    ```

    There are also alternatives for marker interfaces.

    1. **Internal flags:** They can be used in place of marker interface to indicate any specific operation.
    2. **Annotations:** They are used as tags to represent the metadata attached to classes, interfaces, or methods to indicate additional information required by JVM.

    **[⬆ Back to Top](#table-of-contents)**

15. ### What are collections in Java?

    Collections in Java is a unified framework that provides architecture for storing and manipulating a group of objects.

    The `java.util.*` package contains the following classes and interfaces for Collections framework.

    ![Screenshot](images/CollectionsHierarchy.png)

    **[⬆ Back to Top](#table-of-contents)**

16. ### What are the differences between arraylist and vector?

    Both Vector and ArrayList use dynamically resizable array as their internal data structure and implement the List interface. But there are couple of differences between them as listed below,

    | ArrayList                                                                                     | Vector                                                                                      |
    | --------------------------------------------------------------------------------------------- | ------------------------------------------------------------------------------------------- |
    | This data structure is part of Collection framework, introduced in JDK 1.2                    | This is a legacy class                                                                      |
    | The capacity increment of ArrayList is 50% if the number of elements exceeds the current size | The capacity increment of Vector is 100% if the number of elements exceeds the current size |
    | It is not synchronized by default. That means multiple threads can access it concurrently.    | It is synchronized by default. That means only one thread can access it at a time.          |
    | It is quite fast because it is not synchronized                                               | It is quite slow due to synchronization                                                     |
    | ArrayList uses the Iterator interface to traverse over the elements.                          | Vector uses both the Iterator and Enumeration interfaces to traverse over the elements.     |

    **[⬆ Back to Top](#table-of-contents)**

17. ### What is finalize method? How do you override it?

    The `finalize()` is a method from the Object class used to perform cleanup activity before destroying any object. The method is invoked by garbage collector for cleanup activities like closing the resources associated with an object(database connection or network connection). This process is known as **finalization** and it helps JVM for in-memory optimization.

    It is a protected method of Object class with syntax as shown below,

    ```java
    protected void finalize() throws Throwable{}
    ```

    Since Object is the superclass of all java classes, the finalize method is available for every java class. That's why garbage collector can call the `finalize()` method on any java object.

    This method has empty implementation inside Object class. If your class has clean-up activities, you need to override this method. The following example demonstrate how to override the finalize method and call the method explicitly.

    ```java
    import java.lang.*;

    public class finalizeDemo {

        protected void finalize() throws Throwable {
                try {

                    System.out.println("Inside finalize() method of finalizeDemo class");
                }
                catch (Throwable e) {

                    throw e;
                }
                finally {

                    System.out.println("Calling finalize method of the Object(super) class");

                    super.finalize();
                }
        }

        public static void main(String[] args) throws Throwable {
            finalizeDemo fd = new finalizeDemo();
            fd.finalize();
        }
    }
    ```

    The statement `super.finalize()` is called inside finally block to ensure its execution even in the case of exceptions.

    **Note:** The garbage collector invokes the `finalize()` method only once on any object.

    **[⬆ Back to Top](#table-of-contents)**

18. ### What Is the Difference Between the Comparable and Comparator Interfaces

    Java provides Comparable and Comparator interfaces for sorting the collection of objects, but they serve different purposes and are used in different scenarios. 

    **Comparable:**
    The Comparable interface is capable of comparing an object with another object of same type. The class which needs to compare its instances has to implement `java.lang.Comparable` interface.
    It can be used to provide **single way of sorting**. That means that the objects can be sorted based on a single data member. For example, Employee object can be sorted based on single attributes like id, name, age etc.

    If the class implements Comparable interface, it knows how to sort the objects because the same class itself has implemented compareTo method. This type of sorting is called **default or natural sorting**. The class can compare its object by overriding compareTo method with syntax as shown below,

    ```java
    class T implements Comparable<T> {
        @Override
        public int compareTo(T t) {
            // comparison logic goes here
        }
    }
    ```

    For example, group of employees sorted based on their name attribute using Comparable interfaces as follows

    ```java
    import java.util.*;

    class Employee implements Comparable<Employee> {
        private final String id;
        private final String name;
        private final int age;
        
        public Employee(String id, String name, int age) {
            this.id = id;
            this.name = name;
            this.age = age;
        }
        
        @Override
        public int compareTo(final Employee employee) {
            return this.name.compareTo(employee.name);
        }
        
        public String getId() { return this.id; }
        
        public String getName() { return this.name; }
        
        public int getAge() { return this.age; }
        
        @Override
        public String toString() {
            return String.format("ID: %s | Name: %s | Age: %d", id, name, age);
        }
    }

    public class Main {
        public static void main(String[] args) {
            List<Employee> employees = new ArrayList<>();

            employees.add(new Employee("3", "John", 32));
            employees.add(new Employee("1", "James", 27));
            employees.add(new Employee("2", "Jackson", 22));
            
            Collections.sort(employees);

            employees.forEach(employee -> 
                                System.out.println(employee.toString()));
        }
    }
    ```

    **Comparator:**

    The comparator is a functional interface used to sort objects and it provides **multiple sorting sequence** in which objects sorted based on multiple data members. This interface is available as part of `java.util` package.  For example, Employee object can be sorted based on multiple attributes like id, name, age etc.

    The comparator is used for custom ordering where the class is not aware about the sorting logic. The comparator can be created using a lambda expression that accept two objects of given type and return an integer value(i.e, 1, 0, -1) based on ordering with syntax as shown below,

    ```java
     Comparator<T> comparator = (T t1, T t2) -> { 
        //comparison logic 
     }
    ```

    You can create multiple separate classes (which implement Comparator interface) to compare by different members.The Comparator provides the compare() method which can be overridden to customize the comparison logic. For example, group of employees sorted based on id and age data members even though Employee class overridden the compareTo method.

    ```java
    public static void sortById(List<Employee> employees) {
        Comparator<Employee> idComparator = (Employee e1, Employee e2) -> {
            return e1.getId().compareTo(e2.getId());
        };
        
        employees.sort(idComparator);
    }
    
    public static void sortByAge(List<Employee> employees) {
        Comparator<Employee> ageComparator = (Employee e1, Employee e2) -> {
            return e1.getAge() - e2.getAge();
        };
        
        employees.sort(ageComparator);
    }
    ```

    In the above example, idComparator and ageComparator have been created to perform custom sorting. These comparators needs to be passed as an argument to sort method.
    
    **Note:** It is preferred to use lambda expression to create Comparator because it is a functional interface(exactly one abstract method).


    **[⬆ Back to Top](#table-of-contents)**

19. ### What Is an inner class

   An inner class is a class that is defined within another class. Inner classes are used to logically group classes that are only used in one place, increase encapsulation, and make code more readable and maintainable. Java supports four types of inner classes:

   1. **Member Inner Class (Non-static nested class):** A class defined inside another class without the static modifier. It has access to all members of the outer class, including private members.

   ```java
   class Outer {
       private int data = 30;
       
       class Inner {
           void display() {
               System.out.println("Data: " + data);
           }
       }
       
       public static void main(String[] args) {
           Outer outer = new Outer();
           Outer.Inner inner = outer.new Inner();
           inner.display();
       }
   }
   ```

   2. **Static Nested Class:** A static class defined inside another class. It can only access static members of the outer class.

   ```java
   class Outer {
       static int data = 30;
       
       static class StaticNested {
           void display() {
               System.out.println("Data: " + data);
           }
       }
       
       public static void main(String[] args) {
           Outer.StaticNested nested = new Outer.StaticNested();
           nested.display();
       }
   }
   ```

   3. **Local Inner Class:** A class defined within a method. It can access local variables that are final or effectively final.

   ```java
   class Outer {
       void display() {
           final int num = 23;
           
           class LocalInner {
               void print() {
                   System.out.println("Number: " + num);
               }
           }
           
           LocalInner inner = new LocalInner();
           inner.print();
       }
   }
   ```

   4. **Anonymous Inner Class:** A class without a name, used to instantiate objects with certain extras such as overriding methods.

   ```java
   abstract class Animal {
       abstract void sound();
   }
   
   class Test {
       public static void main(String[] args) {
           Animal dog = new Animal() {
               void sound() {
                   System.out.println("Bark");
               }
           };
           dog.sound();
       }
   }
   ```

   **[⬆ Back to Top](#table-of-contents)**

20. ### What is the difference between final, finally, and finalize() in Java?

   The terms `final`, `finally`, and `finalize()` in Java look similar but serve completely different purposes.

   1. **final** → It is a **modifier** used for variables, methods, and classes.  
      - A `final` variable cannot be reassigned once initialized.  
      - A `final` method cannot be overridden in subclasses.  
      - A `final` class cannot be extended.  

   2. **finally** → It is a **block** used in **exception handling** to execute important code such as closing files, releasing connections, etc.  
      - The `finally` block executes **regardless** of whether an exception occurs or not.  

   3. **finalize()** → It is a **method** defined in the `Object` class that the **Garbage Collector** calls before destroying an object.  
      - It is rarely used now because garbage collection timing is unpredictable.

   **Example:**

   ```java
   public class FinalExample {
       final int VALUE = 100;

       public final void display() {
           System.out.println("Final method");
       }

       public static void main(String[] args) {
           try {
               System.out.println("Inside try block");
           } finally {
               System.out.println("Inside finally block");
           }
       }

       @Override
       protected void finalize() throws Throwable {
           System.out.println("Finalize method called");
       }
   }
   ```

   **[⬆ Back to Top](#table-of-contents)**

21. ### What is the difference between '==' and equals() method?
    
    Both **==** and **.equals()** methods are used to compare objects, but they work in different ways:

    1. **== (Reference comparison):** The `==` operator compares the memory addresses (references) of two objects. It returns `true` if both references point to the same object in memory.

    2. **.equals() (Content comparison):** The `.equals()` method compares the actual content or values of two objects. By default, it behaves like `==`, but it can be overridden to provide custom comparison logic.

    ```java
    public class ComparisonExample {
        public static void main(String[] args) {
            String s1 = new String("Hello");
            String s2 = new String("Hello");
            String s3 = s1;
            
            // == compares references
            System.out.println(s1 == s2);      // false (different objects)
            System.out.println(s1 == s3);      // true (same reference)
            
            // equals() compares content
            System.out.println(s1.equals(s2)); // true (same content)
            System.out.println(s1.equals(s3)); // true (same content)
        }
    }
    ```

    | == Operator | equals() Method |
    |-------------|-----------------|
    | Compares object references | Compares object content |
    | Cannot be overridden | Can be overridden |
    | Works with primitives and objects | Works only with objects |
    | Returns true if same memory location | Returns true if content is same |

    **[⬆ Back to Top](#table-of-contents)**

22. ### What is method overloading and method overriding?

    Method overloading and method overriding are two important concepts in Java that enable polymorphism.

    **Method Overloading (Compile-time Polymorphism):**
    Method overloading occurs when multiple methods in the same class have the same name but different parameters (different number, type, or order of parameters). The return type can be the same or different.

    ```java
    class Calculator {
        // Method with two int parameters
        int add(int a, int b) {
            return a + b;
        }
        
        // Overloaded method with three int parameters
        int add(int a, int b, int c) {
            return a + b + c;
        }
        
        // Overloaded method with double parameters
        double add(double a, double b) {
            return a + b;
        }
    }
    ```

    **Method Overriding (Runtime Polymorphism):**
    Method overriding occurs when a subclass provides a specific implementation of a method that is already defined in its parent class. The method must have the same name, return type, and parameters.

    ```java
    class Animal {
        void sound() {
            System.out.println("Animal makes a sound");
        }
    }
    
    class Dog extends Animal {
        @Override
        void sound() {
            System.out.println("Dog barks");
        }
    }
    
    class Cat extends Animal {
        @Override
        void sound() {
            System.out.println("Cat meows");
        }
    }
    ```

    | Method Overloading | Method Overriding |
    |--------------------|-------------------|
    | Same method name, different parameters | Same method name, same parameters |
    | Occurs within the same class | Occurs between parent and child class |
    | Compile-time polymorphism | Runtime polymorphism |
    | Return type can be different | Return type must be same or covariant |
    | Access modifier can be any | Cannot reduce access modifier |

    **[⬆ Back to Top](#table-of-contents)**

23. ### What is the difference between HashMap and Hashtable?

    Both HashMap and Hashtable are used to store key-value pairs in Java, but they have several important differences:

    | HashMap | Hashtable |
    |---------|-----------|
    | Not synchronized (not thread-safe) | Synchronized (thread-safe) |
    | Allows one null key and multiple null values | Does not allow null keys or values |
    | Introduced in Java 1.2 | Legacy class from Java 1.0 |
    | Faster due to no synchronization | Slower due to synchronization overhead |
    | Iterator is fail-fast | Enumerator is not fail-fast |
    | Extends AbstractMap class | Extends Dictionary class |
    | Preferred for single-threaded applications | Can be used in multi-threaded applications |

    ```java
    import java.util.*;

    public class MapComparison {
        public static void main(String[] args) {
            // HashMap example
            HashMap<String, Integer> hashMap = new HashMap<>();
            hashMap.put("One", 1);
            hashMap.put(null, 0);        // Allows null key
            hashMap.put("Two", null);    // Allows null value
            
            // Hashtable example
            Hashtable<String, Integer> hashtable = new Hashtable<>();
            hashtable.put("One", 1);
            // hashtable.put(null, 0);   // Throws NullPointerException
            // hashtable.put("Two", null); // Throws NullPointerException
        }
    }
    ```

    **Note:** For thread-safe operations, prefer `ConcurrentHashMap` over `Hashtable` as it provides better performance through segment-level locking.

    **[⬆ Back to Top](#table-of-contents)**

24. ### What is the difference between ArrayList and LinkedList?

    Both ArrayList and LinkedList implement the List interface but differ in their internal implementation and performance characteristics.

    | ArrayList | LinkedList |
    |-----------|------------|
    | Uses dynamic array internally | Uses doubly linked list internally |
    | Better for storing and accessing data (O(1) for get) | Better for manipulating data (O(1) for add/remove at ends) |
    | Slower manipulation as shifting is required | Faster manipulation, no shifting needed |
    | Implements only List interface | Implements List and Deque interfaces |
    | More memory efficient | More memory overhead (stores prev/next references) |
    | Good for random access | Good for sequential access |

    ```java
    import java.util.*;

    public class ListComparison {
        public static void main(String[] args) {
            // ArrayList - better for random access
            ArrayList<String> arrayList = new ArrayList<>();
            arrayList.add("A");
            arrayList.add("B");
            arrayList.get(0);  // O(1) - fast random access
            
            // LinkedList - better for frequent insertions/deletions
            LinkedList<String> linkedList = new LinkedList<>();
            linkedList.add("A");
            linkedList.addFirst("B");  // O(1) - fast insertion at beginning
            linkedList.removeLast();   // O(1) - fast removal at end
        }
    }
    ```

    **When to use:**
    - Use **ArrayList** when you need frequent access to elements by index
    - Use **LinkedList** when you need frequent insertions/deletions, especially at the beginning or middle of the list

    **[⬆ Back to Top](#table-of-contents)**

25. ### What is Java Reflection API?

    Java Reflection API is a powerful feature that allows programs to examine and modify the behavior of classes, interfaces, methods, and fields at runtime. It is part of the `java.lang.reflect` package.

    **Key capabilities of Reflection:**
    1. Examine class properties at runtime
    2. Create objects dynamically
    3. Invoke methods at runtime
    4. Access and modify private fields
    5. Get information about constructors, methods, and fields

    ```java
    import java.lang.reflect.*;

    class Person {
        private String name;
        public int age;
        
        public Person() {}
        
        public Person(String name, int age) {
            this.name = name;
            this.age = age;
        }
        
        private void privateMethod() {
            System.out.println("Private method called");
        }
        
        public void display() {
            System.out.println("Name: " + name + ", Age: " + age);
        }
    }

    public class ReflectionDemo {
        public static void main(String[] args) throws Exception {
            // Get Class object
            Class<?> clazz = Person.class;
            
            // Get class name
            System.out.println("Class: " + clazz.getName());
            
            // Get all declared methods
            Method[] methods = clazz.getDeclaredMethods();
            for (Method method : methods) {
                System.out.println("Method: " + method.getName());
            }
            
            // Create instance dynamically
            Constructor<?> constructor = clazz.getConstructor(String.class, int.class);
            Person person = (Person) constructor.newInstance("John", 25);
            
            // Access private field
            Field nameField = clazz.getDeclaredField("name");
            nameField.setAccessible(true);
            nameField.set(person, "Jane");
            
            // Invoke method
            Method displayMethod = clazz.getMethod("display");
            displayMethod.invoke(person);
        }
    }
    ```

    **Use cases:** Frameworks like Spring, Hibernate, JUnit use Reflection extensively for dependency injection, ORM mapping, and test execution.

    **[⬆ Back to Top](#table-of-contents)**

26. ### What are the different types of memory areas allocated by JVM?

    JVM allocates memory in different areas for efficient program execution. The main memory areas are:

    1. **Method Area (Metaspace):**
       - Stores class-level data like class structures, method data, and runtime constant pool
       - Shared among all threads
       - Created during JVM startup

    2. **Heap Area:**
       - Stores all objects and their instance variables
       - Shared among all threads
       - Managed by Garbage Collector
       - Divided into Young Generation (Eden, Survivor spaces) and Old Generation

    3. **Stack Area:**
       - Each thread has its own stack
       - Stores local variables, method calls, and partial results
       - Contains stack frames for each method invocation
       - Memory is automatically allocated/deallocated

    4. **PC (Program Counter) Registers:**
       - Each thread has its own PC register
       - Stores address of currently executing JVM instruction
       - Updated after each instruction execution

    5. **Native Method Stack:**
       - Contains native method information
       - Each thread has its own native method stack
       - Used for methods written in languages other than Java (C, C++)

    ```
    JVM Memory Structure:
    ┌─────────────────────────────────────────────┐
    │              Method Area (Metaspace)         │
    │  (Class data, Method data, Constant pool)   │
    ├─────────────────────────────────────────────┤
    │                  Heap Area                   │
    │  ┌─────────────────┬─────────────────────┐  │
    │  │ Young Generation│   Old Generation    │  │
    │  │ (Eden,Survivor) │                     │  │
    │  └─────────────────┴─────────────────────┘  │
    ├─────────────────────────────────────────────┤
    │  Stack │  Stack  │  Stack  │ ... (per thread)│
    ├─────────────────────────────────────────────┤
    │  PC Reg│  PC Reg │  PC Reg │ ... (per thread)│
    ├─────────────────────────────────────────────┤
    │  Native│ Native  │ Native  │ ... (per thread)│
    └─────────────────────────────────────────────┘
    ```

    **[⬆ Back to Top](#table-of-contents)**

27. ### What is the difference between throw and throws?

    Both `throw` and `throws` are used in exception handling but serve different purposes.

    **throw:**
    - Used to explicitly throw an exception
    - Used inside a method body
    - Can throw only one exception at a time
    - Followed by an exception instance

    **throws:**
    - Used to declare exceptions that a method might throw
    - Used in method signature
    - Can declare multiple exceptions
    - Followed by exception class names

    ```java
    import java.io.*;

    public class ThrowVsThrows {
        
        // Using throws - declares that method may throw an exception
        public void readFile(String filename) throws FileNotFoundException, IOException {
            FileReader file = new FileReader(filename);
            BufferedReader reader = new BufferedReader(file);
            String line = reader.readLine();
            reader.close();
        }
        
        // Using throw - explicitly throws an exception
        public void validateAge(int age) {
            if (age < 0) {
                throw new IllegalArgumentException("Age cannot be negative");
            }
            if (age < 18) {
                throw new ArithmeticException("Not eligible to vote");
            }
            System.out.println("Eligible to vote");
        }
        
        // Combining throw and throws
        public void processData(String data) throws CustomException {
            if (data == null) {
                throw new CustomException("Data cannot be null");
            }
            // Process data
        }
    }

    class CustomException extends Exception {
        public CustomException(String message) {
            super(message);
        }
    }
    ```

    | throw | throws |
    |-------|--------|
    | Used to throw an exception | Used to declare an exception |
    | Inside method body | In method signature |
    | Cannot throw multiple exceptions | Can declare multiple exceptions |
    | Followed by instance | Followed by class name |
    | Checked exceptions must be caught | Propagates exception to caller |

    **[⬆ Back to Top](#table-of-contents)**

28. ### What is a singleton class and how to create one?

    A Singleton class is a design pattern that ensures only one instance of a class is created throughout the application lifecycle. It provides a global point of access to that instance.

    **Key characteristics:**
    - Private constructor to prevent direct instantiation
    - Static method to get the single instance
    - Static variable to hold the single instance

    **Different ways to create Singleton:**

    1. **Eager Initialization:**
    ```java
    public class EagerSingleton {
        private static final EagerSingleton instance = new EagerSingleton();
        
        private EagerSingleton() {}
        
        public static EagerSingleton getInstance() {
            return instance;
        }
    }
    ```

    2. **Lazy Initialization:**
    ```java
    public class LazySingleton {
        private static LazySingleton instance;
        
        private LazySingleton() {}
        
        public static LazySingleton getInstance() {
            if (instance == null) {
                instance = new LazySingleton();
            }
            return instance;
        }
    }
    ```

    3. **Thread-Safe Singleton (Double-Checked Locking):**
    ```java
    public class ThreadSafeSingleton {
        private static volatile ThreadSafeSingleton instance;
        
        private ThreadSafeSingleton() {}
        
        public static ThreadSafeSingleton getInstance() {
            if (instance == null) {
                synchronized (ThreadSafeSingleton.class) {
                    if (instance == null) {
                        instance = new ThreadSafeSingleton();
                    }
                }
            }
            return instance;
        }
    }
    ```

    4. **Bill Pugh Singleton (Best Practice):**
    ```java
    public class BillPughSingleton {
        private BillPughSingleton() {}
        
        private static class SingletonHelper {
            private static final BillPughSingleton INSTANCE = new BillPughSingleton();
        }
        
        public static BillPughSingleton getInstance() {
            return SingletonHelper.INSTANCE;
        }
    }
    ```

    **[⬆ Back to Top](#table-of-contents)**

29. ### What are Java 8 Stream API features?

    Java 8 Stream API provides a functional approach to process collections of objects. Streams support sequential and parallel operations on data.

    **Key Features:**
    1. **Lazy Evaluation:** Intermediate operations are not executed until a terminal operation is invoked
    2. **Pipelining:** Operations can be chained together
    3. **Internal Iteration:** Stream handles iteration internally
    4. **Parallel Processing:** Easy parallel execution with `parallelStream()`

    **Common Stream Operations:**

    ```java
    import java.util.*;
    import java.util.stream.*;

    public class StreamDemo {
        public static void main(String[] args) {
            List<Integer> numbers = Arrays.asList(1, 2, 3, 4, 5, 6, 7, 8, 9, 10);
            
            // filter - filters elements based on condition
            List<Integer> evenNumbers = numbers.stream()
                .filter(n -> n % 2 == 0)
                .collect(Collectors.toList());
            // Result: [2, 4, 6, 8, 10]
            
            // map - transforms elements
            List<Integer> squares = numbers.stream()
                .map(n -> n * n)
                .collect(Collectors.toList());
            // Result: [1, 4, 9, 16, 25, 36, 49, 64, 81, 100]
            
            // reduce - combines elements
            int sum = numbers.stream()
                .reduce(0, (a, b) -> a + b);
            // Result: 55
            
            // sorted - sorts elements
            List<Integer> sorted = numbers.stream()
                .sorted(Comparator.reverseOrder())
                .collect(Collectors.toList());
            
            // distinct - removes duplicates
            List<Integer> unique = Arrays.asList(1, 1, 2, 2, 3).stream()
                .distinct()
                .collect(Collectors.toList());
            // Result: [1, 2, 3]
            
            // limit and skip
            List<Integer> limited = numbers.stream()
                .skip(2)
                .limit(5)
                .collect(Collectors.toList());
            // Result: [3, 4, 5, 6, 7]
            
            // anyMatch, allMatch, noneMatch
            boolean hasEven = numbers.stream().anyMatch(n -> n % 2 == 0);
            boolean allPositive = numbers.stream().allMatch(n -> n > 0);
            
            // findFirst, findAny
            Optional<Integer> first = numbers.stream().findFirst();
            
            // count
            long count = numbers.stream().filter(n -> n > 5).count();
            
            // forEach
            numbers.stream().forEach(System.out::println);
        }
    }
    ```

    **[⬆ Back to Top](#table-of-contents)**

30. ### What is the difference between fail-fast and fail-safe iterators?

    Iterators in Java can be categorized as fail-fast or fail-safe based on their behavior when the underlying collection is modified during iteration.

    **Fail-Fast Iterator:**
    - Throws `ConcurrentModificationException` if the collection is modified during iteration
    - Works on the original collection
    - Examples: ArrayList, HashMap, HashSet iterators
    - Uses `modCount` to detect modifications

    ```java
    import java.util.*;

    public class FailFastExample {
        public static void main(String[] args) {
            List<String> list = new ArrayList<>();
            list.add("A");
            list.add("B");
            list.add("C");
            
            Iterator<String> iterator = list.iterator();
            while (iterator.hasNext()) {
                String element = iterator.next();
                if (element.equals("B")) {
                    list.remove(element); // Throws ConcurrentModificationException
                }
            }
        }
    }
    ```

    **Fail-Safe Iterator:**
    - Does not throw exception if collection is modified during iteration
    - Works on a clone/copy of the collection
    - Examples: CopyOnWriteArrayList, ConcurrentHashMap iterators
    - More memory overhead due to copying

    ```java
    import java.util.concurrent.*;
    import java.util.*;

    public class FailSafeExample {
        public static void main(String[] args) {
            CopyOnWriteArrayList<String> list = new CopyOnWriteArrayList<>();
            list.add("A");
            list.add("B");
            list.add("C");
            
            Iterator<String> iterator = list.iterator();
            while (iterator.hasNext()) {
                String element = iterator.next();
                if (element.equals("B")) {
                    list.remove(element); // No exception thrown
                }
            }
            System.out.println(list); // [A, C]
        }
    }
    ```

    | Fail-Fast | Fail-Safe |
    |-----------|-----------|
    | Throws ConcurrentModificationException | No exception thrown |
    | Works on original collection | Works on copy of collection |
    | Less memory overhead | More memory overhead |
    | ArrayList, HashMap, HashSet | CopyOnWriteArrayList, ConcurrentHashMap |

    **[⬆ Back to Top](#table-of-contents)**

31. ### What is the difference between process and thread?

    A process and a thread are both units of execution, but they differ significantly in their characteristics and usage.

    **Process:**
    - Independent executing program with its own memory space
    - Contains at least one thread (main thread)
    - Has its own address space, heap, stack, and system resources
    - Processes are isolated from each other
    - Inter-process communication (IPC) is expensive

    **Thread:**
    - Lightweight unit of execution within a process
    - Shares memory space with other threads in the same process
    - Has its own stack but shares heap with other threads
    - Threads within a process can communicate directly
    - Context switching between threads is faster

    ```java
    public class ProcessVsThread {
        public static void main(String[] args) {
            // Creating a new process
            try {
                ProcessBuilder pb = new ProcessBuilder("notepad.exe");
                Process process = pb.start(); // Creates a new process
            } catch (Exception e) {
                e.printStackTrace();
            }
            
            // Creating a new thread
            Thread thread = new Thread(() -> {
                System.out.println("Thread running: " + Thread.currentThread().getName());
            });
            thread.start(); // Creates a new thread within the same process
        }
    }
    ```

    | Process | Thread |
    |---------|--------|
    | Heavy weight | Light weight |
    | Own memory space | Shared memory space |
    | Slower context switching | Faster context switching |
    | Isolated from other processes | Can communicate with other threads |
    | More resource intensive | Less resource intensive |
    | Process crash doesn't affect others | Thread crash can affect entire process |

    **[⬆ Back to Top](#table-of-contents)**

32. ### What are the different ways to create a thread in Java?

    There are multiple ways to create a thread in Java:

    **1. Extending Thread class:**
    ```java
    class MyThread extends Thread {
        @Override
        public void run() {
            System.out.println("Thread running: " + Thread.currentThread().getName());
        }
    }

    // Usage
    MyThread thread = new MyThread();
    thread.start();
    ```

    **2. Implementing Runnable interface:**
    ```java
    class MyRunnable implements Runnable {
        @Override
        public void run() {
            System.out.println("Runnable running: " + Thread.currentThread().getName());
        }
    }

    // Usage
    Thread thread = new Thread(new MyRunnable());
    thread.start();
    ```

    **3. Using Lambda expression (Java 8+):**
    ```java
    Thread thread = new Thread(() -> {
        System.out.println("Lambda thread running");
    });
    thread.start();
    ```

    **4. Implementing Callable interface (returns result):**
    ```java
    import java.util.concurrent.*;

    class MyCallable implements Callable<Integer> {
        @Override
        public Integer call() throws Exception {
            return 42;
        }
    }

    // Usage
    ExecutorService executor = Executors.newSingleThreadExecutor();
    Future<Integer> future = executor.submit(new MyCallable());
    Integer result = future.get(); // Gets the result
    executor.shutdown();
    ```

    **5. Using ExecutorService:**
    ```java
    ExecutorService executor = Executors.newFixedThreadPool(5);
    
    executor.execute(() -> {
        System.out.println("Task executed by: " + Thread.currentThread().getName());
    });
    
    executor.submit(() -> {
        return "Task completed";
    });
    
    executor.shutdown();
    ```

    | Method | Returns Value | Can Extend Other Class | Exception Handling |
    |--------|--------------|------------------------|-------------------|
    | Thread class | No | No | Unchecked only |
    | Runnable | No | Yes | Unchecked only |
    | Callable | Yes | Yes | Checked and Unchecked |

    **[⬆ Back to Top](#table-of-contents)**

33. ### What is synchronization in Java?

    Synchronization is a mechanism that ensures only one thread can access a shared resource at a time. It prevents race conditions and ensures thread safety.

    **Types of Synchronization:**

    **1. Synchronized Method:**
    ```java
    class Counter {
        private int count = 0;
        
        public synchronized void increment() {
            count++;
        }
        
        public synchronized int getCount() {
            return count;
        }
    }
    ```

    **2. Synchronized Block:**
    ```java
    class Counter {
        private int count = 0;
        private final Object lock = new Object();
        
        public void increment() {
            synchronized (lock) {
                count++;
            }
        }
    }
    ```

    **3. Static Synchronization:**
    ```java
    class StaticCounter {
        private static int count = 0;
        
        public static synchronized void increment() {
            count++;
        }
    }
    ```

    **Example demonstrating the need for synchronization:**
    ```java
    class BankAccount {
        private int balance = 1000;
        
        // Without synchronization - race condition possible
        public void withdraw(int amount) {
            if (balance >= amount) {
                System.out.println(Thread.currentThread().getName() + " is withdrawing");
                balance -= amount;
                System.out.println("Balance after withdrawal: " + balance);
            }
        }
        
        // With synchronization - thread safe
        public synchronized void safeWithdraw(int amount) {
            if (balance >= amount) {
                System.out.println(Thread.currentThread().getName() + " is withdrawing");
                balance -= amount;
                System.out.println("Balance after withdrawal: " + balance);
            }
        }
    }
    ```

    **Key Points:**
    - Every object in Java has an intrinsic lock (monitor)
    - Only one thread can hold the lock at a time
    - Synchronization can cause performance overhead
    - Prefer synchronized blocks over synchronized methods for fine-grained control

    **[⬆ Back to Top](#table-of-contents)**

34. ### What is deadlock and how to avoid it?

    A deadlock is a situation where two or more threads are blocked forever, each waiting for the other to release a lock.

    **Deadlock Example:**
    ```java
    public class DeadlockExample {
        private static final Object lock1 = new Object();
        private static final Object lock2 = new Object();
        
        public static void main(String[] args) {
            Thread thread1 = new Thread(() -> {
                synchronized (lock1) {
                    System.out.println("Thread 1: Holding lock1");
                    try { Thread.sleep(100); } catch (InterruptedException e) {}
                    
                    synchronized (lock2) {
                        System.out.println("Thread 1: Holding lock1 and lock2");
                    }
                }
            });
            
            Thread thread2 = new Thread(() -> {
                synchronized (lock2) {
                    System.out.println("Thread 2: Holding lock2");
                    try { Thread.sleep(100); } catch (InterruptedException e) {}
                    
                    synchronized (lock1) {
                        System.out.println("Thread 2: Holding lock2 and lock1");
                    }
                }
            });
            
            thread1.start();
            thread2.start();
        }
    }
    ```

    **How to Avoid Deadlock:**

    **1. Lock Ordering - Always acquire locks in the same order:**
    ```java
    // Fixed version - both threads acquire locks in same order
    Thread thread1 = new Thread(() -> {
        synchronized (lock1) {
            synchronized (lock2) {
                // work
            }
        }
    });

    Thread thread2 = new Thread(() -> {
        synchronized (lock1) {  // Same order as thread1
            synchronized (lock2) {
                // work
            }
        }
    });
    ```

    **2. Use tryLock with timeout:**
    ```java
    import java.util.concurrent.locks.*;

    ReentrantLock lock1 = new ReentrantLock();
    ReentrantLock lock2 = new ReentrantLock();

    public void safeMethod() {
        boolean gotLock1 = false;
        boolean gotLock2 = false;
        try {
            gotLock1 = lock1.tryLock(1, TimeUnit.SECONDS);
            gotLock2 = lock2.tryLock(1, TimeUnit.SECONDS);
            if (gotLock1 && gotLock2) {
                // Do work
            }
        } catch (InterruptedException e) {
            e.printStackTrace();
        } finally {
            if (gotLock1) lock1.unlock();
            if (gotLock2) lock2.unlock();
        }
    }
    ```

    **3. Avoid nested locks**
    **4. Use lock timeout**
    **5. Avoid holding locks for long periods**

    **[⬆ Back to Top](#table-of-contents)**

35. ### What is the volatile keyword in Java?

    The `volatile` keyword in Java is used to indicate that a variable's value may be modified by different threads. It ensures visibility of changes across threads and prevents caching of the variable.

    **Key Features:**
    1. **Visibility:** Changes made by one thread are immediately visible to other threads
    2. **Atomicity:** Read and write operations on volatile variables are atomic (for primitives)
    3. **No Caching:** The variable is always read from main memory, not from CPU cache

    ```java
    public class VolatileExample {
        private volatile boolean running = true;
        
        public void stop() {
            running = false;
        }
        
        public void run() {
            while (running) {
                // Do work
            }
            System.out.println("Stopped");
        }
        
        public static void main(String[] args) throws InterruptedException {
            VolatileExample example = new VolatileExample();
            
            Thread worker = new Thread(() -> example.run());
            worker.start();
            
            Thread.sleep(1000);
            example.stop(); // This change will be visible to the worker thread
        }
    }
    ```

    **Without volatile:**
    ```java
    // Without volatile, the worker thread might never see the change
    // because it may read from its local cache
    private boolean running = true; // Thread may cache this value
    ```

    **Volatile vs Synchronized:**
    | volatile | synchronized |
    |----------|--------------|
    | Only ensures visibility | Ensures visibility and atomicity |
    | No blocking | Causes blocking |
    | Cannot be used for compound operations | Can protect compound operations |
    | Less overhead | More overhead |

    **Note:** Volatile is not suitable for compound operations like `count++`. Use `AtomicInteger` or `synchronized` for such cases.

    **[⬆ Back to Top](#table-of-contents)**

36. ### What is the transient keyword in Java?

    The `transient` keyword in Java is used to indicate that a field should not be serialized when the object is converted to a byte stream.

    **Use Cases:**
    - Sensitive data like passwords
    - Calculated/derived fields
    - Non-serializable fields
    - Thread-local data

    ```java
    import java.io.*;

    class User implements Serializable {
        private static final long serialVersionUID = 1L;
        
        private String username;
        private transient String password;  // Will not be serialized
        private transient int loginCount;   // Will not be serialized
        
        public User(String username, String password) {
            this.username = username;
            this.password = password;
            this.loginCount = 0;
        }
        
        @Override
        public String toString() {
            return "User{username='" + username + "', password='" + password + 
                   "', loginCount=" + loginCount + "}";
        }
    }

    public class TransientDemo {
        public static void main(String[] args) {
            User user = new User("john", "secret123");
            user.loginCount = 5;
            System.out.println("Before serialization: " + user);
            
            // Serialize
            try (ObjectOutputStream oos = new ObjectOutputStream(
                    new FileOutputStream("user.ser"))) {
                oos.writeObject(user);
            } catch (IOException e) {
                e.printStackTrace();
            }
            
            // Deserialize
            try (ObjectInputStream ois = new ObjectInputStream(
                    new FileInputStream("user.ser"))) {
                User deserializedUser = (User) ois.readObject();
                System.out.println("After deserialization: " + deserializedUser);
                // Output: User{username='john', password='null', loginCount=0}
            } catch (IOException | ClassNotFoundException e) {
                e.printStackTrace();
            }
        }
    }
    ```

    **Key Points:**
    - Transient fields get default values after deserialization (null for objects, 0 for numbers, false for boolean)
    - Static fields are not serialized regardless of transient keyword
    - Can be combined with custom readObject/writeObject for complex scenarios

    **[⬆ Back to Top](#table-of-contents)**

37. ### What is serialization and deserialization?

    **Serialization** is the process of converting an object's state into a byte stream. **Deserialization** is the reverse process - converting a byte stream back into an object.

    **Why Serialization?**
    - Persist object state to file/database
    - Send objects over network
    - Deep copy objects
    - Cache objects

    ```java
    import java.io.*;

    class Employee implements Serializable {
        private static final long serialVersionUID = 1L;
        
        private String name;
        private int id;
        private transient double salary; // Not serialized
        
        public Employee(String name, int id, double salary) {
            this.name = name;
            this.id = id;
            this.salary = salary;
        }
        
        @Override
        public String toString() {
            return "Employee{name='" + name + "', id=" + id + ", salary=" + salary + "}";
        }
    }

    public class SerializationDemo {
        public static void main(String[] args) {
            Employee emp = new Employee("John", 101, 50000);
            
            // Serialization
            try (ObjectOutputStream oos = new ObjectOutputStream(
                    new FileOutputStream("employee.ser"))) {
                oos.writeObject(emp);
                System.out.println("Object serialized successfully");
            } catch (IOException e) {
                e.printStackTrace();
            }
            
            // Deserialization
            try (ObjectInputStream ois = new ObjectInputStream(
                    new FileInputStream("employee.ser"))) {
                Employee deserializedEmp = (Employee) ois.readObject();
                System.out.println("Deserialized: " + deserializedEmp);
            } catch (IOException | ClassNotFoundException e) {
                e.printStackTrace();
            }
        }
    }
    ```

    **Custom Serialization:**
    ```java
    class CustomSerializable implements Serializable {
        private String data;
        private transient String sensitiveData;
        
        private void writeObject(ObjectOutputStream oos) throws IOException {
            oos.defaultWriteObject();
            // Encrypt and write sensitive data
            oos.writeObject(encrypt(sensitiveData));
        }
        
        private void readObject(ObjectInputStream ois) 
                throws IOException, ClassNotFoundException {
            ois.defaultReadObject();
            // Decrypt sensitive data
            sensitiveData = decrypt((String) ois.readObject());
        }
        
        private String encrypt(String data) { return data; } // Placeholder
        private String decrypt(String data) { return data; } // Placeholder
    }
    ```

    **Important:** Always declare `serialVersionUID` to maintain compatibility during deserialization.

    **[⬆ Back to Top](#table-of-contents)**

38. ### What are functional interfaces in Java?

    A functional interface is an interface that contains exactly one abstract method. They are the foundation for lambda expressions in Java 8.

    **Key Characteristics:**
    - Has exactly one abstract method
    - Can have multiple default and static methods
    - Can be annotated with `@FunctionalInterface`
    - Used as target types for lambda expressions

    ```java
    @FunctionalInterface
    interface Calculator {
        int calculate(int a, int b);
        
        // Default method - allowed
        default void print(String msg) {
            System.out.println(msg);
        }
        
        // Static method - allowed
        static void info() {
            System.out.println("Calculator interface");
        }
    }

    public class FunctionalInterfaceDemo {
        public static void main(String[] args) {
            // Using lambda expression
            Calculator add = (a, b) -> a + b;
            Calculator multiply = (a, b) -> a * b;
            
            System.out.println("Sum: " + add.calculate(5, 3));      // 8
            System.out.println("Product: " + multiply.calculate(5, 3)); // 15
        }
    }
    ```

    **Built-in Functional Interfaces (java.util.function):**

    ```java
    import java.util.function.*;

    public class BuiltInFunctionalInterfaces {
        public static void main(String[] args) {
            // Predicate - takes input, returns boolean
            Predicate<Integer> isEven = n -> n % 2 == 0;
            System.out.println(isEven.test(4)); // true
            
            // Function - takes input, returns output
            Function<String, Integer> length = s -> s.length();
            System.out.println(length.apply("Hello")); // 5
            
            // Consumer - takes input, returns nothing
            Consumer<String> printer = s -> System.out.println(s);
            printer.accept("Hello"); // prints Hello
            
            // Supplier - takes nothing, returns output
            Supplier<Double> random = () -> Math.random();
            System.out.println(random.get()); // random number
            
            // BiFunction - takes two inputs, returns output
            BiFunction<Integer, Integer, Integer> add = (a, b) -> a + b;
            System.out.println(add.apply(5, 3)); // 8
            
            // UnaryOperator - takes input, returns same type
            UnaryOperator<Integer> square = n -> n * n;
            System.out.println(square.apply(5)); // 25
            
            // BinaryOperator - takes two inputs of same type, returns same type
            BinaryOperator<Integer> max = (a, b) -> a > b ? a : b;
            System.out.println(max.apply(5, 3)); // 5
        }
    }
    ```

    **[⬆ Back to Top](#table-of-contents)**

39. ### What are lambda expressions in Java?

    Lambda expressions are anonymous functions that provide a concise way to implement functional interfaces. Introduced in Java 8, they enable functional programming in Java.

    **Syntax:**
    ```
    (parameters) -> expression
    (parameters) -> { statements; }
    ```

    **Examples:**

    ```java
    import java.util.*;
    import java.util.function.*;

    public class LambdaExamples {
        public static void main(String[] args) {
            // No parameters
            Runnable runnable = () -> System.out.println("Hello Lambda!");
            runnable.run();
            
            // One parameter (parentheses optional)
            Consumer<String> consumer = s -> System.out.println(s);
            consumer.accept("Hello");
            
            // Multiple parameters
            BiFunction<Integer, Integer, Integer> add = (a, b) -> a + b;
            System.out.println(add.apply(5, 3));
            
            // With type declarations
            BiFunction<Integer, Integer, Integer> multiply = 
                (Integer a, Integer b) -> a * b;
            
            // Multiple statements (braces required)
            BiFunction<Integer, Integer, Integer> calculate = (a, b) -> {
                int sum = a + b;
                int product = a * b;
                return sum + product;
            };
            
            // With Collections
            List<String> names = Arrays.asList("John", "Jane", "Bob", "Alice");
            
            // forEach with lambda
            names.forEach(name -> System.out.println(name));
            
            // Method reference (shorthand for lambda)
            names.forEach(System.out::println);
            
            // Sorting with lambda
            names.sort((s1, s2) -> s1.compareTo(s2));
            
            // Using Comparator method reference
            names.sort(String::compareTo);
            
            // Filtering with streams
            List<String> filtered = names.stream()
                .filter(name -> name.startsWith("J"))
                .collect(Collectors.toList());
            
            // Mapping with streams
            List<Integer> lengths = names.stream()
                .map(name -> name.length())
                .collect(Collectors.toList());
        }
    }
    ```

    **Method References:**
    ```java
    // Static method reference
    Function<String, Integer> parseInt = Integer::parseInt;

    // Instance method reference
    String str = "Hello";
    Supplier<Integer> length = str::length;

    // Constructor reference
    Supplier<ArrayList<String>> listSupplier = ArrayList::new;
    ```

    **Benefits:**
    - Concise and readable code
    - Enables functional programming
    - Better support for parallel processing
    - Reduced boilerplate code

    **[⬆ Back to Top](#table-of-contents)**

40. ### What is Optional class in Java 8?

    The `Optional` class is a container object that may or may not contain a non-null value. It helps avoid `NullPointerException` and makes null handling more explicit.

    **Creating Optional:**
    ```java
    import java.util.Optional;

    public class OptionalDemo {
        public static void main(String[] args) {
            // Creating Optional
            Optional<String> empty = Optional.empty();
            Optional<String> name = Optional.of("John");
            Optional<String> nullable = Optional.ofNullable(null);
            
            // Checking if value present
            System.out.println(name.isPresent());     // true
            System.out.println(empty.isPresent());    // false
            System.out.println(empty.isEmpty());      // true (Java 11+)
            
            // Getting value
            String value = name.get();  // Returns "John"
            // String error = empty.get(); // Throws NoSuchElementException
            
            // Safe access with orElse
            String defaultName = empty.orElse("Unknown");  // "Unknown"
            
            // orElseGet - lazy evaluation
            String lazyDefault = empty.orElseGet(() -> computeDefault());
            
            // orElseThrow
            String required = name.orElseThrow(() -> 
                new IllegalArgumentException("Name is required"));
            
            // ifPresent - execute if value exists
            name.ifPresent(n -> System.out.println("Name: " + n));
            
            // ifPresentOrElse (Java 9+)
            name.ifPresentOrElse(
                n -> System.out.println("Found: " + n),
                () -> System.out.println("Not found")
            );
        }
        
        static String computeDefault() {
            return "Computed Default";
        }
    }
    ```

    **Optional with Streams:**
    ```java
    public class OptionalStreams {
        public static void main(String[] args) {
            Optional<String> name = Optional.of("  John  ");
            
            // map - transform value
            Optional<Integer> length = name.map(String::length);
            
            // Chaining operations
            String result = name
                .map(String::trim)
                .map(String::toUpperCase)
                .orElse("UNKNOWN");
            System.out.println(result);  // "JOHN"
            
            // filter - conditional
            Optional<String> filtered = name
                .filter(n -> n.trim().length() > 3);
            
            // flatMap - for nested Optionals
            Optional<Optional<String>> nested = Optional.of(Optional.of("Hello"));
            Optional<String> flat = nested.flatMap(o -> o);
        }
    }
    ```

    **Best Practices:**
    ```java
    class UserService {
        // Return Optional for methods that may not find a result
        public Optional<User> findById(int id) {
            User user = database.find(id);
            return Optional.ofNullable(user);
        }
        
        // Don't use Optional for fields or parameters
        // Bad: private Optional<String> name;
        // Good: private String name; // can be null
        
        // Don't use Optional.get() without checking
        // Bad: optional.get()
        // Good: optional.orElse(default) or optional.ifPresent(...)
    }
    ```

    **[⬆ Back to Top](#table-of-contents)**

41. ### What is the difference between Collection and Collections?

    `Collection` and `Collections` are two different concepts in Java that are often confused.

    **Collection (Interface):**
    - It is a root interface in the Java Collections Framework
    - Located in `java.util` package
    - Represents a group of objects known as elements
    - Extended by List, Set, and Queue interfaces

    **Collections (Utility Class):**
    - It is a utility class that provides static methods for collection operations
    - Located in `java.util` package
    - Contains methods for sorting, searching, shuffling, reversing, etc.
    - Cannot be instantiated (all methods are static)

    ```java
    import java.util.*;

    public class CollectionVsCollections {
        public static void main(String[] args) {
            // Collection - interface used to create a collection
            Collection<String> collection = new ArrayList<>();
            collection.add("Apple");
            collection.add("Banana");
            collection.add("Cherry");
            
            // Collections - utility class with static methods
            List<String> list = new ArrayList<>(collection);
            
            // Sorting using Collections utility
            Collections.sort(list);
            System.out.println("Sorted: " + list);
            
            // Reverse the list
            Collections.reverse(list);
            System.out.println("Reversed: " + list);
            
            // Shuffle the list
            Collections.shuffle(list);
            System.out.println("Shuffled: " + list);
            
            // Find min and max
            System.out.println("Min: " + Collections.min(list));
            System.out.println("Max: " + Collections.max(list));
            
            // Create unmodifiable collection
            List<String> unmodifiable = Collections.unmodifiableList(list);
            
            // Create synchronized collection
            List<String> syncList = Collections.synchronizedList(new ArrayList<>());
        }
    }
    ```

    | Collection | Collections |
    |------------|-------------|
    | Interface | Utility class |
    | Used to represent a group of objects | Provides static methods for operations |
    | Can be implemented | Cannot be instantiated |
    | Root of Collection hierarchy | Helper class for Collection operations |

    **[⬆ Back to Top](#table-of-contents)**

42. ### What is the difference between Set and List?

    Both Set and List are interfaces in the Java Collections Framework, but they have different characteristics:

    | List | Set |
    |------|-----|
    | Allows duplicate elements | Does not allow duplicate elements |
    | Maintains insertion order | May or may not maintain order (depends on implementation) |
    | Elements can be accessed by index | No index-based access |
    | Allows multiple null values | Allows at most one null value (HashSet, LinkedHashSet) |
    | Implementations: ArrayList, LinkedList, Vector | Implementations: HashSet, LinkedHashSet, TreeSet |

    ```java
    import java.util.*;

    public class ListVsSet {
        public static void main(String[] args) {
            // List - allows duplicates, maintains order
            List<String> list = new ArrayList<>();
            list.add("Apple");
            list.add("Banana");
            list.add("Apple");  // Duplicate allowed
            list.add(null);
            list.add(null);     // Multiple nulls allowed
            System.out.println("List: " + list);  // [Apple, Banana, Apple, null, null]
            System.out.println("Element at index 1: " + list.get(1));  // Index access
            
            // Set - no duplicates
            Set<String> hashSet = new HashSet<>();
            hashSet.add("Apple");
            hashSet.add("Banana");
            hashSet.add("Apple");  // Duplicate ignored
            hashSet.add(null);     // Only one null allowed
            System.out.println("HashSet: " + hashSet);  // Order not guaranteed
            
            // LinkedHashSet - maintains insertion order
            Set<String> linkedHashSet = new LinkedHashSet<>();
            linkedHashSet.add("Cherry");
            linkedHashSet.add("Apple");
            linkedHashSet.add("Banana");
            System.out.println("LinkedHashSet: " + linkedHashSet);  // [Cherry, Apple, Banana]
            
            // TreeSet - sorted order, no nulls
            Set<String> treeSet = new TreeSet<>();
            treeSet.add("Cherry");
            treeSet.add("Apple");
            treeSet.add("Banana");
            System.out.println("TreeSet: " + treeSet);  // [Apple, Banana, Cherry]
        }
    }
    ```

    **When to use:**
    - Use **List** when you need to maintain insertion order and allow duplicates
    - Use **Set** when you need to store unique elements only

    **[⬆ Back to Top](#table-of-contents)**

43. ### What is the difference between HashSet and TreeSet?

    Both HashSet and TreeSet implement the Set interface but have different internal implementations and characteristics:

    | HashSet | TreeSet |
    |---------|---------|
    | Uses HashMap internally | Uses TreeMap (Red-Black Tree) internally |
    | Does not maintain any order | Maintains elements in sorted (natural) order |
    | Allows one null element | Does not allow null elements |
    | O(1) for add, remove, contains | O(log n) for add, remove, contains |
    | Uses hashCode() and equals() | Uses compareTo() or Comparator |
    | Better performance for basic operations | Better when sorted order is needed |

    ```java
    import java.util.*;

    public class HashSetVsTreeSet {
        public static void main(String[] args) {
            // HashSet - no ordering, allows null
            Set<Integer> hashSet = new HashSet<>();
            hashSet.add(30);
            hashSet.add(10);
            hashSet.add(20);
            hashSet.add(null);  // Allowed
            hashSet.add(10);    // Duplicate ignored
            System.out.println("HashSet: " + hashSet);  // Order not guaranteed
            
            // TreeSet - sorted order, no null
            Set<Integer> treeSet = new TreeSet<>();
            treeSet.add(30);
            treeSet.add(10);
            treeSet.add(20);
            // treeSet.add(null);  // Throws NullPointerException
            System.out.println("TreeSet: " + treeSet);  // [10, 20, 30] - sorted
            
            // TreeSet with custom Comparator (descending order)
            Set<Integer> descendingSet = new TreeSet<>(Collections.reverseOrder());
            descendingSet.add(30);
            descendingSet.add(10);
            descendingSet.add(20);
            System.out.println("Descending TreeSet: " + descendingSet);  // [30, 20, 10]
            
            // TreeSet with custom objects
            Set<Person> personSet = new TreeSet<>(Comparator.comparing(Person::getName));
            personSet.add(new Person("John", 25));
            personSet.add(new Person("Alice", 30));
            personSet.add(new Person("Bob", 20));
            System.out.println("Person TreeSet: " + personSet);
        }
    }

    class Person {
        private String name;
        private int age;
        
        public Person(String name, int age) {
            this.name = name;
            this.age = age;
        }
        
        public String getName() { return name; }
        public int getAge() { return age; }
        
        @Override
        public String toString() {
            return name + "(" + age + ")";
        }
    }
    ```

    **[⬆ Back to Top](#table-of-contents)**

44. ### What is the diamond problem in Java?

    The diamond problem is an ambiguity that arises in multiple inheritance when a class inherits from two classes that both inherit from a common superclass. It's called "diamond" because of the shape of the inheritance diagram.

    **The Problem:**
    ```
           A
          / \
         B   C
          \ /
           D
    ```
    If class D inherits from both B and C, and both B and C override a method from A, which version should D use?

    **Java's Solution:**
    Java does not allow multiple inheritance with classes to avoid the diamond problem. However, with Java 8+ interfaces having default methods, a similar situation can occur:

    ```java
    interface A {
        default void display() {
            System.out.println("Display from A");
        }
    }

    interface B extends A {
        @Override
        default void display() {
            System.out.println("Display from B");
        }
    }

    interface C extends A {
        @Override
        default void display() {
            System.out.println("Display from C");
        }
    }

    // Diamond problem with interfaces
    class D implements B, C {
        // Must override to resolve ambiguity
        @Override
        public void display() {
            // Can choose which interface method to call
            B.super.display();  // Calls B's display
            // or
            // C.super.display();  // Calls C's display
            // or provide own implementation
            System.out.println("Display from D");
        }
    }

    public class DiamondProblem {
        public static void main(String[] args) {
            D d = new D();
            d.display();
        }
    }
    ```

    **Resolution Rules in Java:**
    1. **Class wins over interface:** If a class inherits a method from both a superclass and an interface, the class method takes precedence
    2. **Subtype wins:** More specific interface's default method is chosen over less specific one
    3. **Explicit resolution:** If still ambiguous, the class must explicitly override and specify which method to use

    ```java
    class Parent {
        void show() {
            System.out.println("Parent show");
        }
    }

    interface MyInterface {
        default void show() {
            System.out.println("Interface show");
        }
    }

    // Class method wins over interface default method
    class Child extends Parent implements MyInterface {
        // No override needed - Parent's show() is used automatically
    }
    ```

    **[⬆ Back to Top](#table-of-contents)**

45. ### What is dependency injection?

    Dependency Injection (DI) is a design pattern used to implement Inversion of Control (IoC). It allows the creation of dependent objects outside of a class and provides those objects to a class in different ways.

    **Benefits of Dependency Injection:**
    1. Loose coupling between classes
    2. Easier unit testing (mock dependencies)
    3. Better code reusability
    4. Easier maintenance and flexibility

    **Types of Dependency Injection:**

    1. **Constructor Injection:**
    ```java
    // Dependency
    interface MessageService {
        void sendMessage(String message);
    }

    class EmailService implements MessageService {
        @Override
        public void sendMessage(String message) {
            System.out.println("Email sent: " + message);
        }
    }

    class SMSService implements MessageService {
        @Override
        public void sendMessage(String message) {
            System.out.println("SMS sent: " + message);
        }
    }

    // Constructor Injection
    class NotificationService {
        private final MessageService messageService;
        
        // Dependency injected through constructor
        public NotificationService(MessageService messageService) {
            this.messageService = messageService;
        }
        
        public void notify(String message) {
            messageService.sendMessage(message);
        }
    }
    ```

    2. **Setter Injection:**
    ```java
    class NotificationService {
        private MessageService messageService;
        
        // Dependency injected through setter
        public void setMessageService(MessageService messageService) {
            this.messageService = messageService;
        }
        
        public void notify(String message) {
            messageService.sendMessage(message);
        }
    }
    ```

    3. **Interface Injection:**
    ```java
    interface MessageServiceInjector {
        void injectMessageService(MessageService service);
    }

    class NotificationService implements MessageServiceInjector {
        private MessageService messageService;
        
        @Override
        public void injectMessageService(MessageService service) {
            this.messageService = service;
        }
        
        public void notify(String message) {
            messageService.sendMessage(message);
        }
    }
    ```

    **Usage Example:**
    ```java
    public class DIExample {
        public static void main(String[] args) {
            // Create dependencies
            MessageService emailService = new EmailService();
            MessageService smsService = new SMSService();
            
            // Inject dependencies
            NotificationService notifier1 = new NotificationService(emailService);
            notifier1.notify("Hello via Email!");
            
            NotificationService notifier2 = new NotificationService(smsService);
            notifier2.notify("Hello via SMS!");
        }
    }
    ```

    **Note:** Frameworks like Spring provide automatic dependency injection using annotations like `@Autowired`, `@Inject`.

    **[⬆ Back to Top](#table-of-contents)**

46. ### What is the difference between shallow copy and deep copy?

    When copying objects in Java, there are two types of copies: shallow copy and deep copy.

    **Shallow Copy:**
    - Creates a new object but copies references to nested objects
    - Changes to nested objects affect both copies
    - Default behavior of `clone()` method

    **Deep Copy:**
    - Creates a new object and recursively copies all nested objects
    - Changes to nested objects don't affect the original
    - Requires manual implementation

    ```java
    import java.util.ArrayList;
    import java.util.List;

    class Address implements Cloneable {
        String city;
        
        public Address(String city) {
            this.city = city;
        }
        
        @Override
        protected Address clone() throws CloneNotSupportedException {
            return (Address) super.clone();
        }
        
        @Override
        public String toString() {
            return city;
        }
    }

    class Person implements Cloneable {
        String name;
        Address address;
        List<String> hobbies;
        
        public Person(String name, Address address, List<String> hobbies) {
            this.name = name;
            this.address = address;
            this.hobbies = hobbies;
        }
        
        // Shallow Copy
        public Person shallowCopy() throws CloneNotSupportedException {
            return (Person) super.clone();
        }
        
        // Deep Copy
        public Person deepCopy() throws CloneNotSupportedException {
            Person cloned = (Person) super.clone();
            cloned.address = this.address.clone();  // Clone nested object
            cloned.hobbies = new ArrayList<>(this.hobbies);  // Create new list
            return cloned;
        }
        
        @Override
        public String toString() {
            return "Person{name='" + name + "', address=" + address + ", hobbies=" + hobbies + "}";
        }
    }

    public class CopyExample {
        public static void main(String[] args) throws CloneNotSupportedException {
            List<String> hobbies = new ArrayList<>();
            hobbies.add("Reading");
            
            Person original = new Person("John", new Address("New York"), hobbies);
            
            // Shallow Copy
            Person shallowCopy = original.shallowCopy();
            
            // Deep Copy
            Person deepCopy = original.deepCopy();
            
            // Modify nested objects
            original.address.city = "Los Angeles";
            original.hobbies.add("Gaming");
            
            System.out.println("Original: " + original);
            System.out.println("Shallow Copy: " + shallowCopy);  // Address changed!
            System.out.println("Deep Copy: " + deepCopy);        // Address unchanged
        }
    }
    ```

    | Shallow Copy | Deep Copy |
    |--------------|-----------|
    | Copies object references | Copies actual objects |
    | Nested objects are shared | Nested objects are independent |
    | Faster and less memory | Slower and more memory |
    | Changes affect both copies | Changes are isolated |
    | Default clone() behavior | Requires custom implementation |

    **[⬆ Back to Top](#table-of-contents)**

47. ### What are design patterns in Java?

    Design patterns are reusable solutions to common problems in software design. They represent best practices and provide templates for solving design challenges.

    **Categories of Design Patterns:**

    1. **Creational Patterns** - Deal with object creation mechanisms
       - Singleton
       - Factory Method
       - Abstract Factory
       - Builder
       - Prototype

    2. **Structural Patterns** - Deal with object composition
       - Adapter
       - Bridge
       - Composite
       - Decorator
       - Facade
       - Flyweight
       - Proxy

    3. **Behavioral Patterns** - Deal with object interaction
       - Chain of Responsibility
       - Command
       - Iterator
       - Mediator
       - Memento
       - Observer
       - State
       - Strategy
       - Template Method
       - Visitor

    **Common Design Patterns Examples:**

    ```java
    // 1. SINGLETON - Only one instance
    public class Singleton {
        private static Singleton instance;
        private Singleton() {}
        public static synchronized Singleton getInstance() {
            if (instance == null) {
                instance = new Singleton();
            }
            return instance;
        }
    }

    // 2. FACTORY - Creates objects without exposing creation logic
    interface Animal {
        void speak();
    }
    class Dog implements Animal {
        public void speak() { System.out.println("Woof!"); }
    }
    class Cat implements Animal {
        public void speak() { System.out.println("Meow!"); }
    }
    class AnimalFactory {
        public static Animal createAnimal(String type) {
            return switch (type.toLowerCase()) {
                case "dog" -> new Dog();
                case "cat" -> new Cat();
                default -> throw new IllegalArgumentException("Unknown animal");
            };
        }
    }

    // 3. OBSERVER - One-to-many dependency
    interface Observer {
        void update(String message);
    }
    class NewsSubscriber implements Observer {
        private String name;
        public NewsSubscriber(String name) { this.name = name; }
        public void update(String message) {
            System.out.println(name + " received: " + message);
        }
    }

    // 4. STRATEGY - Family of interchangeable algorithms
    interface PaymentStrategy {
        void pay(int amount);
    }
    class CreditCardPayment implements PaymentStrategy {
        public void pay(int amount) {
            System.out.println("Paid $" + amount + " with Credit Card");
        }
    }
    class PayPalPayment implements PaymentStrategy {
        public void pay(int amount) {
            System.out.println("Paid $" + amount + " with PayPal");
        }
    }

    // 5. DECORATOR - Add behavior dynamically
    interface Coffee {
        double getCost();
        String getDescription();
    }
    class SimpleCoffee implements Coffee {
        public double getCost() { return 2.0; }
        public String getDescription() { return "Simple Coffee"; }
    }
    class MilkDecorator implements Coffee {
        private Coffee coffee;
        public MilkDecorator(Coffee coffee) { this.coffee = coffee; }
        public double getCost() { return coffee.getCost() + 0.5; }
        public String getDescription() { return coffee.getDescription() + ", Milk"; }
    }
    ```

    **[⬆ Back to Top](#table-of-contents)**

48. ### What is the factory design pattern?

    The Factory Design Pattern is a creational pattern that provides an interface for creating objects without specifying their exact classes. It delegates the instantiation logic to subclasses or factory methods.

    **Types of Factory Patterns:**

    1. **Simple Factory (Static Factory Method):**
    ```java
    interface Shape {
        void draw();
    }

    class Circle implements Shape {
        @Override
        public void draw() {
            System.out.println("Drawing Circle");
        }
    }

    class Rectangle implements Shape {
        @Override
        public void draw() {
            System.out.println("Drawing Rectangle");
        }
    }

    class Triangle implements Shape {
        @Override
        public void draw() {
            System.out.println("Drawing Triangle");
        }
    }

    // Simple Factory
    class ShapeFactory {
        public static Shape createShape(String shapeType) {
            if (shapeType == null) {
                return null;
            }
            return switch (shapeType.toUpperCase()) {
                case "CIRCLE" -> new Circle();
                case "RECTANGLE" -> new Rectangle();
                case "TRIANGLE" -> new Triangle();
                default -> throw new IllegalArgumentException("Unknown shape: " + shapeType);
            };
        }
    }

    public class SimpleFactoryDemo {
        public static void main(String[] args) {
            Shape circle = ShapeFactory.createShape("CIRCLE");
            circle.draw();
            
            Shape rectangle = ShapeFactory.createShape("RECTANGLE");
            rectangle.draw();
        }
    }
    ```

    2. **Factory Method Pattern:**
    ```java
    // Product interface
    interface Vehicle {
        void drive();
    }

    class Car implements Vehicle {
        @Override
        public void drive() {
            System.out.println("Driving a car");
        }
    }

    class Motorcycle implements Vehicle {
        @Override
        public void drive() {
            System.out.println("Riding a motorcycle");
        }
    }

    // Creator abstract class
    abstract class VehicleFactory {
        // Factory method
        public abstract Vehicle createVehicle();
        
        public void deliverVehicle() {
            Vehicle vehicle = createVehicle();
            System.out.println("Delivering vehicle...");
            vehicle.drive();
        }
    }

    class CarFactory extends VehicleFactory {
        @Override
        public Vehicle createVehicle() {
            return new Car();
        }
    }

    class MotorcycleFactory extends VehicleFactory {
        @Override
        public Vehicle createVehicle() {
            return new Motorcycle();
        }
    }

    public class FactoryMethodDemo {
        public static void main(String[] args) {
            VehicleFactory carFactory = new CarFactory();
            carFactory.deliverVehicle();
            
            VehicleFactory motorcycleFactory = new MotorcycleFactory();
            motorcycleFactory.deliverVehicle();
        }
    }
    ```

    **Benefits:**
    - Loose coupling between creator and products
    - Single Responsibility Principle - creation code in one place
    - Open/Closed Principle - easy to add new product types
    - Easier unit testing with mock objects

    **[⬆ Back to Top](#table-of-contents)**

49. ### What is the builder design pattern?

    The Builder Design Pattern is a creational pattern that separates the construction of a complex object from its representation. It allows step-by-step construction of objects and produces different representations using the same construction process.

    **When to use:**
    - When object has many optional parameters
    - When object creation involves many steps
    - When you want immutable objects with many fields

    ```java
    // Product class with many fields
    class Computer {
        // Required parameters
        private final String processor;
        private final int ram;
        
        // Optional parameters
        private final int storage;
        private final boolean hasGraphicsCard;
        private final boolean hasBluetooth;
        private final boolean hasWifi;
        private final String operatingSystem;
        
        private Computer(ComputerBuilder builder) {
            this.processor = builder.processor;
            this.ram = builder.ram;
            this.storage = builder.storage;
            this.hasGraphicsCard = builder.hasGraphicsCard;
            this.hasBluetooth = builder.hasBluetooth;
            this.hasWifi = builder.hasWifi;
            this.operatingSystem = builder.operatingSystem;
        }
        
        // Getters
        public String getProcessor() { return processor; }
        public int getRam() { return ram; }
        public int getStorage() { return storage; }
        public boolean hasGraphicsCard() { return hasGraphicsCard; }
        public boolean hasBluetooth() { return hasBluetooth; }
        public boolean hasWifi() { return hasWifi; }
        public String getOperatingSystem() { return operatingSystem; }
        
        @Override
        public String toString() {
            return "Computer{" +
                "processor='" + processor + '\'' +
                ", ram=" + ram + "GB" +
                ", storage=" + storage + "GB" +
                ", graphicsCard=" + hasGraphicsCard +
                ", bluetooth=" + hasBluetooth +
                ", wifi=" + hasWifi +
                ", OS='" + operatingSystem + '\'' +
                '}';
        }
        
        // Static Builder class
        public static class ComputerBuilder {
            // Required parameters
            private final String processor;
            private final int ram;
            
            // Optional parameters with default values
            private int storage = 256;
            private boolean hasGraphicsCard = false;
            private boolean hasBluetooth = true;
            private boolean hasWifi = true;
            private String operatingSystem = "Windows";
            
            // Constructor with required parameters
            public ComputerBuilder(String processor, int ram) {
                this.processor = processor;
                this.ram = ram;
            }
            
            // Builder methods for optional parameters
            public ComputerBuilder storage(int storage) {
                this.storage = storage;
                return this;
            }
            
            public ComputerBuilder graphicsCard(boolean hasGraphicsCard) {
                this.hasGraphicsCard = hasGraphicsCard;
                return this;
            }
            
            public ComputerBuilder bluetooth(boolean hasBluetooth) {
                this.hasBluetooth = hasBluetooth;
                return this;
            }
            
            public ComputerBuilder wifi(boolean hasWifi) {
                this.hasWifi = hasWifi;
                return this;
            }
            
            public ComputerBuilder operatingSystem(String operatingSystem) {
                this.operatingSystem = operatingSystem;
                return this;
            }
            
            // Build method to create the final object
            public Computer build() {
                return new Computer(this);
            }
        }
    }

    public class BuilderPatternDemo {
        public static void main(String[] args) {
            // Building a gaming computer
            Computer gamingPC = new Computer.ComputerBuilder("Intel i9", 32)
                .storage(1000)
                .graphicsCard(true)
                .bluetooth(true)
                .wifi(true)
                .operatingSystem("Windows 11")
                .build();
            
            System.out.println("Gaming PC: " + gamingPC);
            
            // Building a basic computer with defaults
            Computer basicPC = new Computer.ComputerBuilder("Intel i3", 8)
                .build();
            
            System.out.println("Basic PC: " + basicPC);
            
            // Building a Mac
            Computer mac = new Computer.ComputerBuilder("Apple M2", 16)
                .storage(512)
                .operatingSystem("macOS")
                .build();
            
            System.out.println("Mac: " + mac);
        }
    }
    ```

    **Benefits:**
    - Readable code with method chaining (fluent interface)
    - Immutable objects can be created easily
    - Clear separation of construction and representation
    - Avoids telescoping constructor anti-pattern

    **[⬆ Back to Top](#table-of-contents)**

50. ### What is the difference between Heap and Stack memory?

    Java memory is divided into two main areas: Heap and Stack. Understanding their differences is crucial for memory management.

    | Stack Memory | Heap Memory |
    |--------------|-------------|
    | Stores method calls and local variables | Stores objects and instance variables |
    | LIFO (Last In First Out) structure | No specific order |
    | Thread-safe (each thread has own stack) | Shared among all threads |
    | Memory allocation/deallocation is automatic | Managed by Garbage Collector |
    | Fixed size (can cause StackOverflowError) | Dynamic size (can cause OutOfMemoryError) |
    | Faster access | Slower access |
    | Stores primitive values and references | Stores actual objects |

    ```java
    public class MemoryExample {
        // Instance variable - stored in Heap
        private int instanceVar = 10;
        
        // Static variable - stored in Method Area (part of Heap in modern JVMs)
        private static int staticVar = 20;
        
        public void demonstrate() {
            // Local primitive - stored in Stack
            int localPrimitive = 30;
            
            // Local reference - reference in Stack, object in Heap
            String localString = new String("Hello");
            
            // Object created in Heap
            Person person = new Person("John", 25);
            
            // Array - reference in Stack, array object in Heap
            int[] numbers = new int[5];
        }
        
        public static void main(String[] args) {
            // Reference 'obj' in Stack, object in Heap
            MemoryExample obj = new MemoryExample();
            obj.demonstrate();
            
            // Recursive call can cause StackOverflowError
            // recursiveMethod(); // Uncomment to see StackOverflowError
        }
        
        public static void recursiveMethod() {
            recursiveMethod(); // Infinite recursion - StackOverflowError
        }
    }

    class Person {
        String name;  // Reference in Heap, String object in Heap
        int age;      // Primitive stored in Heap (as part of object)
        
        Person(String name, int age) {
            this.name = name;
            this.age = age;
        }
    }
    ```

    **Memory Visualization:**
    ```
    STACK                          HEAP
    ┌─────────────────┐            ┌─────────────────────────────────┐
    │ main() frame    │            │                                 │
    │  obj (reference)│──────────► │  MemoryExample object           │
    │                 │            │    instanceVar = 10             │
    ├─────────────────┤            │                                 │
    │ demonstrate()   │            ├─────────────────────────────────┤
    │  localPrimitive │            │                                 │
    │  = 30           │            │  String object "Hello"          │
    │  localString ───│──────────► │                                 │
    │  person ────────│──────────► │  Person object                  │
    │  numbers ───────│──────────► │    name (ref) ──► "John"        │
    └─────────────────┘            │    age = 25                     │
                                   │                                 │
                                   │  int[5] array                   │
                                   └─────────────────────────────────┘
    ```

    **[⬆ Back to Top](#table-of-contents)**

51. ### What is garbage collection in Java?

    Garbage Collection (GC) is an automatic memory management feature in Java that identifies and removes objects that are no longer in use, freeing up heap memory for new objects.

    **How Garbage Collection Works:**

    1. **Mark Phase:** GC identifies which objects are still reachable (in use)
    2. **Sweep Phase:** GC removes unreachable objects
    3. **Compact Phase (optional):** GC compacts remaining objects to reduce fragmentation

    **When does an object become eligible for GC?**
    - When no references point to it
    - When reference is set to null
    - When reference is reassigned
    - When object goes out of scope

    ```java
    public class GarbageCollectionDemo {
        
        public static void main(String[] args) {
            // Object created - not eligible for GC
            Object obj1 = new Object();
            
            // Reference set to null - obj1's object eligible for GC
            obj1 = null;
            
            // Object reassignment - first object eligible for GC
            Object obj2 = new Object();
            obj2 = new Object();  // First object now eligible for GC
            
            // Objects in method scope
            createObjects();
            // After method returns, local objects are eligible for GC
            
            // Request garbage collection (not guaranteed to run immediately)
            System.gc();
            // or
            Runtime.getRuntime().gc();
        }
        
        static void createObjects() {
            Object localObj = new Object();
            // localObj goes out of scope when method returns
        }
    }

    // Using finalize() - deprecated but shows GC callback
    class MyObject {
        private String name;
        
        public MyObject(String name) {
            this.name = name;
            System.out.println(name + " created");
        }
        
        @Override
        protected void finalize() throws Throwable {
            System.out.println(name + " is being garbage collected");
            super.finalize();
        }
    }

    // Demonstrating object eligibility
    class GCEligibility {
        public static void main(String[] args) throws InterruptedException {
            // Island of isolation - objects reference each other but unreachable
            MyObject a = new MyObject("A");
            MyObject b = new MyObject("B");
            
            // Create circular reference
            // a.partner = b;
            // b.partner = a;
            
            // Both become eligible for GC (island of isolation)
            a = null;
            b = null;
            
            // Request GC
            System.gc();
            Thread.sleep(1000);  // Give GC time to run
        }
    }
    ```

    **JVM Heap Generations:**
    ```
    ┌────────────────────────────────────────────────────────────┐
    │                          HEAP                              │
    ├─────────────────────────────┬──────────────────────────────┤
    │     Young Generation        │      Old Generation          │
    │  ┌───────┬───────┬───────┐  │      (Tenured)               │
    │  │ Eden  │  S0   │  S1   │  │                              │
    │  │       │(From) │ (To)  │  │   Long-lived objects         │
    │  │ New   │       │       │  │                              │
    │  │objects│Survivor Spaces│  │                              │
    │  └───────┴───────┴───────┘  │                              │
    └─────────────────────────────┴──────────────────────────────┘
    ```

    **GC Process:**
    1. New objects are allocated in Eden space
    2. When Eden fills up, Minor GC occurs
    3. Surviving objects move to Survivor space
    4. Objects that survive multiple Minor GCs move to Old Generation
    5. When Old Generation fills up, Major GC (Full GC) occurs

    **JVM GC Options:**
    ```bash
    # Set heap size
    java -Xms256m -Xmx1024m MyApp
    
    # Choose garbage collector
    java -XX:+UseG1GC MyApp          # G1 Garbage Collector
    java -XX:+UseParallelGC MyApp    # Parallel GC
    java -XX:+UseZGC MyApp           # Z Garbage Collector (Java 11+)
    
    # GC logging
    java -Xlog:gc* MyApp             # Java 9+
    ```

    **[⬆ Back to Top](#table-of-contents)**

52. ### What are the different types of garbage collectors in Java?

    Java provides several garbage collector implementations, each optimized for different scenarios:

    **1. Serial Garbage Collector (-XX:+UseSerialGC)**
    - Uses single thread for garbage collection
    - Best for single-threaded applications
    - Causes "stop-the-world" pauses
    - Suitable for small applications with small heaps

    **2. Parallel Garbage Collector (-XX:+UseParallelGC)**
    - Uses multiple threads for garbage collection
    - Also known as "throughput collector"
    - Default GC in Java 8
    - Good for multi-threaded applications requiring high throughput

    **3. G1 Garbage Collector (-XX:+UseG1GC)**
    - Divides heap into regions
    - Designed for large heaps (> 4GB)
    - Default GC from Java 9 onwards
    - Balances throughput and latency
    - Predictable pause times

    **4. Z Garbage Collector (-XX:+UseZGC)**
    - Introduced in Java 11
    - Ultra-low latency (< 10ms pause times)
    - Handles heaps from 8MB to 16TB
    - Concurrent garbage collection

    **5. Shenandoah Garbage Collector (-XX:+UseShenandoahGC)**
    - Low pause time garbage collector
    - Performs concurrent compaction
    - Available in OpenJDK

    ```java
    public class GCDemo {
        public static void main(String[] args) {
            // Check current garbage collector
            java.lang.management.GarbageCollectorMXBean gc;
            for (java.lang.management.GarbageCollectorMXBean bean : 
                    java.lang.management.ManagementFactory.getGarbageCollectorMXBeans()) {
                System.out.println("GC Name: " + bean.getName());
                System.out.println("Collection Count: " + bean.getCollectionCount());
                System.out.println("Collection Time: " + bean.getCollectionTime() + "ms");
            }
        }
    }
    ```

    **JVM Options for GC:**
    ```bash
    # Serial GC
    java -XX:+UseSerialGC -jar app.jar

    # Parallel GC
    java -XX:+UseParallelGC -XX:ParallelGCThreads=4 -jar app.jar

    # G1 GC
    java -XX:+UseG1GC -XX:MaxGCPauseMillis=200 -jar app.jar

    # ZGC
    java -XX:+UseZGC -jar app.jar
    ```

    | GC Type | Best For | Pause Time | Throughput |
    |---------|----------|------------|------------|
    | Serial | Small apps | High | Low |
    | Parallel | Throughput apps | Medium | High |
    | G1 | Large heaps | Low-Medium | Medium-High |
    | ZGC | Low latency | Very Low | Medium |

    **[⬆ Back to Top](#table-of-contents)**

53. ### What is the difference between wait() and sleep() methods?

    Both `wait()` and `sleep()` are used to pause thread execution, but they have significant differences:

    | wait() | sleep() |
    |--------|---------|
    | Defined in Object class | Defined in Thread class |
    | Releases the lock/monitor | Does not release the lock |
    | Must be called from synchronized context | Can be called from anywhere |
    | Can be woken up by notify()/notifyAll() | Cannot be woken up (except interrupt) |
    | Used for inter-thread communication | Used for introducing delay |
    | Instance method | Static method |

    ```java
    public class WaitVsSleep {
        private static final Object lock = new Object();
        
        public static void main(String[] args) {
            // Demonstrating sleep()
            Thread sleepThread = new Thread(() -> {
                System.out.println("Sleep thread starting...");
                try {
                    Thread.sleep(2000);  // Sleeps for 2 seconds
                } catch (InterruptedException e) {
                    e.printStackTrace();
                }
                System.out.println("Sleep thread woke up!");
            });
            
            // Demonstrating wait()
            Thread waitThread = new Thread(() -> {
                synchronized (lock) {
                    System.out.println("Wait thread starting...");
                    try {
                        lock.wait(2000);  // Waits for 2 seconds or until notified
                    } catch (InterruptedException e) {
                        e.printStackTrace();
                    }
                    System.out.println("Wait thread woke up!");
                }
            });
            
            // Notify thread
            Thread notifyThread = new Thread(() -> {
                try {
                    Thread.sleep(1000);  // Wait 1 second
                } catch (InterruptedException e) {
                    e.printStackTrace();
                }
                synchronized (lock) {
                    System.out.println("Notifying...");
                    lock.notify();  // Wakes up the waiting thread
                }
            });
            
            sleepThread.start();
            waitThread.start();
            notifyThread.start();
        }
    }
    ```

    **Key Points:**
    - `wait()` is used for coordination between threads
    - `sleep()` is used to pause execution for a specific time
    - Always call `wait()` inside a synchronized block
    - `wait()` can be interrupted by `notify()` before timeout

    **[⬆ Back to Top](#table-of-contents)**

54. ### What is the difference between notify() and notifyAll()?

    Both `notify()` and `notifyAll()` are methods in the Object class used to wake up threads waiting on an object's monitor.

    | notify() | notifyAll() |
    |----------|-------------|
    | Wakes up only one waiting thread | Wakes up all waiting threads |
    | Which thread is woken is not guaranteed | All threads compete for the lock |
    | More efficient when only one thread needs to proceed | Safer when multiple threads may need the resource |
    | Can cause thread starvation | No starvation, but more overhead |

    ```java
    public class NotifyVsNotifyAll {
        private static final Object lock = new Object();
        private static boolean resourceAvailable = false;
        
        public static void main(String[] args) throws InterruptedException {
            // Create multiple waiting threads
            for (int i = 1; i <= 3; i++) {
                final int threadNum = i;
                new Thread(() -> {
                    synchronized (lock) {
                        while (!resourceAvailable) {
                            System.out.println("Thread " + threadNum + " waiting...");
                            try {
                                lock.wait();
                            } catch (InterruptedException e) {
                                e.printStackTrace();
                            }
                        }
                        System.out.println("Thread " + threadNum + " got the resource!");
                    }
                }).start();
            }
            
            Thread.sleep(1000);  // Let all threads start waiting
            
            // Using notify() - wakes only ONE thread
            synchronized (lock) {
                System.out.println("\nCalling notify()...");
                resourceAvailable = true;
                lock.notify();  // Only one thread wakes up
            }
            
            Thread.sleep(1000);
            
            // Reset and demonstrate notifyAll()
            resourceAvailable = false;
            
            // Create more waiting threads
            for (int i = 4; i <= 6; i++) {
                final int threadNum = i;
                new Thread(() -> {
                    synchronized (lock) {
                        while (!resourceAvailable) {
                            System.out.println("Thread " + threadNum + " waiting...");
                            try {
                                lock.wait();
                            } catch (InterruptedException e) {
                                e.printStackTrace();
                            }
                        }
                        System.out.println("Thread " + threadNum + " got the resource!");
                    }
                }).start();
            }
            
            Thread.sleep(1000);
            
            // Using notifyAll() - wakes ALL threads
            synchronized (lock) {
                System.out.println("\nCalling notifyAll()...");
                resourceAvailable = true;
                lock.notifyAll();  // All threads wake up
            }
        }
    }
    ```

    **When to use:**
    - Use `notify()` when only one thread can proceed (e.g., single resource)
    - Use `notifyAll()` when multiple threads might be able to proceed or when condition varies

    **[⬆ Back to Top](#table-of-contents)**

55. ### What is an immutable class and how to create one?

    An immutable class is a class whose instances cannot be modified after creation. Once an object is created, its state remains constant throughout its lifetime.

    **Benefits of Immutability:**
    - Thread-safe without synchronization
    - Can be safely shared and cached
    - Good for hash keys (hashCode never changes)
    - Easier to reason about

    **Rules for Creating Immutable Class:**
    1. Declare the class as `final`
    2. Make all fields `private` and `final`
    3. Don't provide setter methods
    4. Initialize all fields via constructor
    5. Perform deep copy for mutable objects
    6. Return copies of mutable objects in getters

    ```java
    import java.util.ArrayList;
    import java.util.Collections;
    import java.util.List;

    // Immutable class example
    public final class ImmutablePerson {
        private final String name;
        private final int age;
        private final List<String> hobbies;
        
        public ImmutablePerson(String name, int age, List<String> hobbies) {
            this.name = name;
            this.age = age;
            // Deep copy of mutable object
            this.hobbies = new ArrayList<>(hobbies);
        }
        
        public String getName() {
            return name;
        }
        
        public int getAge() {
            return age;
        }
        
        // Return unmodifiable copy to prevent modification
        public List<String> getHobbies() {
            return Collections.unmodifiableList(hobbies);
        }
        
        // Method that appears to modify but returns new instance
        public ImmutablePerson withAge(int newAge) {
            return new ImmutablePerson(this.name, newAge, this.hobbies);
        }
        
        @Override
        public String toString() {
            return "ImmutablePerson{name='" + name + "', age=" + age + 
                   ", hobbies=" + hobbies + "}";
        }
    }

    // Usage
    class ImmutableDemo {
        public static void main(String[] args) {
            List<String> hobbies = new ArrayList<>();
            hobbies.add("Reading");
            hobbies.add("Gaming");
            
            ImmutablePerson person = new ImmutablePerson("John", 25, hobbies);
            System.out.println("Original: " + person);
            
            // Original list modification doesn't affect the object
            hobbies.add("Cooking");
            System.out.println("After modifying original list: " + person);
            
            // Cannot modify returned list
            // person.getHobbies().add("Swimming"); // Throws UnsupportedOperationException
            
            // Create new instance with different age
            ImmutablePerson olderPerson = person.withAge(30);
            System.out.println("New person: " + olderPerson);
            System.out.println("Original unchanged: " + person);
        }
    }
    ```

    **Java Record (Java 14+):**
    ```java
    // Records are immutable by default
    public record Person(String name, int age) {
        // Automatically generates constructor, getters, equals, hashCode, toString
    }
    ```

    **[⬆ Back to Top](#table-of-contents)**

56. ### What is the difference between String, StringBuilder, and StringBuffer?

    All three are used to handle strings in Java, but they have different characteristics:

    | Feature | String | StringBuilder | StringBuffer |
    |---------|--------|---------------|--------------|
    | Mutability | Immutable | Mutable | Mutable |
    | Thread Safety | Thread-safe (immutable) | Not thread-safe | Thread-safe (synchronized) |
    | Performance | Slower for concatenation | Fastest | Slower than StringBuilder |
    | Storage | String Pool | Heap | Heap |
    | Since | Java 1.0 | Java 1.5 | Java 1.0 |

    ```java
    public class StringComparison {
        public static void main(String[] args) {
            // String - immutable
            String str = "Hello";
            str = str + " World";  // Creates new String object
            System.out.println("String: " + str);
            
            // StringBuilder - mutable, not thread-safe
            StringBuilder sb = new StringBuilder("Hello");
            sb.append(" World");  // Modifies same object
            System.out.println("StringBuilder: " + sb);
            
            // StringBuffer - mutable, thread-safe
            StringBuffer sbuf = new StringBuffer("Hello");
            sbuf.append(" World");  // Modifies same object
            System.out.println("StringBuffer: " + sbuf);
            
            // Performance comparison
            long startTime, endTime;
            
            // String concatenation (slow)
            startTime = System.currentTimeMillis();
            String s = "";
            for (int i = 0; i < 100000; i++) {
                s += "a";
            }
            endTime = System.currentTimeMillis();
            System.out.println("String time: " + (endTime - startTime) + "ms");
            
            // StringBuilder (fast)
            startTime = System.currentTimeMillis();
            StringBuilder sb2 = new StringBuilder();
            for (int i = 0; i < 100000; i++) {
                sb2.append("a");
            }
            endTime = System.currentTimeMillis();
            System.out.println("StringBuilder time: " + (endTime - startTime) + "ms");
            
            // StringBuffer (moderate)
            startTime = System.currentTimeMillis();
            StringBuffer sbuf2 = new StringBuffer();
            for (int i = 0; i < 100000; i++) {
                sbuf2.append("a");
            }
            endTime = System.currentTimeMillis();
            System.out.println("StringBuffer time: " + (endTime - startTime) + "ms");
        }
    }
    ```

    **Common Methods (StringBuilder/StringBuffer):**
    ```java
    StringBuilder sb = new StringBuilder("Hello");
    sb.append(" World");           // Append
    sb.insert(5, ",");             // Insert at position
    sb.delete(5, 6);               // Delete range
    sb.reverse();                  // Reverse
    sb.replace(0, 5, "Hi");        // Replace range
    String result = sb.toString(); // Convert to String
    ```

    **When to use:**
    - **String:** When string won't change much
    - **StringBuilder:** When string changes frequently (single-threaded)
    - **StringBuffer:** When string changes frequently (multi-threaded)

    **[⬆ Back to Top](#table-of-contents)**

57. ### What is the difference between static and instance variables?

    Static variables belong to the class, while instance variables belong to individual objects.

    | Static Variable | Instance Variable |
    |-----------------|-------------------|
    | Belongs to class | Belongs to object |
    | Single copy shared by all instances | Each instance has its own copy |
    | Declared with `static` keyword | Declared without `static` keyword |
    | Accessed via class name | Accessed via object reference |
    | Memory allocated once when class loads | Memory allocated when object is created |
    | Stored in Method Area | Stored in Heap |

    ```java
    public class Employee {
        // Static variable - shared by all instances
        private static int employeeCount = 0;
        private static String companyName = "TechCorp";
        
        // Instance variables - unique to each instance
        private int id;
        private String name;
        private double salary;
        
        public Employee(String name, double salary) {
            this.name = name;
            this.salary = salary;
            this.id = ++employeeCount;  // Use static counter
        }
        
        // Static method - can only access static members
        public static int getEmployeeCount() {
            return employeeCount;
        }
        
        public static String getCompanyName() {
            return companyName;
        }
        
        // Instance method - can access both static and instance members
        public void displayInfo() {
            System.out.println("ID: " + id);
            System.out.println("Name: " + name);
            System.out.println("Salary: " + salary);
            System.out.println("Company: " + companyName);  // Accessing static
        }
        
        public static void main(String[] args) {
            // Accessing static variable before creating any object
            System.out.println("Company: " + Employee.companyName);
            System.out.println("Initial count: " + Employee.getEmployeeCount());
            
            // Create instances
            Employee emp1 = new Employee("John", 50000);
            Employee emp2 = new Employee("Jane", 60000);
            Employee emp3 = new Employee("Bob", 55000);
            
            // Each has unique instance variables
            emp1.displayInfo();
            System.out.println();
            emp2.displayInfo();
            
            // Static variable is shared
            System.out.println("\nTotal employees: " + Employee.getEmployeeCount());
            
            // Change static variable - affects all
            Employee.companyName = "NewTechCorp";
            System.out.println("\nAfter company name change:");
            emp1.displayInfo();
            emp2.displayInfo();
        }
    }
    ```

    **Static Block:**
    ```java
    class StaticDemo {
        static int value;
        
        // Static block - executed once when class loads
        static {
            System.out.println("Static block executed");
            value = 100;
        }
    }
    ```

    **[⬆ Back to Top](#table-of-contents)**

58. ### What is the purpose of the super keyword?

    The `super` keyword in Java is used to refer to the immediate parent class. It has three main uses:

    **1. Access Parent Class Variables:**
    ```java
    class Animal {
        String name = "Animal";
    }

    class Dog extends Animal {
        String name = "Dog";
        
        void displayNames() {
            System.out.println("Child name: " + name);
            System.out.println("Parent name: " + super.name);
        }
    }
    ```

    **2. Call Parent Class Methods:**
    ```java
    class Animal {
        void eat() {
            System.out.println("Animal is eating");
        }
    }

    class Dog extends Animal {
        @Override
        void eat() {
            super.eat();  // Call parent method first
            System.out.println("Dog is eating dog food");
        }
    }
    ```

    **3. Call Parent Class Constructor:**
    ```java
    class Person {
        String name;
        int age;
        
        Person(String name, int age) {
            this.name = name;
            this.age = age;
        }
    }

    class Employee extends Person {
        String department;
        double salary;
        
        Employee(String name, int age, String department, double salary) {
            super(name, age);  // Call parent constructor (must be first statement)
            this.department = department;
            this.salary = salary;
        }
    }
    ```

    **Complete Example:**
    ```java
    class Vehicle {
        String brand = "Generic";
        int maxSpeed = 100;
        
        Vehicle() {
            System.out.println("Vehicle constructor");
        }
        
        Vehicle(String brand, int maxSpeed) {
            this.brand = brand;
            this.maxSpeed = maxSpeed;
            System.out.println("Vehicle parameterized constructor");
        }
        
        void start() {
            System.out.println("Vehicle starting...");
        }
        
        void displayInfo() {
            System.out.println("Brand: " + brand + ", Max Speed: " + maxSpeed);
        }
    }

    class Car extends Vehicle {
        String brand = "Car Brand";  // Hides parent variable
        int numDoors;
        
        Car(String brand, int maxSpeed, int numDoors) {
            super(brand, maxSpeed);  // Call parent constructor
            this.numDoors = numDoors;
            System.out.println("Car constructor");
        }
        
        @Override
        void start() {
            super.start();  // Call parent method
            System.out.println("Car engine started!");
        }
        
        void showBrands() {
            System.out.println("Car brand field: " + brand);
            System.out.println("Parent brand field: " + super.brand);
        }
    }

    public class SuperDemo {
        public static void main(String[] args) {
            Car car = new Car("Toyota", 200, 4);
            car.start();
            car.showBrands();
            car.displayInfo();
        }
    }
    ```

    **[⬆ Back to Top](#table-of-contents)**

59. ### What is the purpose of the this keyword?

    The `this` keyword in Java refers to the current object instance. It has several uses:

    **1. Distinguish Instance Variables from Parameters:**
    ```java
    class Person {
        String name;
        int age;
        
        Person(String name, int age) {
            this.name = name;  // this.name refers to instance variable
            this.age = age;    // age (right) is the parameter
        }
    }
    ```

    **2. Call Another Constructor (Constructor Chaining):**
    ```java
    class Employee {
        String name;
        int age;
        String department;
        
        Employee() {
            this("Unknown", 0, "General");  // Call parameterized constructor
        }
        
        Employee(String name) {
            this(name, 0, "General");
        }
        
        Employee(String name, int age, String department) {
            this.name = name;
            this.age = age;
            this.department = department;
        }
    }
    ```

    **3. Pass Current Object as Parameter:**
    ```java
    class Calculator {
        int value;
        
        Calculator(int value) {
            this.value = value;
        }
        
        void display(Calculator calc) {
            System.out.println("Value: " + calc.value);
        }
        
        void show() {
            display(this);  // Pass current object
        }
    }
    ```

    **4. Return Current Object (Method Chaining/Fluent Interface):**
    ```java
    class Builder {
        private String name;
        private int age;
        private String email;
        
        Builder setName(String name) {
            this.name = name;
            return this;  // Return current object for chaining
        }
        
        Builder setAge(int age) {
            this.age = age;
            return this;
        }
        
        Builder setEmail(String email) {
            this.email = email;
            return this;
        }
        
        void build() {
            System.out.println("Name: " + name + ", Age: " + age + ", Email: " + email);
        }
    }

    // Usage with method chaining
    class ThisDemo {
        public static void main(String[] args) {
            new Builder()
                .setName("John")
                .setAge(25)
                .setEmail("john@example.com")
                .build();
        }
    }
    ```

    **5. Reference Current Class Instance in Inner Class:**
    ```java
    class Outer {
        int value = 10;
        
        class Inner {
            int value = 20;
            
            void display() {
                int value = 30;
                System.out.println("Local: " + value);
                System.out.println("Inner: " + this.value);
                System.out.println("Outer: " + Outer.this.value);
            }
        }
    }
    ```

    **[⬆ Back to Top](#table-of-contents)**

60. ### What are generics in Java?

    Generics enable types (classes and interfaces) to be parameters when defining classes, interfaces, and methods. They provide compile-time type safety and eliminate the need for casting.

    **Benefits of Generics:**
    - Type safety at compile time
    - Elimination of casts
    - Code reusability
    - Enable generic algorithms

    **Generic Class:**
    ```java
    // Generic class with type parameter T
    class Box<T> {
        private T content;
        
        public void set(T content) {
            this.content = content;
        }
        
        public T get() {
            return content;
        }
    }

    // Multiple type parameters
    class Pair<K, V> {
        private K key;
        private V value;
        
        public Pair(K key, V value) {
            this.key = key;
            this.value = value;
        }
        
        public K getKey() { return key; }
        public V getValue() { return value; }
    }
    ```

    **Generic Method:**
    ```java
    class Utilities {
        // Generic method
        public static <T> void printArray(T[] array) {
            for (T element : array) {
                System.out.print(element + " ");
            }
            System.out.println();
        }
        
        // Generic method with return type
        public static <T> T getFirst(List<T> list) {
            return list.isEmpty() ? null : list.get(0);
        }
        
        // Multiple type parameters
        public static <K, V> V getValue(Map<K, V> map, K key) {
            return map.get(key);
        }
    }
    ```

    **Bounded Type Parameters:**
    ```java
    // Upper bound - T must extend Number
    class NumberBox<T extends Number> {
        private T number;
        
        public NumberBox(T number) {
            this.number = number;
        }
        
        public double doubleValue() {
            return number.doubleValue();
        }
    }

    // Multiple bounds
    class MultiBound<T extends Number & Comparable<T>> {
        private T value;
        
        public int compareTo(T other) {
            return value.compareTo(other);
        }
    }
    ```

    **Wildcards:**
    ```java
    class WildcardDemo {
        // Unbounded wildcard
        public static void printList(List<?> list) {
            for (Object item : list) {
                System.out.println(item);
            }
        }
        
        // Upper bounded wildcard (read-only)
        public static double sumNumbers(List<? extends Number> list) {
            double sum = 0;
            for (Number n : list) {
                sum += n.doubleValue();
            }
            return sum;
        }
        
        // Lower bounded wildcard (write-only)
        public static void addIntegers(List<? super Integer> list) {
            list.add(1);
            list.add(2);
            list.add(3);
        }
    }
    ```

    **Usage Example:**
    ```java
    public class GenericsDemo {
        public static void main(String[] args) {
            // Generic class usage
            Box<String> stringBox = new Box<>();
            stringBox.set("Hello");
            String str = stringBox.get();  // No cast needed
            
            Box<Integer> intBox = new Box<>();
            intBox.set(100);
            int num = intBox.get();
            
            // Pair
            Pair<String, Integer> pair = new Pair<>("Age", 25);
            System.out.println(pair.getKey() + ": " + pair.getValue());
            
            // Generic method
            Integer[] intArray = {1, 2, 3, 4, 5};
            String[] strArray = {"A", "B", "C"};
            Utilities.printArray(intArray);
            Utilities.printArray(strArray);
            
            // Bounded type
            NumberBox<Integer> numBox = new NumberBox<>(42);
            System.out.println("Double value: " + numBox.doubleValue());
        }
    }
    ```

    **[⬆ Back to Top](#table-of-contents)**

61. ### What is type erasure in Java generics?

    Type erasure is the process by which the Java compiler removes all generic type information during compilation. Generic type parameters are replaced with their bounds or Object, and type casts are inserted where necessary.

    **How Type Erasure Works:**

    ```java
    // Before compilation (source code)
    public class Box<T> {
        private T content;
        
        public void set(T content) {
            this.content = content;
        }
        
        public T get() {
            return content;
        }
    }

    // After type erasure (bytecode equivalent)
    public class Box {
        private Object content;
        
        public void set(Object content) {
            this.content = content;
        }
        
        public Object get() {
            return content;
        }
    }
    ```

    **Bounded Type Erasure:**
    ```java
    // Before erasure
    public class NumberBox<T extends Number> {
        private T number;
        
        public double getValue() {
            return number.doubleValue();
        }
    }

    // After erasure - T replaced with Number (its bound)
    public class NumberBox {
        private Number number;
        
        public double getValue() {
            return number.doubleValue();
        }
    }
    ```

    **Bridge Methods:**
    The compiler generates bridge methods to preserve polymorphism:

    ```java
    class Node<T> {
        public T data;
        
        public void setData(T data) {
            this.data = data;
        }
    }

    class IntegerNode extends Node<Integer> {
        @Override
        public void setData(Integer data) {
            System.out.println("IntegerNode.setData");
            super.setData(data);
        }
    }

    // Compiler generates bridge method:
    // public void setData(Object data) {
    //     setData((Integer) data);  // Calls the actual method
    // }
    ```

    **Implications of Type Erasure:**

    ```java
    public class TypeErasureDemo {
        public static void main(String[] args) {
            // 1. Cannot create instances of type parameters
            // T obj = new T();  // Compile error
            
            // 2. Cannot create arrays of parameterized types
            // List<String>[] array = new List<String>[10];  // Compile error
            List<?>[] array = new List<?>[10];  // OK with wildcard
            
            // 3. Cannot use instanceof with parameterized types
            List<String> list = new ArrayList<>();
            // if (list instanceof ArrayList<String>) {}  // Compile error
            if (list instanceof ArrayList<?>) {}  // OK with wildcard
            
            // 4. Runtime type is same regardless of type parameter
            List<String> stringList = new ArrayList<>();
            List<Integer> intList = new ArrayList<>();
            System.out.println(stringList.getClass() == intList.getClass());  // true
            
            // 5. Cannot overload methods that have same erasure
            // void process(List<String> list) {}
            // void process(List<Integer> list) {}  // Compile error - same erasure
        }
        
        // Workaround: Use Class<T> for runtime type information
        public static <T> T createInstance(Class<T> clazz) throws Exception {
            return clazz.getDeclaredConstructor().newInstance();
        }
    }
    ```

    **Why Type Erasure?**
    - Backward compatibility with pre-generics code
    - No need for new bytecode instructions
    - Reduced memory footprint (no runtime type info)

    **Limitations:**
    - Cannot determine generic type at runtime
    - Cannot create generic arrays
    - Cannot use primitives as type parameters
    - Cannot catch or throw generic exceptions

    **[⬆ Back to Top](#table-of-contents)**


<!-- QUESTIONS_END -->
