
# Question 1

<pre>
<code>
class Message {
    public static void main(String [] args) {
        System.out.println("Welcome! " + args[1]);
     
}
 
public class Guest {
    public static void main(String [] args) {
         Message.main(args);
    }
}

</code>

java Guest James Gosling
What is the result?
</pre>

**Answer**

Welcome Gosling

**Reason** 

Both the classes contain special main method. No compilation error with the code: file is correctly names as Guest.java (name of public class).

`java Guest James Gosling` passes new String [] {"James", "Gosling"} to args of Guest.main method.

Apart from being special main method, Message.main is static method so Guest.main method invokes Message.main method with the same argument: new String [] {"James", "Gosling"}. args[1] is "Gosling" hence "Welcome! Gosling" gets printed on to the console.






