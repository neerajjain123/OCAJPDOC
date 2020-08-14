
# Question 1

<pre>
<code>
public class Test {
     public static void main(String[] args) {
         String [] arr = {"*", "**", "***", "****", "*****"};
         Predicate pr1 = s -> s.length() < 4;
         print(arr, pr1);
     }
 
     private static void print(String [] arr, Predicate<String> predicate) {
         for(String str : arr) {
             if(predicate.test(str)) {
                 System.out.println(str);
             }
         }
     }
}

</code>
What is the result.
</pre>

**Answer** 

Compilation Error. 

**Reason**

Though Predicate is a generic interface but raw type is also allowed. Type of the variable in lambda expression is inferred by the generic type of Predicate<T> interface. 

In this case, Predicate pr1 = s -> s.length() < 4; Predicate is considered of Object type so variable "s" is of Object type and Object class doesn't have length() method. So, s.length() causes compilation error.









