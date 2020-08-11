
# 1. Question 1.
<pre>
<code>
abstract class Super {
	public abstract void m1() throws IOException;
}

class Sub extends Super {
    @Override
    public void m1() throws IOException {
            throw new FileNotFoundException();
    }
}

public class Test {
    public static void main(String[] args) {
        Super s = new Sub();
        try {
            s.m1();
        } catch (IOException e) {
            System.out.print("A");
        } catch(FileNotFoundException e) {
            System.out.print("B");
        } finally {
            System.out.print("C");
        }
    }
}
</pre>

What is the output of the program. 
</code>

**Answer**

Compilation Error. unreachable catch block

**Reason** 

FileNotFoundException extends IOException and hence catch block of FileNotFoundException should appear before the catch block of IOException.


# Question 2.

<pre>
<code>
public class Test {
    private static void m1() throws NullPointerException {
        throw new NullPointerException();
    }

    public static void main(String[] args) {
        try {
            m1();
        }
        finally {
            System.out.println("A");
        }
    }
}

</pre>
What is the output of the program. 
</code>

**Answer**
A Run time Exception: java.lang.NullPointerException

**Reason** 
A catch block is not a must for the runtime exception therfeore compiler will not complain. At runtime null pointer exception is thrown but no catch block to handle it. Threfore program will throw NullPointerException.


# Question 3.

<pre>
<code>
public class Test {
    private static void m1() throws IOException {
        throw new IOException();
    }

    public static void main(String[] args) {
        try {
            m1();
        }
        finally {
            System.out.println("A");
        }
    }
}

</pre>
What is the output of the program. 
</code>

**Answer**
A compile time Error: Unhandled exception

**Reason** 
A catch block is a must for the checked Exception therfeore compiler will give error.

## Point to Rememeber

- If the abstract method in the interface throws certain exception. The implemented method can throw the same exception.
- If the abstract method in the interface throws certain exception. The implemented method can choose not to throw any exception.
- If the abstract method in the interface throws certain exception. The implemented method can throw its subtype. 
- If the abstract method in the interface throws certain exception. The implemented method should not throw its super type.  














