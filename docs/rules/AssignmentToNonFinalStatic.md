# AssignmentToNonFinalStatic
**Category:** `pmd`<br/>
**Rule Key:** `pmd:AssignmentToNonFinalStatic`<br/>


-----

<!-- (c) 2019 PMD -->
Identifies a possible unsafe usage of a static field.

<h2>Example:</h2>
<pre>
public class StaticField {
 static int x;
 public FinalFields(int y) {
  x = y; // unsafe
 }
}
</pre>
