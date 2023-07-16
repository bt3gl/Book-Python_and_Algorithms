## trees

<br>


### `Tree.py`

<br>

```python
> python3 Trees.py


🌴🌴🌴 Testing SimpleTree 🌴🌴🌴
a
	b
		d
		e
	c
		h
		g



🌳🌳🌳 Testing BinaryTree 🌳🌳🌳

🟡 Adding [4, 1, 4, 6, 7, 9, 10, 5, 11, 5] to the tree...
🟢 Printing the tree in preorder...
4
1
6
9
5
5
11
10
7
4

🟢 Searching for node 5: True
❌ Searching for node 15: False
❌ Is root a leaf? False
🟢 Is root full? True
❌ Is the tree balanced? False
❌ Is the tree a binary search tree? False


🎄🎄🎄 Testing BinarySearchTree 🎄🎄🎄

🟡 Adding [4, 1, 4, 6, 7, 9, 10, 5, 11, 5] to the tree...
❌ Item 4 not added as BSTs do not support repetition.
❌ Item 5 not added as BSTs do not support repetition.
🟢 Printing the tree in preorder:
4
1
6
5
7
9
10
11

🟢 Searching for node 5: True
❌ Searching for node 15: False
❌ Is root a leaf? False
🟢 Is root full? True
🟢 Largest node? 11
🟢 Smallest node? 1
❌ Is the tree balanced? False
🟢 Is the tree a binary search tree? True
```

<br>

### `BinaryTree.py`

<br>

* a clean implementation adapted from the class above.

```python
> python3 BinaryTree.py

🌳🌳🌳 Testing BinaryTree 🌳🌳🌳

🟡 Adding [4, 1, 4, 6, 7, 9, 10, 5, 11, 5] to the tree...
🟢 Print the tree preorder: [4, 1, 6, 9, 5, 5, 11, 10, 7, 4]
🟢 Print the tree inorder: [4, 1, 6, 9, 5, 5, 11, 10, 7, 4]
🟢 Print the tree postorder: [4, 1, 6, 9, 5, 5, 11, 10, 7, 4]

🟢 Search for node 5: True
❌ Search for node 15: False
```