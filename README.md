# COMP 271 002 F17 Lab 5 (Week 7)

# Team project

Work in teams of two, optionally.

# Objectives

An understanding of the following concepts and techniques:

- ADT implementation perspective
- stack ADT
- dynamically allocated objects
- implementing stack as linked list
- algorithms based on the stack's LIFO policy
- interface-based testing

# Instructions

In this lab, you will have the opportunity to implement a generic stack as a linked list and use this implementation to solve a simple problem.

Specifically:

1. Complete the TODO items in the `LinkedStack` implementation until the tests pass.
1. Complete the main class `ReverseLines`, which reads successive input lines until EOF and then prints themin reverse order, using a suitable stack instance.
1. Answer the following questions:
   - Why does `LinkedStack` not require an explicit constructor?
   - What is the time and (extra) space complexity of each of the `LinkedStack` methods, as well as `ReverseLines.main`?
   - How else (not using `Node`) could we have implemented `LinkedStack` in such a way that it is still based on a linked list but the `asList` method uses constant time and space?
   - Is it better for `push` and `pop` to return the item or the stack itself?
    Briefly discuss the pros and cons of each design.

# Grading

- 8 submission via GitHub
- 16 completion of items marked TODO in `LinkedStack` and tests passing
- 8 completion of `ReverseLines` and correct behavior
- 8 written part
  - 6 responses to the questions above
  - 2 grammar, style, formatting

*40 points TOTAL*
