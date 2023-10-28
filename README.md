# Queue Data Structure

A queue is a fundamental data structure in computer science that follows the First-In-First-Out (FIFO) principle. This means that the first element added to the queue is the first one to be removed. Queues can be visualized as a collection of elements arranged in a linear structure, with two primary operations: **enqueue** and **dequeue**. The enqueue operation adds an element to the back of the queue, and the dequeue operation removes an element from the front.

## Characteristics of a Queue

1. **FIFO Principle**: The first element added to the queue is the first to be removed.

2. **Operations**:
    - **Enqueue**: Adds an element to the back of the queue.
    - **Dequeue**: Removes an element from the front of the queue.

3. **Front and Rear**: Queues often have pointers or references to the front and rear elements for easy access.

4. **Empty Queue**: A queue can be empty, indicating it contains no elements.

5. **Fixed or Dynamic Size**: Queues can have a fixed size, meaning they can only hold a specific number of elements, or a dynamic size where the queue can grow or shrink as needed.

## Implementing a Queue

In C++, you can implement a queue using various data structures like arrays or linked lists. A basic approach to implement a queue involves using an array and managing the queue's size manually. Here's a brief outline of the steps:

1. **Declare an Array**: Create an array to store the queue's elements.

2. **Front and Rear Pointers**: Maintain two pointers (integers), one for the front and one for the rear of the queue. Initialize them accordingly.

3. **Enqueue Operation**: To enqueue an element, increment the rear pointer and store the element in the array at that index.

4. **Dequeue Operation**: To dequeue an element, access the element at the front index, increment the front pointer, and update the rear pointer as needed.

5. **Check for Empty Queue**: Ensure that you handle cases where the queue is empty (front pointer is ahead of or equal to the rear pointer) before dequeuing.

6. **Dynamic Sizing**: If you want a dynamic-sized queue, consider resizing the array when it becomes full or using a linked list to avoid size limitations.

Remember that this is a basic outline, and you may need to add error handling and other features depending on your specific use case. In practice, C++ provides a more convenient way to work with queues using the Standard Template Library (STL) `queue` container, as demonstrated in the previous code example in the README.
