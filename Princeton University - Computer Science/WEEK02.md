# WEEK 02: STACKS AND QUEUES

> Princeton University
>
> Computer Science: Algorithms, Theory, and Machines

**Question 01:** Suppose that you start with an empty  stack and interpret a letter to mean push and – to mean pop. Mark the sequences below that leave e at the **bottom** of the stack.

* a – b – c – d – e f g – h ✅
* a – b c – – d – e f g – h ✅
* a – b c – – d – e f g h – ✅
* a b c d – – – – e f g – h ✅
* a – b c – d – e – f g – h ❌

**Question 02:** Which of the following is the primary reason to use generics when implementing stacks and queues?

* Eliminates need to have multiple implementations for different types

**Question 03:** When does a data type not implement the **Queue API**? Mark all that apply.

* When the order of growth of the time required to enqueue an item is logarithmic ❌
* When the only operations that change the queue are to insert an item and to remove the least recently inserted item ❌

When does a data type not implement the **Stack API**? Mark all that apply.

* When the order of growth of the time required to insert an item is logarithmic ❌
* When the only operations that modify the stack are to insert an item and to remove the least recently inserted item ❌

**Question 04:**

* Evaluate the Postfix expression `1 1 + 1 1 + * 1 + 1 +`
  * Input: 6
* Evaluate the Postfix expression `1 1 1 1 1 1 + + * + *`
  * Input: 4
