# Github Markdown

## Texts

### Bold

```
**bold**
__also bold__
```
**bold**
__also bold__

### Italic

```
*italic*
_also italic_
```
*italic*
_also italic_

### Strickthrough

```
~~strickthrough~~
```
~~strickthrough~~

### Emojis

```
:sparkles: :boom:
```
:sparkles: :boom:

### Link

```
[inline-style](www.google.com)
[reference-style][this can be number or text]
[link itself]

[this can be number or text]: www.google.com
[link itself]: www.google.com
```
[inline-style](www.google.com)
[reference-style][this can be number or text]
[link itself]

[this can be number or text]: www.google.com
[link itself]: www.google.com

## Lists

### Ordered

```
1. one
  1. sub-one
1. two
```
1. one
  1. sub-one
1. two

### Unordered

```
* bullet point
  * subpoint
- same with
  - dashes
  + and pluses
```
* bullet point
  * subpoint
- same with
  - dashes
  + and pluses

### Task List

```
- [x] task done
- [ ] task undone
```
- [x] task done
- [ ] task undone

## Code

### Inline Code Block

```
`inline code block`
```
`inline code block`

### Multiple Line Code Block

````
    if (longerBlockOfCode) {
        return indentFourSpaces();
    }
```
if (tooLazyToIndent) {
    return useCodeFencing();
}
```
````
    if (longerBlockOfCode) {
        return indentFourSpaces();
    }
```
if (tooLazyToIndent) {
    return useCodeFencing();
}
```

### Syntax Highlighting

````
```java
if (wantSyntaxHighlighting) {
    return includeLanguage();
}
```
````

```java
if (wantSyntaxHighlighting) {
    return includeLanguage();
}
```

## Formatting

### Headers

```
# H1
## H2
### H3
#### H4
##### H5
###### H6
H1
==
H2
--
```
# H1
## H2
### H3
#### H4
##### H5
###### H6
H1
==
H2
--

### Quotes

```
> quotes
```
> quotes

### Tables

```
Column 1 | Column 2
--------:|:-------:
left | centered
aligned | yay
```
Column 1 | Column 2
--------:|:-------:
left | centered
aligned | yay

## Others

### Mentions

```
@hyominjeon
```
@hyominjeon

### Images

```
![inline](https://static.pexels.com/photos/106144/rubber-duck-bath-duck-toys-costume-106144.jpeg "random picture")

![reference][1]

[1]: https://static.pexels.com/photos/106144/rubber-duck-bath-duck-toys-costume-106144.jpeg
```
![inline](https://static.pexels.com/photos/106144/rubber-duck-bath-duck-toys-costume-106144.jpeg "random picture")

![reference][1]

[1]: https://static.pexels.com/photos/106144/rubber-duck-bath-duck-toys-costume-106144.jpeg "the same picture"

### SHA References

```
24fa920b32dd663ab7cef3d2269c5c93ea380c1f
hyominjeon@24fa920b32dd663ab7cef3d2269c5c93ea380c1f
hyominjeon/til@24fa920b32dd663ab7cef3d2269c5c93ea380c1f
```
24fa920b32dd663ab7cef3d2269c5c93ea380c1f
hyominjeon@24fa920b32dd663ab7cef3d2269c5c93ea380c1f
hyominjeon/til@24fa920b32dd663ab7cef3d2269c5c93ea380c1f

### Issue References

```
#1
hyominjeon#1
hyominjeon/til#1
```
#1
hyominjeon#1
hyominjeon/til#1

### Horizontal Lines

```
Hyphens
---
Asterisks
***
Underscores
___
```
Hyphens
---
Asterisks
***
Underscores
___
