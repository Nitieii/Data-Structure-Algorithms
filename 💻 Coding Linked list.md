```python
class Node:
	def __init__(self, value):
		self.value = value
		self.next = None
	
class LinkedList:
	# This contructor will be used to create a new node
	def __init__(self, value):
		new_node = Node(value)
		self.head = new_node
		self.tail = new_node
		self.length = 1

	# This function will be used to add node to the end of the list
	def append(self, value):
		new_node = Node(value)
		
		if self.head is None:
			self.head = new_node
			self.tail = new_node
		else:
			self.tail.next = new_node
			self.tail = new_node
		
		self.length += 1
		return True

	# This function will be used to add node to the beginning of the list
	def prepend(self, value):

	# This function will be used to insert node to a position inside the       list
	def insert(self, value):
		
	# This function will print all of the linked list
	def print_list(self):
		temp = self.head
		while temp is not Node:
			print(temp.value)
			temp = temp.next	

```