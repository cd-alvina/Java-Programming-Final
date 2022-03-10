# Java-Programming-Final

# Section 1
**1. Which of following statments are true when you create a object from class Object at runtime as seen below. (Choose Three)**

```java.lang.Object obj = new java.lang.Object();```

_(Choose all correct answers)_

1. Reference obj can be reassigned to any other type of object. *
2. A new instance of class Object is created. *
3. Memory is allocated for a new object, if available.
4. This Object instance will not be created because you never defined class Object.

**2. What is the output from the following code snippet?**
```public class Test {
public static void main(String[] args) {

System.out.println(1 + 2 + "java" + 3);
}
}
```


1. The code will compile and print "java3"
2. The code will compile and print "6java"
3. The code does not compile.
4. The code will compile and print "3java3" *
5. The code will compile and print "12java3"

**3. Which two statements best describe data encapsulation? (Choose Two)**

_(Choose all correct answers)_

1. The access modifier for methods is protected. *
2. Member data can be modified directly.
3. Methods provide for access and modification of data.
4. The access modifier to member data is private. *

**4. What is the output from the following code snippet?**

``` public static void main(String[] args){
  try{
   String[] s=null;
   s[0]="Java";
   System.out.println(s[0]);
  }catch(Exception e) {
   System.out.println("Exception");
  }catch(NullPointerException e){
   System.out.println("NullPointerException");
 }
 ```


1. NullPointerException *
2. Exception
3. Compile fails
4. Java

**5. Which statement added at line one allows the code to compile and run?**

_line one_
```
public class Test (
  public static void main (String[] args) {
   java.io.PrintWriter out = new java.io.PrintWriter
        (new java.io.OutputStreamWriter (System.out), true);
   System.out.println("Java");
  }
}
```
1. include java.io.*;
2. No statement is needed. *
3. import java.io.OutputStreamWriter
4. import java.io.PrintWriter;
5. import java.io.*; 

**6. Virtual method invocation occurs:**

1. When the method of a subclass is used on a superclass reference.*
2. When the method of a subclass is used on a subclass reference.
3. Not part of polymorphism.
4. When the method of a superclass is used on a superclass reference.

**7. The instanceof operator enables to discover the type of object it was invoked upon. True or false**

* True *
* False

**8. Reading great code is just as important for a programmer as reading great books is for a writer. True or false?**

* True *
* False

 **9.The main purpose of unit testing is to verify that an individual unit (a class, in Java) is working correctly before it is combined with other components in the system. True or false?**

* True *
* False

**10. Which two statements are equivalent to line 2?**
_(Choose Two)_

```
1. public interface Account{
2. int accountID=100;
3. }
```

1. protected int accountID=100;
2. static int accountID=100; *
3. Final int accountID=100; *
4. Abstract int accountID=100;
5. private int accountID=100;

# Section 2
**11. Modeling business problems requires understanding the interaction between interfaces, abstract and concrete classes, subclasses, and enum classes.**

* True *
* False

# Section 3

**12. A generic class increases the risk of runtime class conversion exceptions.
True or False?**

* True
* False *

**13. The following code will compile.**
```
class Node<T> implements Comparable<T>{
    public int compareTo(T obj){return 1;}
}

class Test{
    public static void main(String[] args){
        Node<String> nc=new Node<>();
        Comparable<String> com=nc;
}
```

* True *
* False

**14. A sequential search is an iteration through the array that stops at the index where the desired element is found. True or false?**

* True *
* False

**15. Which of the following is the correct lexicographical order for the conents of the following int array?**
```
{17, 1, 1, 83, 50, 28, 29, 3, 71, 22}
```

1. {1, 2, 7, 0, 9, 5, 6, 4, 8, 3}
2. {0, 1, 2, 3, 4, 5, 6, 7, 8, 9}
3. {71, 1, 3, 28,29, 50, 22, 83, 1, 17}
4. {83, 71, 50, 29, 28, 22, 17, 3, 1, 1}
5. {1, 1, 17, 22, 28, 29, 3, 50, 71, 83} *
6. {1, 1, 3, 17, 22, 28, 29, 50, 71, 83}

**16. Which searching algorithm involves using a low, middle, and high index value to find the location of a value in a sorted set of data (if it exists)?**

1. Sequential Search
2. Merge Sort
3. Selection Sort
4. Binary Search
5. All of the above *
6. None of the above.

**17. Which of these could be a set? Why?**


1. {1, 1, 2, 22, 305, 26} because a set may contain duplicates and all its elements are of the same type.
2. {"Apple", 1, "Carrot", 2} because it records the index of the elements with following integers.
3. {1, 2, 5, 178, 259} because it contains no duplicates and all its elements are of the same type. *
4. All of the above are sets because they are collections that can be made to fit any of the choices.

**18. Which of the following correctly adds "Cabbage" to the ArrayList vegetables?**

1. vegetables.get("Cabbage");
2. vegetables += "Cabbage"; 
3. vegetables[0] = "Cabbage";
4. vegetables.add("Cabbage"); *

**19. What is a set?**

1. Something that enables you to create a generic class without specifying a type between angle brackets <>.
2. A collection of elements that does not contain duplicates. *
3. A collection of elements that contains duplicates.
4. A keyword in Java that initializes an ArrayList.

**20. A HashMap can only store String types.
True or false?**

* True 
* False *

**21. A LinkedList is a type of Stack.
True or False?**

* True *
* False

**22. Which of the following describes a deque.**

1. It is pronounced "deck" for short.
2. It implements a stack.
3. Allows for insertion or deletion of elements from the first element added or the last one.
4. All of the above. *

# Section 4

**23. In a regular expression, {x} and {x,} represent the same thing, that the preceding character may occur x or more times to create a match.
True or false?**

* True
* False *

**24. Your teacher asks you to write a segment of code that returns true if String str contains zero or one character(s) and false otherwise. Which of the following code segments completes this task?(Choose Two)**

_(Choose all correct answers)_

1. if( str.length() == 0 || str.length() == 1)
{ return true;}
return false; *
2. return str.matches(".?"); *
3. return str.contains(".");
4. return str.matches("[a-z]*");

**25. Identify the method, of those listed below, that is not available to both StringBuilders and Strings?**

1. charAt(int index)
2. length()
3. delete(int start, int end) *
4. indexOf(String str)

**26. Which of the following methods are StringBuilder methods?**

1. append
2. delete
3. insert
4. replace
5. All of the above. *
6. None of the above.

**27. A non-linear recursive method is less expensive than a linear recursive method.
True or false?**

* True
* False *

**28. Which case does a recursive method call last?**

1. Recursive Case
2. Convergence Case
3. Basic Case
4. Base Case *
5. None of the above

# Section 5

**29. Which of the following is an attribute of a three tier architecture application?**

1. an application of that type has a client and server only 
2. a complex application that includes a client, a server and database
3. an application of that type runs on a single computer *
4. None of the above
5. All of the above

**30. Which of the following files are not required to be uploaded to a web server to deploy a JWS java application/applet?**

1. jar files
2. JNLP files
3. html files
4. .java files *
5. None of the above

**31. The java.nio.file package has improved exception handling.
True or false?**
 * True *
* False

**32. The java.io package has problems with no support for symbolic links.
True or false?**

* True *
* False

**33. The BufferedOutputStream is a direct subclass of what other class?**

1. PrintStream
2. ObjectOutputStream
3. OutputStream
4. FilterOutputStream *
5. DigestOutputStream

**34. The BufferedInputStream is a direct subclass of what other class?**

1. PipedInputStream
2. InputStream
3. InputStream
4. FilterInputStream *
5. FileInputStream

# Section 6

**35. Suppose that you have a table EMPLOYEES with three rows. The first_name in those rows are A, B, and C. What does the following output?**

```
String sql = "select first_name from Employees order by first_name desc";
Statement stmt=conn.createStatement = (ResultSet.TYPE_SCROLL_SENSITIVE,ResultSet.CONCUR_READ_ONLY);
ResultSet rset= stmt.executeQuery(sql);
rset.absolute(1);
rset.next();
System.out.println(rset.getString(1));
```
1. A
2. B *
3. C
4. The code does not compile.
5. A SQLException is thrown.

**36. Which JDBC interface can be used to access information such as database URL, username and table names?**

1. Statement Interface
2. PreparedStatement Interface
3. DatabaseMetaData Interface *
4. CallableStatement Interface

**37. Given the following code, assume there are rows of data in the table EMP. What is the result?**
``` 
1 Connection conn - new Connection(URL);
  2 Statement stmt = conn.createStatement();
  3 ResultSet result - stmt.executeQuery("select count(*) from EMP");
  4 if(rs.next()){
  5 System.out.println(rs.getInt(1));
  6 }
  ```

1. Compiler error on line 2
2. Runtime error on line 3
3. 2
4. 0
5. Compiler error on line 1

**38. What type of JDBC driver will convert the database invocation directly into network protocol?**

1. Type 1 driver
2. Type 2 driver
3. Type 3 driver
4. Type 4 driver *

# Section 7

**39. In which area of heap memory are newly created objects stored?**

1. Survivor Space 0
2. Survivor Space 1
3. Eden *
4. Tenured

**40. Given the following output from the Minor GC:**
```
[GC [DefNew: 4032K->64K(4032K), 0.0429742 secs] 9350K->7748K(32704K), 0.0431096 secs]
```
_Which of the following statements is TRUE?_

1. Entire heap is 9350k.
2. Young Generation usage decreased by 3968k. *
3. The pause time spent in Young Generation is 0.0431096 *
4. The size of Eden space is 4032k.

**41. During runtime, the Java platform loads classes dynamically as required.**

* True *
* False

**42. Which of the following statements is NOT TRUE about the JVM?**

1. The JVM is a virtual Machine that acts as an intermediary layer between the Java Application and the Native Operating System.
2. The JVM reads byte code from the class file, and generates machine code.
3. The JVM does not understand the Java language specification.
4. The JVM reads Java source code, and then translates it into byte code. *

# Section 8

**43. Like in the Java source code file, one Java class file can contain multiple class definitions.**

* True
* False *

**44. The class file contains the definition it inherits from the superclass.**

* True
* False *

**45. Which of the following commands allows a developer to see the effects of a running java application on memory and CPU?**

1. javac
2. jvisualvm *
3. java
4. javap

**46. Which of the following commands can be used to monitor the Java Virtual Machine statistics?**

1. jstat *
2. javap
3. javac
4. jmap

# Section 9

**47. In the ClassLoader hierarchy, which of the following is the only class loader that does NOT have a parent?**

1. custom class loader
2. application class loader
3. bootstrap class loader *
4. extension class loader

**48. The Java developer can define a number of additional or custom classloaders.**

* True *
* False

**49. To inspect bytecode, which option is used with the javap command to disassemble the class file?**

1. -a
2. -b
3. -c *
4. -d

**50. Choose which opcode is used to push an int constant 5 onto the operand stack.**

1. iconst_5 *
2. idc5
3. iload_5
4. iaload_5
5. iinc5