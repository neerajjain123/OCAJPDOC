
# Question 1.
<pre>
<code>
public class Test {
	public static void main(String[] args) {
		Integer foo = 10;
		switch(foo) {
			default:
				System.out.println("DEFAULT");
			case 20:
				System.out.println("TWENTY");
				break;
			case 11:
				System.out.println("TEN");
				break;
			case null:
				System.out.println("null");

		}
	}
}
What will be the output of the above program. 
</code>
</pre>

**Answer** 

Compilation error. The reason that the compiler doesn't complain about switch (foo) where foo is an Integer is because Java auto-unboxes the Integer to an int. the unboxing will throw a NullPointerException when foo is null. Therefore case with null is not allowed within switch label.  


# Point to remeber

**Switch can accept primitive types: byte, short, int, char; wrapper types: Byte, Short, Integer, Character; String and enums.**
**The prohibition against using null as a switch label prevents one from writing code that can never be executed. If the switch expression is of a reference type, such as a boxed primitive type or an enum, a run-time error will occur if the expression evaluates to null at run-time.**
