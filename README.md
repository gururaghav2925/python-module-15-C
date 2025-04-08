# Build an Expression Tree and Print Inorder and Postorder Traversals

## Aim
To build an expression tree from a predefined list of operators and operands, and perform inorder and postorder traversals on the tree.

## Procedure
1. Create a `Node` class to represent each node in the tree.
2. Manually build the expression tree from the list `x = ['*', '+', '-', 9, 3, 8, 4]` based on its structure.
   - Treat it as a binary expression tree:
     ```
            *
          /   \
         +     -
        / \   / \
       9   3 8   4
     ```
3. Implement recursive functions for:
   - Inorder traversal (left, root, right)
   - Postorder traversal (left, right, root)
4. Print both traversal results.

## Python Program
```python
from binarytree import build,Node
x=['*','+','-',9,3,8,4]
t=build(x)
print(t.inorder)
print(t.postorder)
```

# Output:
![image](https://github.com/user-attachments/assets/b14c5387-3397-44b6-a9f5-4aaaa56899eb)
## Result:
thus the program succesffuly completed the Build an Expression Tree and Print Inorder and Postorder Traversals and executrd successfully.
