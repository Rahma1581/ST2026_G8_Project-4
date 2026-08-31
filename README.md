# C++ Trie (Prefix Tree) Implementation

A high-performance C++ implementation of a **Trie** (Prefix Tree) data structure designed for efficient string storage, exact search, prefix matching, and dynamic autocomplete operations. 

---

# Project Overview

A Trie is a tree-like data structure that stores a dynamic set of strings where keys are usually strings. Unlike a standard binary search tree, no node in the tree stores the key associated with that node; instead, its position in the tree defines the key it is associated with.

This project implements a complete `Trie` class supporting $O(L)$ operations (where $L$ is the length of the string), including recursive deletion with dynamic branch pruning and limited prefix auto-completion.

---

# Key Features

* **Core Operations**: Fast insertion, exact word search, and prefix validation (`startsWith`).
* **Autocomplete Engine**: Retrieve suggestions for a given prefix, with optional search limits.
* **Dynamic Pruning**: Safe node deletion that removes unused branches while preserving overlapping words.
* **Analytics**: Subtree word counting, overall unique word metrics, and longest prefix matching.
* **Memory Safe**: Full post-order recursive cleanup on tree destruction or manual resets.
