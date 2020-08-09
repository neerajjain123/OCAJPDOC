
# Question 1
<pre>
<code> 
public class Test { 
	public static void main(String[] args) { <
		long lvar = 100_23l; 
		int ivar = 3400;
		float fvar = 2.12f;
		double dvar = 15_0.35d;
		fvar = lvar;  // line 1
		dvar = lvar;  // line 2
		fvar = dvar;  // line 3
		dvar = fvar;  // line 4
		fvar = ivar;  // line 5
		ivar = fvar;  // line 6
		ivar = (int)dvar;  // line 7
	}
}
</code>
</pre>

Identify the compilation error in the above code

**Answer**

Line 3 and Line 6. 

## Point to Remember

**byte -> short -> int -> long -> float -> double**

To convert from left to right (a widening conversion), there is no cast necessary (which is why long to float is allowed). To convert right to left (a narrowing conversion) an explicit cast is necessary.


Similarly Conversion of an int or a long value to float, or of a long value to double, may result in loss of precision-that is, the result may lose some of the least significant bits of the value. In this case, the resulting floating-point value will be a correctly rounded version of the integer value

To put it another way, the JLS distinguishes between a loss of magnitude and a loss of precision.

int to byte for example is a (potential) loss of magnitude because you can't store 500 in a byte.

long to float is a potential loss of precision but not magnitude because the value range for floats is larger than that for longs.

So the rule is:

- Loss of magnitude: explicit cast required;
- Loss of precision: no cast required.
