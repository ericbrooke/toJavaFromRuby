
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
```
##HashSet

This class implements the Set interface and permits the null element. This collection does not allow duplicates. It creates a collection that uses a hash table for storage. A hash table stores information by using a mechanism called hashing where the value stored is used to determine a unique key, which is used as the index at which the data is stored. The advantage of hashing is that it allows fast execution times for basic operations, like add( ) and remove().

```
class TestHashSet {
  public static void main(String args[]) {
    // Creating a HashSet
    HashSet<String> androids = new HashSet<String>(); 
    // Adding elements
    androids.add("Cupcake");
    androids.add("Cupcake");
    androids.add("Eclair"); 
    androids.add("Eclair"); 
    androids.add("Gingerbread"); 
    androids.add("Honeycomb"); 
    androids.add("Ice Cream Sandwich"); 
    androids.add("Jelly Bean");

    System.out.println("The contents of the HashSet: "+androids);
  } 
}
```
