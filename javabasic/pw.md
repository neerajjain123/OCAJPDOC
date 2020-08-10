
# 1. Question 1. 

<pre>
<code>
public class Test {

		private static void add(double d1, double d2) {
				System.out.println("double version: " + (d1 + d2));
		}

		private static void add(Double d1, Double d2) {
				System.out.println("Double version: " + (d1 + d2));
		}

		public static void main(String[] args) {
				add(10.0, new Integer(10));
		}

}
</code>

What is the output of the program. 
</pre>

**Answer** 

double version: 20.0 

**Reason**

int can be converted to double but Integer type can't be converted to Double type as Integer and Double are siblings (both extends from Number class) so can't be casted to each other. add(10.0, new Integer(10)); => 1st parameter is tagged to double primitive type and 2nd parameter is converted to int, is tagged to double primitive type as well. So, add(double, double); method is invoked.


# 1. Question 2. 

<pre>
<code>

public class Test {
	public static void main(String[] args) {
		Boolean b1 = new Boolean("tRuE");
		Boolean b2 = new Boolean("fAlSe");
		Boolean b3 = new Boolean("abc");
		Boolean b4 = null;
		System.out.println(b1 + ":" + b2 + ":" + b3 + ":" + b4);
	}
}

</code>
What is the output of the program. 
</pre>

**Answer** 

true:false:false:null

**Reason**

new Boolean(String s) creates a Boolean object which contain the value true if the string argument is not null and is equal, ignoring case, to the string “true”, otherwise Boolean object with value false is created.







