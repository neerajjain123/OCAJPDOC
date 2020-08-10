
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



