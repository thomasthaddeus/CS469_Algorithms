# Notes

The actual runtime of hash table operations in this exercise will depend on the specific implementation and the input data. However, in general, hash tables offer faster average-case performance for insertions and lookups compared to simple arrays. This is because hash tables have an average-case time complexity of O(1) for both insertions and lookups, while simple arrays have an average-case time complexity of O(n) for lookups and O(1) for insertions at the end. In the provided code, the main function measures the time taken to insert items and find items in both the SimpleArrayGroceryStoreInventoryClass and the HashGroceryStoreInventoryClass.

Upon running the script, it is expected that the hash table implementation will demonstrate a faster performance for lookups when compared to the simple array implementation, while both data structures should have similar insertion times. However, it is important to note that the performance improvement provided by hash tables comes at the cost of increased memory usage due to the use of an array with a specified load factor, as well as the possibility of collisions in the hash table. These collisions can be resolved by using a linked list, as demonstrated in the script.

In conclusion, the script showcases the time difference between the two data structures, which can be used to justify the choice of a particular data structure based on the specific use case and requirements. In general, hash tables are a better choice when faster lookups are a priority, while simple arrays can be more appropriate when memory usage is a concern.