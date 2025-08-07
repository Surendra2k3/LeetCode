In Java, an array is an important linear data structure that allows us to store multiple values of the same type.

Arrays in Java are objects, like all other objects in Java, arrays implicitly inherit from the java.lang.Object class. This allows you to invoke methods defined in Object (such as toString(), equals() and hashCode()).
Arrays have a built-in length property, which provides the number of elements in the array

**Key features of Arrays**

Store Primitives and Objects: Java arrays can hold both primitive types (like int, char, boolean, etc.) and objects (like String, Integer, etc.)
Contiguous Memory Allocation When we use arrays of primitive types, the elements are stored in contiguous locations. For non primitive types, references of items are stored at contiguous locations.
Zero-based Indexing: The first element of the array is at index 0.
Fixed Length: After creating an array, its size is fixed; we can not change it.
