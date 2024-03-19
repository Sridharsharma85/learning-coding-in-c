# learning-coding-in-c

1. Create a LIFO-like datastore with a capacity of 10 that supports the following operations.
    - **int insert(int)**:
        - inserts the given TimeValue to the data store. A TimeValue consists of a timestamp represented as a positive integer and a positive integer value. The timestamps values are in increasing order. 
        - returns the remaining capacity of the datastore if the insertion is successful.
        - if the insertion is not possible, because the datastore is full, then return -1.
    - **int peek()**:
        - returns the value with the latest timestamp from the datastore.
    - **int pop()**:
        - removes and returns the value with the latest timestamp from the datastore.
    - **int size()**:
        - returns the size of the datastore.
2. Create a datastore that supports the following operations.
    - **int get(int)**:
        - retrieves and returns the value at the given index. If the index is not valid, return -1.
    - **int put(int)**:
        - appends the given positive value to the datastore and returns its index.
    - **int delete(int)**:
        - removes and returns the value from the given index. If the index is not valid, return -1.
    - **int size()**:
        - returns the size of the datastore.
