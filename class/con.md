
# 1. Question

<pre>
<code>

class Parent {
    int i = 10;
    Parent(int i) {
            super();
            this.i = i;
    }
}

class Child extends Parent {
    int j = 20;

    Child(int j) {
            super(0);
            this.j = j;
    }

    Child(int i, int j) {
            super(i);
            this(j);
    }

}

public class Test {
    public static void main(String[] args) {
            Child child = new Child(1000, 2000);
            System.out.println(child.i + ":" + child.j);
    }
}

</code>

What is the output of the program.

</pre>

**Answer**

Compilation Error. 

**Reason** 

Child(int, int) constructor has both super(i) and this(j) statements. A constructor should have super(...) or this(...) but not both. Hence Child(int, int) causes compilation failure.
As all the classes are defined in Test.java file under com.udayan.oca.test package, hence child.i and child.j don't give compilation error. i and j are declared with package scope.






