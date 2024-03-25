An visualization way to represent linked list using json format

![[CleanShot 2024-03-25 at 10.18.26@2x.png]]
![[CleanShot 2024-03-25 at 10.19.06@2x.png]]

*Code inside code editor:*

```python
head = {
	"value": 11,
	"next": {
		"value": 3,
		"next": {
			"value": 23,
			"next": {
				"value": 7,
				"next": None
			}
		}
	}
}

print (head['next']['next']['value'])

# This will print out 23

```

