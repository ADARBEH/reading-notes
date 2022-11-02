#### Hash tables are a type of data structure in which the address/ index value of the data element is generated from a hash function. This enables very fast data access as the index value behaves as a key for the data value.

#### Hash tables are used to implement associative arrays, database indexing, caches, sets, and so on. In some languages, they are given built-in support, while in others, they are implemented using arrays or linked lists.

#### Hash tables are a very important data structure in computer science. They are used in many applications, such as spell checkers, compilers, and data compression. They are also used in the implementation of other data structures, such as sets, associative arrays, and databases.

#### Hash tables are a very important data structure in computer science. They are used in many applications, such as spell checkers, compilers, and data compression. They are also used in the implementation of other data structures, such as sets, associative arrays, and databases.

---

## Collision Handling

### 1.Linear Probing :
#### In linear probing, when a collision occurs, the search for the next empty slot begins at the next slot and continues in a linear fashion until an empty slot is found. If the entire hash table is searched and all slots are full, then the hash table is said to be full.

### 2.Quadratic Probing :
#### In quadratic probing, when a collision occurs, the search for the next empty slot begins at the next slot and continues in a quadratic fashion until an empty slot is found. If the entire hash table is searched and all slots are full, then the hash table is said to be full.

### 3.Double Hashing :
#### In double hashing, when a collision occurs, the search for the next empty slot begins at the next slot and continues in a double hashing fashion until an empty slot is found. If the entire hash table is searched and all slots are full, then the hash table is said to be full.

### 4.Chaining :
#### Lastly this way is the most easiest of all. Each Index will be it's own List and so the values with the same hashindexes will be put on the same List. Again, we have a performance increase when many values fall into the same key, but we don't have bad clusters like in Linear Probing. That means that we don't have values from other key's in between, but search only in the specific key List. So, the perfromance will only be affected on those key's that have many values and the others will continue working just fine!

---

## Example of Hash Table Chainning
![Hash Table](https://steemitimages.com/p/axopD2eJJx4em8SsAXJGsWY4D4L1NaBHQFPofwc5boD7dS4Sj8QjH1yQJw4A?format=match&mode=fit&width=1280)
