
## Question 1. 

package com.udayan.oca;
 
import java.util.ArrayList;
import java.util.List;
 
public class Test {
    public static void main(String[] args) {
        List<String> neerajlist = new ArrayList<>();
        neerajlist.add(null);
        neerajlist.add(null);
        neerajlist.add(null);
        System.out.println(neerajlist.remove(0) + ":" + neerajlist.remove(null));
    }
}

**Answer: null: true**

**Reason:**

remove(int) returns the deleted member of the list. In this case `list.remove(0);` returns null as null was deleted from the 0th index. So, list is left with 2 elements: [null, null].

remove(Object) returns true if deletion was successful otherwise false. In this case `list.remove(null)` removes first null from the list and returns true and list is left with just one element: [null].











