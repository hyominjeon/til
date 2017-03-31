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
[inline-style](http://www.google.com)

[reference-style][this can be number or text]

[link itself]

[this can be number or text]: http://www.google.com
[link itself]: http://www.google.com

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

### Images

```
![inline](https://github.com/hyominjeon/til/blob/master/github/sample-image.jpeg "random picture")

![reference][1]

[1]: https://github.com/hyominjeon/til/blob/master/github/sample-image.jpeg "the same random picture"
```
![inline](https://github.com/hyominjeon/til/blob/master/github/sample-image.jpeg "random picture")

![reference][1]

[1]: https://github.com/hyominjeon/til/blob/master/github/sample-image.jpeg "the same random picture"

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
