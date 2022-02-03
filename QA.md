### 1. Is Scala 3 Dotty sound?

> Dotty is a compiler for the development of Scala 3 with DOT Calculus. DOT is a type-calculus used to prove that Dotty’s language specification and its type system are sound. DOT validates the language specification correctness formally. The compiler research team has been developing this to have a core and sound understanding of the foundation of Scala 3’s type system

Sources :

* [Essence of Scala, Martin Odersky : Scala Blog ](https://www.scala-lang.org/blog/2016/02/03/essence-of-scala.html)
* [Introduction to Dotty and Scala 3, Milad khajavi: Baeldung Scala](https://www.baeldung.com/scala/dotty-scala-3)

### 1. Why does Scala does not have the Hindley-Milner type system?

According to Scala's creator, Martin Odersky:
> The reason Scala does not have Hindley/Milner type inference is that it is very difficult to combine with features such as overloading (the ad-hoc variant, not type classes), record selection, and subtyping. I’m not saying impossible — there exist a number of extensions that incorporate these features; in fact I have been guitly of some of them myself. I’m just saying it’s very difficult to make this work well in practice, where one needs to have small type expressions, and good error messages. It’s not a shut case either — many researchers are working on pushing the boundaries here (look for instance at Remy’s MLF). But right now it is a tradeoff of better type inferencing vs better support for these features. You can make the tradeoff both ways. The fact that we wanted to integrate with Java tipped the scales in favor of subtyping and away from Hindley/Milner.

* [Universal Type Inference is a Bad Thing, Martin Odersky? : CodeCommit Scala Blog](http://www.codecommit.com/blog/scala/universal-type-inference-is-a-bad-thing)
