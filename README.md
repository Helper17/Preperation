Queue 
One of the main features of the queue is that it does have specific number of elements in it but the capacity is not limited. This means that we can append new elements in the que no matter how much elements are there. 
Generally, there are two operations defined for queue, which are enqueue and dequeue. Enqueue places an element in the last place, while dequeue removes an element that was put first. 

Complexity
As in queue are placed in a sequence then time complexity for accessing and searching for one of the element equals the length of the specific queue. If it has n elements we will denote the complexity by O(n). On the other hand, enque and deque operations’ complexity differs, as we know that element will be added from the “top” and removed from the “end” then it requires only a step. So we will note it as O(1).

The code
In the code it is needed to use array as a type of storing the items which means that the queue has limited length. So, it can also be empty or full. If it will be empty then any element will not be able to be removed and in case it will be full no element can be added. 

I have made a class queue which has items placed in an array. Then I defined methods for the queue which are is_empty(to check whether it is empty or not), size (that counts the length of the queue). 

Also, I have added enqueue and dequeue. In the least ones I wrote a code that will check whether elements can be added or removed accordingly.
