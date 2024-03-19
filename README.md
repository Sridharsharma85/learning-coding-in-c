# learning-coding-in-c

1. Create a LIFO-like datastore with a capacity of 10 that supports the following operations.
    - **int insert(TimeValue)**:
        - inserts the given TimeValue to the data store. A TimeValue consists of a timestamp and value, both positive integer values. The timestamps are in increasing order. 
        - returns the remaining capacity of the datastore if the insertion is successful.
        - if the insertion is not possible, because the datastore is full, then return -1.
    - **int peek()**:
        - returns the value with the latest timestamp from the datastore.
        - if the datastore is empty, returns -1.
    - **int pop()**:
        - returns the value with the latest timestamp from the datastore, and removes it.
        - if the datastore is empty, returns -1.
    - **int size()**:
        - returns the number of elements present in the datastore.
2. Create a datastore that supports the following operations.
    - **int get(int)**:
        - returns the value present at the given index. Returns -1 if the datastore is empty.
    - **int put(int)**:
        - appends the given positive value to the datastore and returns its index.
    - **int delete(int)**:
        - returns the value present at the given index, and removes it from the datastore. Returns -1 if the datastore is empty.
    - **int size()**:
        - returns the number of elements present in the datastore.
