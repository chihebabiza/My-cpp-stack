# Templated Stack Implementation in C++

This project implements a generic **Stack** data structure using a **templated class** in C++. It supports standard stack operations along with extended functionalities for educational and debugging purposes.

## Features

- **Generic Stack**: Uses C++ templates to support any data type.
- **Core Operations**:
  - `push(item)`
  - `pop()`
  - `Top()` - view the top element
  - `Bottom()` - view the bottom element
  - `Size()` - get the number of elements
  - `Print()` - print the stack from top to bottom

- **Extended Functionalities**:
  1. `GetItem(index)` - Get element at a specific index
  2. `Reverse()` - Reverse the order of the stack
  3. `UpdateItem(index, value)` - Update an item at a given index
  4. `InsertAfter(index, value)` - Insert a value after a given index
  5. `InsertAtFront(value)` - Insert a value at the top of the stack
  6. `InsertAtBack(value)` - Insert a value at the bottom of the stack
  7. `Clear()` - Remove all elements from the stack

## Sample Output

```

Stack:
50 40 30 20 10

Stack Size: 5
Stack Top: 50
Stack Bottom: 10

Stack after pop():
40 30 20 10

Item(2): 20

Stack after reverse():
10 20 30 40

Stack after updating Item(2) to 600:
10 20 600 40

Stack after Inserting 800 after Item(2):
10 20 600 800 40

Stack after Inserting 1000 at top:
1000 10 20 600 800 40

Stack after Inserting 2000 at bottom:
1000 10 20 600 800 40 2000

Stack after Clear():
(empty)

````

## Built With

This project was built by **Chiheb Abiza** as a practical implementation of templated data structures in C++.

## License

This project is licensed under the [MIT License](LICENSE).

---


