0x1D. C - Binary trees
its a project about 
Basic Binary Tree which entails 
/**
 * struct binary_tree_s - Binary tree node
 *
 * @n: Integer stored in the node
 * @parent: Pointer to the parent node
 * @left: Pointer to the left child node
 * @right: Pointer to the right child node
 */
struct binary_tree_s
{
    int n;
    struct binary_tree_s *parent;
    struct binary_tree_s *left;
    struct binary_tree_s *right;
};

typedef struct binary_tree_s binary_tree_t;
Binary Search Tree
typedef struct binary_tree_s bst_t;
AVL Tree
typedef struct binary_tree_s avl_t;
Max Binary Heap
typedef struct binary_tree_s heap_t;
Note: For tasks 0 to 23 (included), you have to deal with simple binary trees. They are not BSTs, thus they don’t follow any kind of rule.

Print function
To match the examples in the tasks, you are given this function

This function is used only for visualization purposes. You don’t have to push it to your repo. It may not be used during the correctin
which has the following tasks

. New node
mandatory
Score: 0.0% (Checks completed: 0.0%)
Write a function that creates a binary tree node

1. Insert left
mandatory
Score: 0.0% (Checks completed: 0.0%)
Write a function that inserts a node as the left-child of another node
2. Insert right
mandatory
Score: 0.0% (Checks completed: 0.0%)
Write a function that inserts a node as the right-child of another node
3. Delete
mandatory
Score: 0.0% (Checks completed: 0.0%)
Write a function that deletes an entire binary tree
4. Is leaf
mandatory
Score: 0.0% (Checks completed: 0.0%)
Write a function that checks if a node is a leaf
5. Is root
mandatory
Score: 0.0% (Checks completed: 0.0%)
Write a function that checks if a given node is a root
6. Pre-order traversal
mandatory
Score: 0.0% (Checks completed: 0.0%)
Write a function that goes through a binary tree using pre-order traversal

7. In-order traversal
mandatory
Score: 0.0% (Checks completed: 0.0%)
Write a function that goes through a binary tree using in-order traversal
8. Post-order traversal
mandatory
Score: 0.0% (Checks completed: 0.0%)
Write a function that goes through a binary tree using post-order traversal
9. Height
mandatory
Score: 0.0% (Checks completed: 0.0%)
Write a function that measures the height of a binary tree
10. Depth
mandatory
Score: 0.0% (Checks completed: 0.0%)
Write a function that measures the depth of a node in a binary tree
11. Size
mandatory
Score: 0.0% (Checks completed: 0.0%)
Write a function that measures the size of a binary tree
12. Leaves
mandatory
Score: 0.0% (Checks completed: 0.0%)
Write a function that counts the leaves in a binary tree
13. Nodes
mandatory
Score: 0.0% (Checks completed: 0.0%)
Write a function that counts the nodes with at least 1 child in a binary tree
14. Balance factor
mandatory
Score: 0.0% (Checks completed: 0.0%)
Write a function that measures the balance factor of a binary tree
Write a function that checks if a binary tree is full

Prototype: int binary_tree_is_full(const binary_tree_t *tree);
Where tree is a pointer to the root node of the tree to check
If tree is NULL, your function must return 0
16. Is perfect
mandatory
Score: 0.0% (Checks completed: 0.0%)
Write a function that checks if a binary tree is perfect
17. Sibling
mandatory
Score: 0.0% (Checks completed: 0.0%)
Write a function that finds the sibling of a node

Prototype: binary_tree_t *binary_tree_sibling(binary_tree_t *node);
Where node is a pointer to the node to find the sibling
Your function must return a pointer to the sibling node
If node is NULL or the parent is NULL, return NULL
If node has no sibling, return NULL
18. Uncle
mandatory
Score: 0.0% (Checks completed: 0.0%)
Write a function that finds the uncle of a node

Prototype: binary_tree_t *binary_tree_uncle(binary_tree_t *node);
Where node is a pointer to the node to find the uncle
Your function must return a pointer to the uncle node
If node is NULL, return NULL
If node has no uncle, return NULL

