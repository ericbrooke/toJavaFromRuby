
##Array List
An Arraylist is a resizable-array implementation of the List interface. It implements all optional list operations, and permits all elements, including null. It also provides methods to manipulate the size of the array that is used internally to store the list.

```
import java.util.*; 
class TestArrayList {
  public static void main(String args[]) {
  // Creating an array list
  ArrayList<String> androids = new ArrayList<String>(); 
  // Adding elements
  androids.add("Cupcake");
  androids.add("Donut");
  androids.add("Eclair");
  androids.add("Froyo");
  androids.add("Gingerbread"); 
  androids.add("Honeycomb");
  androids.add("Ice Cream Sandwich"); 
  androids.add("Jelly Bean");

  System.out.println("Size of ArrayList: " + androids.size());
  // Display the contents of the array list 
  System.out.println("The ArrayList has the following elements: " + androids);
  // Remove elements from the array list
  } 
}
