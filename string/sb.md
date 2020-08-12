
# 1. Question 1.

<pre>
<code>
public class Test {
    public static void main(String[] args) {
        List<StringBuilder> days = new ArrayList<>();
        days.add(new StringBuilder("Sunday"));
        days.add(new StringBuilder("Monday"));
        days.add(new StringBuilder("Tuesday"));

        if(days.contains(new StringBuilder("Sunday"))) {
            days.add(new StringBuilder("Wednesday"));
        }

        System.out.println(days.size());
    }
}

</pre>

What is the output of the program. 

</code>

**Answer**

3

**Reason** 
StringBuilder class doesn't override equals(Object) method and hence days.contains(new StringBuilder("Sunday")) returns false. Code inside if-block is not executed and days.size() returns 3.


# 1. Question 2.

<pre>
<code>

package com.udayan.oca;
 
public class Test {
    public static void main(String[] args) {
        StringBuilder sb = new StringBuilder("Hurrah! I Passed...");
        sb.delete(0, 100);
        System.out.println(sb.length());
    }
}

</code>

What will be the result?

</pre>

**Answer**

0

**Reason** 

public StringBuilder delete​(int start, int end); 
Throws: StringIndexOutOfBoundsException - if start is negative, greater than length(), or greater than end.

If end is greater than the length of StringBuilder object, then StringIndexOutOfBoundsException is not thrown and end is set to sb.length(). So, in this case, `sb.delete(0, 100);` is equivalent to `sb.delete(0, sb.length());` and this deletes all the characters from the StringBuilder object.
