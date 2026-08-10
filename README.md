# Prolog Family Tree

## About the Project

This project demonstrates a simple family relationship system using Prolog.
It represents family members, parent relationships, gender, and rules to find
different family relationships.

## Technologies Used

- Prolog
- SWI-Prolog
- Visual Studio Code
- Git & GitHub

## Features

- Find parents
- Find father
- Find mother
- Find grandparents
- Find grandfather
- Find siblings

## Family Members

The program contains the following family members:

- Tom
- Bob
- Liz
- Pam
- Ann
- Pat
- Jim

## Prolog Rules

The program defines the following relationships:

- `parent(X,Y)`
- `father(X,Y)`
- `mother(X,Y)`
- `grandparent(X,Y)`
- `grandfather(X,Y)`
- `sibling(X,Y)`

## Example Queries

```prolog
?- parent(bob, X).
X = pam ;
X = ann ;
X = pat.
