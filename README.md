# Whatsapp-Chatlist-using-LRU-Cache
     
     LRU (Least Latest Used) cache contains the most recently used page numbers and discards the oldest or longest used page numbers or entries.
Will be using Linked List
We used linked lists datastructure. An important phenomenon of LRU is "aging".
Referenced pages are "young" (latest) pages, and pages that are not referenced/unvisited are "old" pages. If a page is reasonably old and referenced, it`s young again. Therefore, entries in the LRU cache goes to and fro frequently. Each node (including the page number) can be moved forward or backward easily by just moving two pointers.

DATASTRUCTURES USED:

Queue implemented with Linked List --> will be useful to implement new and old referenced page number(node).
As with just movement of two pointer we can move any node(which contains page number) to and fro easily.

Better Approch:
Best approach is to use Hash which stores page number which are in queue.
So the datastructure used : Queue with LL and Hash
