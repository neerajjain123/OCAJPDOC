
# Question 1
<pre>
<code> 
public class Test { <br/>
		public static void main(String[] args) { <br/>
				long lvar = 100_23l; <br/>
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








