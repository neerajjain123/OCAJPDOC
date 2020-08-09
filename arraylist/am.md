
## Question 1. 
 
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


## Question 2. 

public class Test { <br/>

		public static void main(String[] args) { <br/>
            List<Integer> intlist = new ArrayList<>(); <br/>
				intlist.add(10); <br/>
				intlist.add(20); <br/>
				intlist.add(1); <br/>
				intlist.add(2); <br/>
				intlist.add(0); <br/>
				intlist.add(null); <br/>

				intlist.remove(1);
				intlist.remove(Integer.valueOf(0));
				intlist.remove(new Integer(0));
                intlist.remove(null);
        }



## Point to Remember:

1. </p> you must remember to use ArrayList remove methods, only when you are not iterating over ArrayList. if you are iterating then use Iterator.remove() method, failing to do so may result in </b>ConcurrentModificationException</b> in Java. </p>











