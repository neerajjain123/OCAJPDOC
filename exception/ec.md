
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


## Point to Rememeber












