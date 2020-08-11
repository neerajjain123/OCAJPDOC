
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

# 1. Question 3. 

<pre>
<code>

public class Test {
	public static void main(String... strings) {

		Integer integer1 = 3;
		Integer integer2 = 3;

		if (integer1 == integer2)
				System.out.println("integer1 == integer2");
		else
				System.out.println("integer1 != integer2");

		Integer integer3 = 300;
		Integer integer4 = 300;

		if (integer3 == integer4)
				System.out.println("integer3 == integer4");
		else
				System.out.println("integer3 != integer4");

		Integer integer5 = new Integer(3);
		Integer integer6 = new Integer(3);

		if (integer5 == integer6)
				System.out.println("integer5 == integer6");
		else
				System.out.println("integer5 != integer6");

		Integer integer7 = new Integer(3);
		Integer integer8 = Integer.valueOf(3);

		if (integer7 == integer8)
				System.out.println("integer7 == integer8");
		else
				System.out.println("integer7 != integer8");

		if (integer1 == integer8)
				System.out.println("integer1 == integer8");
		else
				System.out.println("integer1 != integer8");
	}
}

</code>
What is the output of the program. 
</pre>

**Answer** 
integer1 == integer2
integer3 != integer4
integer5 != integer6
integer7 != integer8
integer1 == integer8


**Reason**
integer1 == integer2 ==>  integer1 == integer8  ==> 
Integer objects are cached internally and reused via the same referenced objects. This is applicable for Integer values in range between –127 to +127 (Max Integer value). This Integer caching works only on autoboxing. This is called object interning. 

integer3 != integer4 ==> This is than literal value is more than 127 than caching will not work. 

integer5 != integer6 ==> Since this objects are created using the constructor not with the interning therefore both the object will have different references.  


# point to remember

Two instances of following wrapper objects, created through auto-boxing will always be same, if their primitive values are same:

Boolean,

Byte,

Character from \u0000 to \u007f (7f equals to 127),

Short and Integer from -128 to 127. 







