# C - Binary trees

![image](https://user-images.githubusercontent.com/32038582/207987097-738b89fa-ae94-43bd-8f5a-212a6620d978.png)

A binary tree is a rooted tree that is also an ordered tree (a.k.a. plane tree) in which every node has at most two children. A rooted tree naturally imparts a notion of levels (distance from the root), thus for every node a notion of children may be defined as the nodes connected to it a level below. Ordering of these children

## Tests :heavy_check_mark:

* [tests](./tests): Folder of test files for all tasks. Provided by Holberton
School.

## Helper File :raised_hands:

* [binary_tree_print.c](./binary_tree_print.c): C function that prints binary
trees in a pretty way.

## Header File :file_folder:

* [binary_trees.h](./binary_trees.h): Header file containing definitions and
prototypes for all types and functions written for the project.

Data Structures
```
struct binary_tree_s
{
    int n;
    struct binary_tree_s *parent;
    struct binary_tree_s *left;
    struct binary_tree_s *right;
};

typedef struct binary_tree_s binary_tree_t;
typedef struct binary_tree_s bst_t;
typedef struct binary_tree_s avl_t;
typedef struct binary_tree_s heap_t;
```


## Authors :black_nib:

* __Christopher Akinsanmi__ <[Swapdevs](https://github.com/Swapdevs)>
