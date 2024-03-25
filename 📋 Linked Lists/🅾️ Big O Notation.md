### Big O

#### Append a new node to the end of the list

![[CleanShot 2024-03-25 at 09.42.44@2x.png]]

- We have the last node point to the new node.
	![[CleanShot 2024-03-25 at 09.43.33@2x 1.png]]

- Then add it into the list.
	![[CleanShot 2024-03-25 at 09.44.00@2x.png]]

	=> This is **O(1)**, because:
	> No matter how long the linked list is (how many items that it has), the time complexity is the same.

#### Remove the last node from the linked list

![[CleanShot 2024-03-25 at 09.46.50@2x.png]]

- Iterate through all of the elements inside the list to get to the point of the node that is placed before the removed node.
	![[CleanShot 2024-03-25 at 09.48.19@2x 1.png]]

- Then set tail equals to the pointer of the second last most :>
	![[CleanShot 2024-03-25 at 09.49.12@2x.png]]

=> Big O is **O(n)**, because we have to iterate through the entire list. 
#### Append a new node to the beginning of the list

![[CleanShot 2024-03-25 at 09.50.21@2x.png]]

- Set the next pointer from the new node to the current head of the linked list.
	![[CleanShot 2024-03-25 at 09.52.31@2x.png]]

- Then set the head of the linked list to the new node.
	![[CleanShot 2024-03-25 at 09.53.02@2x.png]]

=> Big O is O(1) because it does not matter how long the linked list is.
#### Insert a new node to an index inside the linked list

![[CleanShot 2024-03-25 at 09.54.11@2x.png]]

- Iterate through the linked list until we get to the node that we want to insert the new to node.
	![[CleanShot 2024-03-25 at 09.55.23@2x.png]]

- Set the pointer from the new node to the next node of the inserted node.
	![[CleanShot 2024-03-25 at 09.56.14@2x.png]]

- Then set the pointer of the inserted node to the new node.
	![[CleanShot 2024-03-25 at 09.56.50@2x.png]]

	![[CleanShot 2024-03-25 at 09.57.23@2x 1.png]]


#### Search a node inside the linked list

![[CleanShot 2024-03-25 at 10.13.34@2x.png]]

- Iterate through all of the nodes inside the list until find the index 2.
=> The Big O is **O(n)**



### Compare Linked Lists to Lists

![[CleanShot 2024-03-25 at 10.15.40@2x.png]]

