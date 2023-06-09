# C - Binary trees

<html>
<div class="panel panel-default" id="project-description">
 <div class="panel-body">
  <h2>
   Resources
  </h2>
  <p>
   <strong>
    Read or watch
   </strong>
   :
  </p>
  <ul>
   <li>
    <a href="https://en.wikipedia.org/wiki/Binary_tree" target="_blank" title="Binary tree">
     Binary tree
    </a>
    (
    <em>
     note the first line:
     <code>
      Not to be confused with B-tree.
     </code>
    </em>
    )
   </li>
   <li>
    <a href="https://www.tutorialspoint.com/data_structures_algorithms/tree_data_structure.htm" target="_blank" title="Data Structure and Algorithms - Tree">
     Data Structure and Algorithms - Tree
    </a>
   </li>
   <li>
    <a href="https://www.tutorialspoint.com/data_structures_algorithms/tree_traversal.htm" target="_blank" title="Tree Traversal">
     Tree Traversal
    </a>
   </li>
   <li>
    <a href="https://en.wikipedia.org/wiki/Binary_search_tree" target="_blank" title="Binary Search Tree">
     Binary Search Tree
    </a>
   </li>
   <li>
    <a href="https://www.youtube.com/watch?v=H5JubkIy_p8" target="_blank" title="Data structures: Binary Tree">
     Data structures: Binary Tree
    </a>
   </li>
  </ul>
  <h2>
   Learning Objectives
  </h2>
  <p>
   At the end of this project, you are expected to be able to
   <a href="https://fs.blog/feynman-learning-technique/" target="_blank" title="explain to anyone">
    explain to anyone
   </a>
   ,
   <strong>
    without the help of Google
   </strong>
   :
  </p>
  <h3>
   General
  </h3>
  <ul>
   <li>
    What is a binary tree
   </li>
   <li>
    What is the difference between a binary tree and a Binary Search Tree
   </li>
   <li>
    What is the possible gain in terms of time complexity compared to linked lists
   </li>
   <li>
    What are the depth, the height, the size of a binary tree
   </li>
   <li>
    What are the different traversal methods to go through a binary tree
   </li>
   <li>
    What is a complete, a full, a perfect, a balanced binary tree
   </li>
  </ul>
  <h2>
   Requirements
  </h2>
  <h3>
   General
  </h3>
  <ul>
   <li>
    Allowed editors:
    <code>
     vi
    </code>
    ,
    <code>
     vim
    </code>
    ,
    <code>
     emacs
    </code>
   </li>
   <li>
    All your files will be compiled on Ubuntu 20.04 LTS using gcc, using the options -Wall -Werror -Wextra -pedantic -std=gnu89
   </li>
   <li>
    All your files should end with a new line
   </li>
   <li>
    A
    <code>
     README.md
    </code>
    file, at the root of the folder of the project, is mandatory
   </li>
   <li>
    Your code should use the
    <code>
     Betty
    </code>
    style. It will be checked using
    <a href="https://github.com/holbertonschool/Betty/blob/master/betty-style.pl" target="_blank" title="betty-style.pl">
     betty-style.pl
    </a>
    and
    <a href="https://github.com/holbertonschool/Betty/blob/master/betty-doc.pl" target="_blank" title="betty-doc.pl">
     betty-doc.pl
    </a>
   </li>
   <li>
    You are not allowed to use global variables
   </li>
   <li>
    No more than 5 functions per file
   </li>
   <li>
    You are allowed to use the standard library
   </li>
   <li>
    In the following examples, the
    <code>
     main.c
    </code>
    files are shown as examples. You can use them to test your functions, but you don’t have to push them to your repo (if you do we won’t take them into account). We will use our own
    <code>
     main.c
    </code>
    files at compilation. Our
    <code>
     main.c
    </code>
    files might be different from the one shown in the examples
   </li>
   <li>
    The prototypes of all your functions should be included in your header file called
    <code>
     binary_trees.h
    </code>
   </li>
   <li>
    Don’t forget to push your header file
   </li>
   <li>
    All your header files should be include guarded
   </li>
  </ul>
  <h3>
   GitHub
  </h3>
  <p>
   <strong>
    There should be one project repository per group. If you clone/fork/whatever a project repository with the same name before the second deadline, you risk a 0% score.
   </strong>
  </p>
  <h2>
   More Info
  </h2>
  <h3>
   Data structures
  </h3>
  <p>
   Please use the following data structures and types for binary trees. Don’t forget to include them in your header file.
  </p>
  <h4>
   Basic Binary Tree
  </h4>
  <pre><code>/**
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
</code></pre>
  <h4>
   Binary Search Tree
  </h4>
  <pre><code>typedef struct binary_tree_s bst_t;
</code></pre>
  <h4>
   AVL Tree
  </h4>
  <pre><code>typedef struct binary_tree_s avl_t;
</code></pre>
  <h4>
   Max Binary Heap
  </h4>
  <pre><code>typedef struct binary_tree_s heap_t;
</code></pre>
  <p>
   <strong>
    Note:
   </strong>
   For tasks 0 to 23 (included), you have to deal with simple binary trees. They are not BSTs, thus they don’t follow any kind of rule.
  </p>
  <h3>
   Print function
  </h3>
  <p>
   To match the examples in the tasks, you are given
   <a href="https://github.com/holbertonschool/0x1C.c" target="_blank" title="this function">
    this function
   </a>
  </p>
  <p>
   This function is used only for visualization purposes. You don’t have to push it to your repo. It may not be used during the correction
  </p>
 </div>
</div>

[--LINK PROJECT--](https://intranet.hbtn.io/projects/270)
</html>
