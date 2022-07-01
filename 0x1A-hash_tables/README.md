# 0x1A. C - Hash tables
*  A hash table uses a hash function to compute an index, also called a hash code, into an array of buckets or slots, from which the desired value can be found. During lookup, the key is hashed and the resulting hash indicates where the corresponding value is stored.

## Table of contents
| Files                   | Task description                               |
| ------------------------|----------------------------------------        |
| [hash_tables.h](./hash_tables.h)           | Header file containing the function prototypes |               |                         |                                                |
|[0-hash_table_create.c](./0-hash_table_create.c)    | C function that creates a hash table           |
[1-djb2.c](./1-djb2.c) | A hash function that implements djb2 algorithms
[2-key_index.c](./2-key_index.c) | That gives the undex of a key
[3-hash_table_set.c](./3-hash_table_set.c) | C function that adds an elements to the hash table
[4-hash_table_get.c](./4-hash_table_get.c) | C function that retrieves a value associated with a key
[5-hash_table_print.c](./5-hash_table_print.c) | C function that prints a hash table
[6-hash_table_delete.c](./6-hash_table_delete.c) | C function that deletes a hash table
[100-sorted_hash_table.c](./100-sorted_hash_table.c) | C functions for a sorted hash table