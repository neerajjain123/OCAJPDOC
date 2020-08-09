
## Question 1. 

package com.neeraj.oca;<br/>
import java.util.ArrayList;<br/>
import java.util.List;<br/>
 
public class Test {
    public static void main(String[] args) { <br/>
        List<**String**> neerajlist = new ArrayList<>();<br/>
        neerajlist.add(null);<br/>
        neerajlist.add(null);<br/>
        neerajlist.add(null);<br/>
        System.out.println(neerajlist.remove(0) + ":" + neerajlist.remove(null));<br/>
    }<br/>
}<br/>

**Answer: null: true**

**Reason:**

Remove(int) returns the deleted member of the list. In this case `list.remove(0);` returns null as null was deleted from the 0th index. So, list is left with 2 elements: [null, null].

Remove(Object) returns true if deletion was successful otherwise false. In this case `list.remove(null)` removes first null from the list and returns true and list is left with just one element: [null].












