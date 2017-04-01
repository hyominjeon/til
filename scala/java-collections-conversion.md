# Java and Scala Collection Conversions

### Implicit bidirectional conversion

supported in the JavaConverters object

Scala | Java
------|------
Iterator|Iterator
Iterator|Enumeration
Iterable|Iterable
Iterable|Collection
Buffer|List
Set|Set
Map|Map
ConcurrentMap|ConcurrentMap

### example of usage

```scala
import collection.JavaConverters._
import collection.mutable

val jul: java.util.List[Int] = ArrayBuffer(1, 2, 3).asJava
val buf: Seq[Int] = jul.asScala
val m: java.util.Map[String, Int] = HashMap("abc" -> 1, "hello" -> 2).asJava
```

Conversion works by setting up a "wrapper" object that forwards all operations to the underlying collection object. So collections are never copied when converting between Java and Scala. If you do a round-trip conversion from a Java type to Scala type and back to Java type, you end up with the identical collection object you started with.

### One way conversion from Scala to Java

Scala | Java
------|------
Seq|List
mutable.Seq|List
Set|Set
Map|Map

Because Java doesn't distinguish between mutable and immutable collections, a conversion from Scala immutable collections will yield a Java List where all mutation operations throw an "UnsupportedOperationException"

```scala
val jul = List(1, 2, 3).asJava
jul.add(7) -> throws java.lang.UnsupportedOperationException
```

all are from [Scala Documentation](http://docs.scala-lang.org/overviews/collections/conversions-between-java-and-scala-collections.html)
