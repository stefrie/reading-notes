#### [Home](../README.md) | [Code 102](../102main.md) | [Code 201](../201main.md) | [Code 301](../301main.md) | [Code 401](../401main.md)

---

# **Code 401 | Reading 27a - Hash Tables**

## Hash Tables

### **Terminology:**

| Term           | Definition                                                                                                                                                                                                                                |
| -------------- | ----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| **Hash**       | A hash is the result of some algorithm taking an incoming string and converting it into a value that could be used for either security or some other purpose. In the case of a hashtable, it is used to determine the index of the array. |
| **Buckets**    | A bucket is what is contained in each index of the array of the hashtable. Each index is a bucket. An index could potentially contain multiple key/value pairs if a collision occurs.                                                     |
| **Collisions** | A collision is what happens when more than one key gets hashed to the same location of the hashtable.                                                                                                                                     |

### **What Are They?**

Hashtables are a data structure that utilize key value pairs. This means every `Node` or `Bucket` has both a key, and a value.

The basic idea of a hashtable is the ability to store the key into this data structure, and quickly retrieve the value. This is done through what we call a `hash`. A `hash` is the ability to encode the key that will eventually map to a specific location in the data structure that we can look at directly to retrieve the value.

Since we are able to `hash` our key and determine the exact location where our value is stored, we can do a lookup in an O(1) time complexity. This is ideal when quick lookups are required.

## Structure

### **Hashing**

Basically, a hash code turns a key into an integer. It’s very important that hash codes are deterministic: their output is determined only by their input. Hash codes should never have randomness to them. The same key should always produce the same hash code.

### **Creating a Hash**

A hashtable traditionally is created from an array. Use logic to turn the “key” into a numeric value. Suggestion:

1. Add or multiply all the ASCII values together.
1. Multiply it by a prime number such as 599.
1. Use modulo to get the remainder of the result, when divided by the total size of the array.
1. Insert into the array at that index.

We now know that our key Cat maps to index 16 of the array. We can view into this index and find “Josie”, our value quickly.

### **How the Key/Values Are Stored**

Each index of the array can hold many types of values. The trick is how the values are stored in comparison to efficiency. Each Index of the array contain “buckets”. Each of these “buckets” holds one key/value pair combination. When there is no entry in a specific bucket, the buckets (each index of the array) all start null. The hash table starts each bucket empty and overwrites their value once a key generates a hashCode that corresponds with an index.

### **Collisions**

A collision occurs when two different keys resolve to the same index of the array. The hash map needs to be able to handle two keys resolving to the same index.

Collisions are solved by changing the initial state of the buckets. Instead of starting them all as `null` we can initialize a `LinkedList` in each one, so if two keys resolve to the same index, then their key/value pairs can be stored as a node in a linked list. Each index in the array is called a “bucket” because it can store multiple key/value pairs.

---

## Resources

-   **Read**: [Intro to Hash Tables](https://codefellows.github.io/common_curriculum/data_structures_and_algorithms/Code_401/class-30/resources/Hashtables.html)
-   **Watch**: [What is a Hash Table?](https://www.youtube.com/watch?v=MfhjkfocRR0)
-   **Read**: [Basics of Hash Tables](https://www.hackerearth.com/practice/data-structures/hash-tables/basics-of-hash-tables/tutorial/)
-   **Skim**: [Hash Table Wiki](https://en.wikipedia.org/wiki/Hash_table)

---

#### [Home](../README.md) | [Code 102](../102main.md) | [Code 201](../201main.md) | [Code 301](../301main.md) | [Code 401](../401main.md)
