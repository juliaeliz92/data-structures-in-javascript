## Objective

Data structure implementation in Javascript. Data structure currently focused on is linked list.

## Explanation
- Linked list
  A linked list is an ordered collection of data elements. A data element can be represented as a node in a linked list. Each node consists of two parts: data & pointer to the next node. Unlike arrays, data elements are not stored at contiguous locations. The data elements or nodes are linked using pointers, hence called a linked list. The first node, head, is pointed to the first node, and the last node points to null.

  In this context, each node is treated as an object which has next property with value of the next node. The head will be the first child of the list object meanwhile the inner most nested object has next property null. It goes like this:

  ```
  const list = {
    head: {
        value: 6
        next: {
            value: 10                                             
            next: {
                value: 12
                next: {
                    value: 3
                    next: null	
                    }
                }
            }
        }
    }
  };


I have demonstrated different manipulation methods on linked lists: appending to the front, retrieving the index of a node, inserting a node at a given index, removing a node, removing a node at a particular index, and displaying the list data.

## Prerequisites

All you need is an IDE, preferably Visual Code, and the latest node installed in the system. 

## How to run 

Run `node [name of the file]` at the root of the directory
