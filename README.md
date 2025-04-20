# LINKED-LIST-IMPLEMENTATION

COMPANY = CODTECH IT SOLUTIONS

NAME = SAYALI PADMANE

INTERN ID = CT04WR115

DOMAIN = C PROGRAMMING

DURATION = 4 WEEKS

MENTOR = NEELA SANTOSH

DESCRIPTION

Description of the Singly Linked List Program
The Singly Linked List Program is a user-friendly implementation of a fundamental data structure known as a singly linked list. Linked lists are widely used in computer science for their efficient management of dynamic collections of elements. Unlike arrays, linked lists can grow and shrink in size easily during runtime, which makes them ideal for situations where the number of elements fluctuates. This program provides an elevated user experience through its clear interface, concise instructions, and informative feedback.

Key Features
Singly Linked List Structure:
The program begins by defining a data structure called Node, which contains two elements:

An integer data representing the value stored in the node.
A pointer next, which points to the next node in the list. If it's the last node, this pointer will be NULL, indicating the end of the list.
Dynamic Node Creation:
The program features a function called createNode, which dynamically allocates memory for a new node and initializes it with a given value. This function is vital for handling the memory requirements while ensuring efficient use of resources. In case of a memory allocation failure, the program prompts a relevant error message and exits gracefully.

User-Friendly Insertions:
Two primary insertion methods are implemented:

Insert at Beginning: This function allows users to place a new node at the start of the list. It efficiently updates the head pointer to point to the new node, maintaining the integrity of the linked list structure.
Insert at End: This function appends a new node to the end of the list. It traverses the list until it reaches the last node and modifies the next pointer to accommodate the new node. Both insertion functions provide instant feedback to users, confirming the successful operation.
Deletion of Nodes:
The program includes a deletion function that allows users to remove a node by its value. It begins by checking if the list is empty, preventing unnecessary operations. If the node to delete is the head, it efficiently updates the head pointer. If the node is found elsewhere, the program redirects the pointers accordingly to unlink the node while ensuring no memory leaks occur. Informative messages keep users updated on the status of their operations.

Traversal and Visualization:
Users can visualize the contents of the linked list utilizing the traverseList function. This function goes through each node, printing its value in an easy-to-read format that resembles the structure of the list. Should the list be empty, a friendly message informs the user.

Interactive Menu System:
The program utilizes a menu-driven interface, inviting the user to choose their desired operation. With an easy-to-understand menu displayed in a loop, users can continuously interact with the linked list, performing multiple operations without restarting the program. Feedback is provided for invalid choices, reinforcing learning and engagement.

Memory Management:
The program is structured to ensure efficient memory usage. The nodes created dynamically are freed upon exiting the program, preventing memory leaks. This indicates a commitment to responsible coding practices and user reassurance.

Exit Gracefully:
When the user opts to exit the program, a warm thank-you message is displayed, leaving users with a positive impression. This simple touch enhances the overall user experience, promoting satisfaction.

OUTPUT
![Image](https://github.com/user-attachments/assets/09204896-5941-4394-98bf-17b1962aba6f)
