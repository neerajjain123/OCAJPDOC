
# Question 1

public class Test {
		public static void main(String[] args) {
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

Identify the compilation error in the above code








