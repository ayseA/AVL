AVL
===

AVL -- standard AVL and some more tree methods as explained in the code. 

Standard AVL: keeps "height" info to operate on on every tree node. 

The following are the signatures of the methods outside the standard AVL description. Each method is explained in its comments.

public Node<K,V> CommonAncestor(Node<K,V> node1, Node<K,V> node2);
public boolean compare (Node<K,V> node, Node<K,V> foreignNode);
public int treeDepth(Node <K,V> node) {  
public Node<K,V> clone (Node<K,V> root);
public void printListFull(List k);
public int diameter(Node<K,V> root);
public List atLvl(Node<K,V> node, int level);
public void preOrderWPar(Node<K,V> node);
public void postOrderWPar (Node<K,V> node);
public void inOrder(Node<K,V> node);
public List inOrderList(Node<K,V> node);

Helper methods: 
==============
private List concatLists(List l1, List l2);
private void checkBrute(Node<K,V> node);
