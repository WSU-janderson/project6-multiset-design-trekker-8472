[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-22041afd0340ce965d47ae6ef1cefeee28c7c493a6346c4f15d667ab976d596c.svg)](https://classroom.github.com/a/fGHNCM3V)
# Project 6 - MultiSet Design

The project descriptinon is in the [PDF](MultiSet_Fall25.pdf) located in this repo.

You will need to add any and all files you use for this project into this repository.

Remember to commit your changes regularly, just like you would with a programming assignment.

RTS Army build
    pros can set army cap; limited types of troops; not given as a specific type
        on the pdf, may be more unique
    cons not given as a specific type on the pdf, may be more unique

Different possibilities for the Data Structure
    Sequence: more or less a linked list: each change will have to iterate through the array to edit the appropriate one
    Hash table: unique ID per unit can limit size to total possible Unit count
    AVLTree cannot be a binary search tree in this instance easily; not the best to do

Intro:

    Working with a data multiset to create the basis to store something viable for a game, I chose to work with 
the idea of a real time strategy game (RTS).  I want to keep ary unit maintenance inside a HashTable<string, 
unsigned int>.