
# Memory

- Stack
- Heap

## Stack

The stack holds alot of different data, variables that are not static (i.e. variables that you do not explicitly declare in code)

The stack can also be used for program scope. when a new function is called the calling code info is pushed to stack.

## Heap

Holds dynamic data like empty variables declared in code. Also Un-initialized varibles.

## Stack Frames

Stack frames are for different scopes.

In a stack frame you it uses the RBP (Base pointer location) to determine where ceratin data will go

- Local Variables: RBP + 8
- Saved RBP: RBP + 0
- Return Address: RBP + 8
- Funtion Params: RBP + 16

Theses spaces are used each time a stack frame is created

## Endianess

Little endian - most significant byte is stored first
Big endian - least is stored is stored first


