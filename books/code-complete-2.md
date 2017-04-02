# Code Compete 2

## Chapter 5: Design in Construction

### 5.3: Design Building Blocks: Heuristics

#### Find Real-World Objects

Steps in designing with objects:
1. Identify the objects and their attributes (methods and data).
1. Determine what can be done to each object.
1. Determine what each object is allowed to do to other objects.
   * Which objects contain which other objects?
   * Which objects can inherit from which other objects?
1. Determine the parts of each object that will be visible to other objects.
1. Define each object's public interfaces.

When finished going through the steps to achieve a top-level object-oriented system organization:
* Iterate on the top-level system organization to get a better organization of classes.
* Iterate on each of the classes defined, driving the design of each class to a more detailed level.

## Chapter 9: The Pseudocode Programming Process

### 9.3: Constructing Routines by Using the PPP

#### Check the Code

* 우선 눈으로 체크하고 컴파일 하기.

> The "Just One More Compile" syndrome leads to hasty, error prone changes that take more time in the 
long run. Avoid the rush to completion by not compiling until you've convinced yourself that the 
routine is right.

> Compiling before you're sure your program works is often a symptom of the hacker mindset.

* 디버거 이용하기.

> If you find that a routine is unusually buggy, start over. Don't hack around it - rewrite it. Hacks 
usually indicate incomplete understanding and guarantee errors both now and later. Creating an 
entirely new design for a buggy routine pays off.

## Chapter 11: The Power of Variable Names

### 11.5 Standarized Prefixes

Provides a terse but consistent and readable approach to naming data

#### User-Defined Type Abbreviations

Identifies the data type of the object or variable being named

##### Examples

UDT Abbreviation | Meaning
:---------------:|:------:
doc|document
pa|paragraph
sel|selection
wn|window

```
Doc activeDoc;
Pa firstPa;
Wn wnMain;
```

#### Semantic Prefixes

Describes how the variable or object is used

##### Examples

Semantic Prefix | Meaning
:---------------:|:------:
c|count
i|index into an array
p|pointer

#### Advantage of Standarized Prefixes

* fewer names to remember
* precision to naming
* compact names
* easier type checking when using abstract data types that compiler can't check
* pitfall: neglecting to give the variable a meaningful name in addition to its prefix
