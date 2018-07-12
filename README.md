# COMP 271 SU18 Lab 6 (Week 8)

- Why does FixedArrayQueue require an explicit constructor?
  - You are assigning a capacity to a fixed array queue.
- What happens when you offer an item to a full FixedArrayQueue?
  - You will receive an IllegalStateException stating the queue is full.
- What happens when you poll an empty FixedArrayQueue?
  - Null is returned. 
- What is the time and (extra) space complexity of each of the FixedArrayQueue methods?
  - Accessing and searching the queue is O(n), queue insertion and deletion are O(1).
