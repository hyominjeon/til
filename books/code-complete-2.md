# Code Compete 2

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

* provides a terse but consistent and readable approach to naming data

#### User-Defined Type Abbreviations

* identifies the data type of the object or variable being named

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

* describes how the variable or object is used

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
