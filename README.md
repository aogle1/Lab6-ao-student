# COMP 271 SU18 Lab 6 (Week 8)

•	Why does FixedArrayQueue require an explicit constructor?
o	You are assigning a capacity to a fixed array queue.
•	What happens when you offer an item to a full FixedArrayQueue?
o	You will receive an IllegalStateException stating the queue is full.
•	What happens when you poll an empty FixedArrayQueue?
o	Null is returned. 
•	What is the time and (extra) space complexity of each of the FixedArrayQueue methods?
o	Since this is a circular array it is O(1).
