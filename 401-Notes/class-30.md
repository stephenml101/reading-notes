# Hash Tables

[Intro to Hash Tables](https://codefellows.github.io/common_curriculum/data_structures_and_algorithms/Code_401/class-30/resources/Hashtables.html)

[What is a hash table?](https://www.youtube.com/watch?v=MfhjkfocRR0)

[Basics of hash tables](https://www.hackerearth.com/practice/data-structures/hash-tables/basics-of-hash-tables/tutorial/)

[Hash Table Wiki](https://en.wikipedia.org/wiki/Hash_table)


## Vocabulary:

- Hash - A hash is the result of some algorithm taking an incoming string and converting it into a value that could be used for either security or some other purpose. In the case of a hashtable, it is used to determine the index of the array.

- Buckets - A bucket is what is contained in each index of the array of the hashtable. Each index is a bucket. An index could potentially contain multiple key/value pairs if a collision occurs.

- Collisions - A collision is what happens when more than one key gets hashed to the same location of the hashtable.

## Facts

- Hash maps take advantage of an array’s O(1) read access.

- A hash code turns a key into an integer.

- Collisions are initialized by LinkedLists.

## Methods

```set()```
- When adding a new key/value pair to a hashtable:

  - send the key to the hash() method.
  - Once you determine the index of where it should be placed, go to that index
  - Check if something exists at that index already, if it doesn’t, add it with the key/value pair.
  - If something does exist, add the new key/value pair to the data structure within that bucket.

```get()```

- The get() method takes in a key, gets the Hash, and goes to the index location specified. Once at the index location is found in the array, it is then the responsibility of the algorithm the iterate through the bucket and see if the key exists and return the value.

```has()```

- The has() method will accept a key, and return a bool on if that key exists inside the hashtable. The best way to do this is to have the contains call the hash() method and check the hashtable if the key exists in the table given the index returned.

```keys()```

- The keys() method returns a collection (array) of unique hash keys.

```hash()```

- The hash() method will accept a key as a string, conduct the hash, and then return the index of the array where the key/value should be placed.