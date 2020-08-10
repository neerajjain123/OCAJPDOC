
# Question 1.

<pre>
<code>
public class Test {
	public static void main(String [] args) {
        int a = 2;
        boolean res = false;
        res = a++ == 2 || ++a == 2  && --a == 2;
        System.out.println(a);
	}
}
</pre>
What is the ouput of the program.
</code>

**Answer** 

3

**Reason**

JVM will only evalute the first part of the statement a++ == 2 which is true. Since first (|| is a short-circuit operator) condition is true than compiler will not evaluate the further statement and return. 





