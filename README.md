
# Pointers in C

A pointer in C is a variable that stores the memory address of another variable. Pointers provide a powerful tool for working with memory and data structures in C.




## Declaring and Initializing a Pointer

To declare a pointer in C, you use the asterisk (*) symbol before the variable name. For example, to declare a pointer that points to an integer variable, you would write:

```
int* ptr;
```
To initialize a pointer, you can set it to point to the memory address of another variable using the ampersand (&) symbol. For example:

```
int x = 7;
int* ptr = &x;
```

## Dereferencing a Pointer

```
printf("%d\n", *ptr);
```
This returns the value stored in the address pointer is pointing to.