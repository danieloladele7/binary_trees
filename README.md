# 0x1D. C - Binary trees
## Resources:
- [Binary tree](https://en.wikipedia.org/wiki/Binary_tree) (note the first line: Not to be confused with B-tree.)
- [Data Structure and Algorithms](https://intranet.alxswe.com/rltoken/QmcTMCkQyrgMjrqoWxYdhw) - Tree
- [Tree Traversal](https://intranet.alxswe.com/rltoken/z6ZaXr_RxwE5nTHAUx_dfQ)
- [Binary Search Tree](https://intranet.alxswe.com/rltoken/qO5dBlMnYJzbaWG3xVpcnQ)
- [Data structures: Binary Tree](https://intranet.alxswe.com/rltoken/BeyJ2gjlE7_djwRiDyeHig)

## Betty code style:
To use [betty](https://github.com/holbertonschool/Betty) style:

`cd binary_trees/Betty`, and `sudo ./install.sh`

Then test script: `betty <script_name>`


## Project Learning Objectives
- What is the binary tree
- What is the difference between a binary tree and a Binary Search Tree
- What is the possible gain in terms of time complexity compared to linked lists
- What are the depth, the height, the size of a binary tree
- What are the different traversal methods to go through a binary tree
- What is a complete, a full, a perfect, a balanced binary tree

## Requirements
- Allowed editors: `vi`, `vim`, `emacs`
- All your files will be compiled on `Ubuntu 20.04 LTS` using `gcc`, using the options `-Wall -Werror -Wextra -pedantic -std=gnu89`
- All your files should end with a new line
- A `README.md` file, at the root of the folder of the project, is mandatory
- Your code should use the Betty style. It will be checked using `betty-style.pl` and `betty-doc.pl`
- You are not allowed to use global variables
- No more than 5 functions per file
- You are allowed to use the standard library
- In the following examples, the `main.c` files are shown as examples. You can use them to test your functions, but you don’t have to push them to your repo (if you do we won’t take them into account). We will use our own `main.c` files at compilation. Our `main.c` files might be different from the one shown in the examples
- The prototypes of all your functions should be included in your header file called `binary_trees.h`
- Don’t forget to push your header file
- All your header files should be include guarded

## Creating New Binaries
For simplicity in creating binaries add all previous tasks i.e
`gcc -Wall -Wextra -Werror -pedantic binary_tree_print.c main/<tasks-main.c> <task.c> <...previous-tasks.c> -o <binary_name>` example
`gcc -Wall -Wextra -Werror -pedantic binary_tree_print.c main/1-main.c 1-binary_tree_insert_left.c 0-binary_tree_node.c -o 1-left`

## Testing binaries
`./<task_name>` e.g `./0-node`

## Some Terminologies
- **Node**:
- **Root**:
- **Tree**:
- **Child**:
- **Tree Depth**: 
- **Leaf**:
- **Uncle**: In a binary tree, an uncle of a node is the sibling of its parent node. In other words, the uncle of a node is the parent’s sibling. For example, in the binary tree below, node 6 has two uncles: nodes 2 and 7. 
```
          1
        /   \
       2     3
     /  \   /  \
    4    5 6    7
```
- **Siblings**:
- **Lowest Common Ancestor**: The lowest common ancestor (LCA) of two nodes x and y in a binary tree is the lowest (i.e., deepest) node that has both x and y as descendants, where each node can be a descendant of itself (so if x is reachable from w, w is the LCA). In other words, the LCA of x and y is the shared ancestor of x and y that is located farthest from the root.
- Uncle: 