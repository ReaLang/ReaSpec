# Rea Spec

## Introduction

### What is Rea

Rea is a recently designed new form of language targeting system programing. Rea aims to be a better C++ without most complicated parts of it. Rea take advantages of OOP but only has part of it. In rea, we call `class` and `struct` in other languages "data constraint". There are two types of "data constraint", both of them act mostly same as `class` or `struct` in other languages, but none of them can inherit or be inherited from others, which means all methods are not virtual there is no virtual table in Rea. However, we define a new type call interface. In interfaces, you can only define methods or properties. Only one kind of "data constraint" can implement interfaces. Interface types can be used as a parameter or local variable. But they are boxed  "data constraint" and can't be converted back. By this way, Rea takes advantages of OOP and avoid disadvantages of it.

## Roadmap

[Roadmap](./roadmap.md)

