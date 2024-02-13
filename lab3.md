# Lab Report 3
## Part 1
The bug that I choose is the List methods bugs.
### Failure inducing input Test Code
```java
import static org.junit.Assert.*;
import org.junit.*;
import java.util.ArrayList;
import java.util.List;

public class ListTests {
    @Test 
    public void testFilter(){
        List<String> l1 = new ArrayList<>();
        l1.add("Apple");
        l1.add("Banana");
        l1.add("Acid");
        StringChecker sc = new StringChecker() {
            public boolean checkString(String s){
                return s.startsWith("A");
            }
        };
        List<String> l2 = ListExamples.filter(l1,sc);
        List<String> l3 = new ArrayList<>();
        l3.add("Apple");
        l3.add("Succ");//l3 = {"Apple","Acid"}
        assertArrayEquals(l3.toArray(), l2.toArray());
    }
}
```

### Successful inducing input Test Code
```java
import static org.junit.Assert.*;
import org.junit.*;
import java.util.ArrayList;
import java.util.List;

public class ListTests {
    @Test 
    public void testFilter(){
        List<String> l1 = new ArrayList<>();
        l1.add("Apple");
        l1.add("Banana");
        l1.add("Acid");
        StringChecker sc = new StringChecker() {
            public boolean checkString(String s){
                return s.startsWith("A");
            }
        };
        List<String> l2 = ListExamples.filter(l1,sc);
        List<String> l3 = new ArrayList<>();
        l3.add("Acid");
        l3.add("Apple");//l3 = {"Acid","Apple"}
        assertArrayEquals(l3.toArray(), l2.toArray());
    }
}
```
