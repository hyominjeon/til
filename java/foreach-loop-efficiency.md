# Foreach Loop Efficiency

I've always felt uneasy writing foreach loop the following way:
```java
for (String s : veryExpensiveStringListGenerator()) {
    doSomthing(s);
}
```
because I wasn't sure if the `veryExpensiveIntListGenerator()` is called only once. But according to 
the [Java 5 doc](http://docs.oracle.com/javase/1.5.0/docs/guide/language/foreach.html) (where foreach 
was first introduced in Java), the code above is equivalant to:
```java
for (Iterator<String> iter = veryExpensiveStringListGenerator().iterator(); i.hasNext(); ) {
    doSomething(iter.next());
}
```
Meaning `veryExpensiveStringListGenerator()` is called only once and I'm good to breathe a sigh of 
relief :)
