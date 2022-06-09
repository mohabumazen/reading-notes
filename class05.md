# Big O: Analysis of Algorithm Efficiency

- Big O is used to measure the efficiency of an algorithm by two things: Running time, Memory space.

- Big O describes the worst case scienaro of an algorithm

- We should consider 4 factors for choosing Big O:
    1. Input size: The size of the parameter values that are read by the algorithm (Size and number of parameters that the algorithm reads) The higher the Input Size the more likely there will be an increase to Running Time and Memory Space.
    2. Units of measurment
    3. Orders of growth
    4. Best case, worst case and average case

- To quantify the Memory Space in our analysis: Four Sources of Memory Usage during function run-time: 1. The amount of space needed to hold the code for the algorithm Number of bytes required to store the characters for the instructions specified in your function. 2. The amount of space needed to hold the input data If direct input data is not considered, we may just refer to this as Additional Memory Space since not all functions have direct input values. 3. The amount of space needed for the output data 4. The amount of space needed to hold working space during the calculation Working Space can be thought of as the creation of variables and reference points as our function performs calculations. This will also include Stack Space of recursive function calls

- **Constant Complexity** Growth No matter what inputs are thrown at our algorithm, it always uses the same amount of time or space The number 1 is used to represent a constant value. Complexity growth: O(1) 

    ![const](./assets/class05/constant.png)



- **Logarithmic Complexity** Growth A decrease in the rate of complexity growth, the greater our value of the input size. Complexity growth: O(lgn)

    ![log](./assets/class05/log.png)

- **Linear Complexity** Growth The size of our inputs will directly determine the amount of Memory Space used and Running Time length. This is a very common efficiency and is usually used to denote functions with loops, or often algorithms that use recursion. Complexity growth: O(n)

    ![linear](./assets/class05/linear.png)

# Linked Lists

- A node is a collection of two sub-elements or parts. A data part that stores the element and a next part that stores the link to the next node. A Linked List is a sequence of Nodes that are connected/linked to each other. Order of operations is extremely important when it comes to working with a Linked List

- Terminology

    1. Linked List - A data structure that contains nodes that links/points to the next node in the list.
    2. Singly - Singly refers to the number of references the node has. A Singly linked list means that there is only one reference, and the reference points to the Next node in a linked list.
    3. Doubly - Doubly refers to there being two (double) references within the node. A Doubly linked list means that there is a reference to both the Next and Previous node.
    4. Node - Nodes are the individual items/links that live in a linked list. Each node contains the data for each link.
    5. Next - Each node contains a property called Next. This property contains the reference to the next node.
    6. Head - The Head is a reference of type Node to the first node in a linked list.
    7. Current - The Current is a reference of type Node to the node that is currently being looked at. When traversing, you create a new Current variable at the Head to guarantee you are starting from the beginning of the linked list.

- Traversal We depend on the Next value in each node to guide us where the next reference is pointing. The Next property is exceptionally important because it will lead us where the next node is and allow us to extract the data appropriately.

- The best way to approach a traversal is through the use of a while() loop. This allows us to continually check that the Next node in the list is not null. If we accidentally end up trying to traverse on a node that is null, a NullReferenceException gets thrown and our program will crash/end.

- Traversal Big O If we are looking for a specific node Big O of time: O(n) Big O of space: O(1) If we are adding a new node Big O of time: O(1) Big O of space: O(1)