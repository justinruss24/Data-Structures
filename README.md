# Data Structures 

Topics:
 * Singly Linked Lists
 * Queues and Stacks
 * Doubly Linked Lists
 * Binary Search Trees
 * Related Code Challenge Problems


## Implementations throughout Repo
 * Implement the Stack and Queue classes using built-in Python lists and the Node and LinkedList classes you created during the Module 1 Guided Project.
 * Implement the Doubly Linked List class
 * Implement the Binary Search Tree class
 * Implement traversal methods on Binary Search Trees

### Stacks
* Should have the methods: `push`, `pop`, and `len`.
   * `push` adds an item to the top of the stack.
   * `pop` removes and returns the element at the top of the stack
   * `len` returns the number of elements in the stack.

### Queues
 * Has the methods: `enqueue`, `dequeue`, and `len`.
   * `enqueue` adds an element to the back of the queue.
   * `dequeue` removes and returns the element at the front of the queue.
   * `len` returns the number of elements in the queue.
 
![Image of Queue](https://upload.wikimedia.org/wikipedia/commons/thumb/5/52/Data_Queue.svg/600px-Data_Queue.svg.png)

### Doubly Linked Lists
 * The `ListNode` class, which represents a single node in the doubly-linked list, has already been implemented for you. Inspect this code and try to understand what it is doing to the best of your ability.
 * The `DoublyLinkedList` class itself should have the methods: `add_to_head`, `add_to_tail`, `remove_from_head`, `remove_from_tail`, `move_to_front`, `move_to_end`, `delete`, and `get_max`.
   * `add_to_head` replaces the head of the list with a new value that is passed in.
   * `add_to_tail` replaces the tail of the list with a new value that is passed in.
   * `remove_from_head` removes the head node and returns the value stored in it.
   * `remove_from_tail` removes the tail node and returns the value stored in it.
   * `move_to_front` takes a reference to a node in the list and moves it to the front of the list, shifting all other list nodes down. 
   * `move_to_end` takes a reference to a node in the list and moves it to the end of the list, shifting all other list nodes up. 
   * `delete` takes a reference to a node in the list and removes it from the list. The deleted node's `previous` and `next` pointers should point to each afterwards.
   * `get_max` returns the maximum value in the list. 
 * The `head` property is a reference to the first node and the `tail` property is a reference to the last node.
 
![Image of Doubly Linked List](https://upload.wikimedia.org/wikipedia/commons/thumb/5/5e/Doubly-linked-list.svg/610px-Doubly-linked-list.svg.png)

### Binary Search Trees
* Should have the methods `insert`, `contains`, `get_max`.
  * `insert` adds the input value to the binary search tree, adhering to the rules of the ordering of elements in a binary search tree.
  * `contains` searches the binary search tree for the input value, returning a boolean indicating whether the value exists in the tree or not.
  * `get_max` returns the maximum value in the binary search tree.
  * `for_each` performs a traversal of _every_ node in the tree, executing the passed-in callback function on each tree node value. There is a myriad of ways to perform tree traversal; in this case any of them should work. 

![Image of Binary Search Tree](https://upload.wikimedia.org/wikipedia/commons/thumb/d/da/Binary_search_tree.svg/300px-Binary_search_tree.svg.png)

---
