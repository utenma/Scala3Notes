<div align="center">
  <img height="50" src="https://user-images.githubusercontent.com/19735362/133747096-377b039a-e41a-49ad-bf57-2b3674f5c098.png">
</div>

## Scala Books 📗 

* [Progamming in Scala](https://www.artima.com/shop/programming_in_scala_5ed) by [@odersky](https://github.com/odersky) [@lexspoon](https://github.com/lexspoon) [@bvenners](https://github.com/bvenners) [@fsommers](https://github.com/fsommers)

* [Hands on Scala](https://www.handsonscala.com) by [@lihaoyi](https://github.com/lihaoyi)

* [Programming Scala](https://www.oreilly.com/library/view/programming-scala-3rd/9781492077886/) by [@deanwampler](https://github.com/deanwampler)

## Scala Lectures 📔

* [Twitter's Scala School](https://twitter.github.io/scala_school)

## Scala Courses 🎓

### Coursera 

Functional Programming in Scala Specialization by EPFL

1. [Functional Programming Principles in Scala](https://www.coursera.org/learn/scala-functional-programming) by [@odersky](https://github.com/odersky)
2. [Functional Program Design in Scala](https://www.coursera.org/learn/scala-functional-program-design) by [@odersky](https://github.com/odersky)
3. [Parallel programming](https://www.coursera.org/learn/scala-parallel-programming) by [@vkuncak](https://github.com/vkuncak) and [axel22](https://github.com/axel22)
4. [Big Data Analysis with Scala and Spark](https://www.coursera.org/learn/scala-spark-big-data) by [@heathermiller](https://github.com/heathermiller)
5. [Functional Programming in Scala Capstone](https://www.coursera.org/learn/scala-capstone) by [@julienrf](https://github.com/@julienrf)

Supplementary courses by EPFL

6. [Effective Programming in Scala](https://www.coursera.org/learn/effective-scala) by [@julienrf](https://github.com/@julienrf) [@noelwelsh](https://github.com/noelwelsh)
7. [Programming Reactive Systems](https://www.coursera.org/learn/scala-akka-reactive) by [@odersky](https://github.com/odersky) [@rkuhn](https://github.com/rkuhn) [@ktoso](https://github.com/ktoso) [@julienrf](https://github.com/@julienrf)

### Rock the JVM
* [Scala at Light Speed](https://rockthejvm.com/p/scala-at-light-speed)
* [Scala 3 & Functional Programming Essentials](https://rockthejvm.com/p/scala)
* [Scala & Functional Programming Interview Practice](https://rockthejvm.com/p/scala-functional-programming-interview-practice)
* [Advanced Scala 3 and Functional Programming](https://rockthejvm.com/p/advanced-scala)

## Blogs and Articles

By Martin Odersky (Artima)

* [A Brief History of Scala](https://www.artima.com/weblogs/viewpost.jsp?thread=163733)
* [In Defense of Pattern Matching](https://www.artima.com/weblogs/viewpost.jsp?thread=166742)
* [Pattern Matching Wrap-Up](https://www.artima.com/weblogs/viewpost.jsp?thread=168839)
* [Pimp my Library](https://www.artima.com/weblogs/viewpost.jsp?thread=179766)
* [The Myth Makers 1: Scala's "Type Types"](https://www.artima.com/weblogs/viewpost.jsp?thread=245183)

With Martin Odersky (Artima)

1. [The Origins of Scala : A Conversation with Martin Odersky, Part I](https://www.artima.com/articles/the-origins-of-scala)
2. [The Goals of Scala's Design: A Conversation with Martin Odersky](https://www.artima.com/articles/the-goals-of-scalas-design)
3. [The Purpose of Scala's Type System: A Conversation with Martin Odersky](https://www.artima.com/articles/the-purpose-of-scalas-type-system)
4. [The Point of Pattern Matching in Scala
A Conversation with Martin Odersky](https://www.artima.com/articles/the-point-of-pattern-matching-in-scala)

 Others

* https://www.scala-lang.org/blog/
* https://blog.rockthejvm.com/
* https://blog.softwaremill.com/tagged/scala
* https://www.lihaoyi.com/

---
## Questions and Answers 🙋

 Is Scala 3 Dotty sound?

> Dotty is a compiler for the development of Scala 3 with DOT Calculus. DOT is a type-calculus used to prove that Dotty’s language specification and its type system are sound. DOT validates the language specification correctness formally. The compiler research team has been developing this to have a core and sound understanding of the foundation of Scala 3’s type system

Sources :

* [Essence of Scala, Martin Odersky : Scala Blog](https://www.scala-lang.org/blog/2016/02/03/essence-of-scala.html)
* [Scaling Dot to Scala - Soundness, Martin Odersky : Scala Blog](https://www.scala-lang.org/blog/2016/02/17/scaling-dot-soundness.html)
* [Introduction to Dotty and Scala 3, Milad khajavi: Baeldung Scala](https://www.baeldung.com/scala/dotty-scala-3)
* [The Sound of Dotty, Scalawags with Martin Odersky](https://gist.github.com/SethTisue/79960134da77ec6f209d)

Why does Scala does not have the Hindley-Milner type system?

According to Scala's creator, Martin Odersky:
> The reason Scala does not have Hindley/Milner type inference is that it is very difficult to combine with features such as overloading (the ad-hoc variant, not type classes), record selection, and subtyping. I’m not saying impossible — there exist a number of extensions that incorporate these features; in fact I have been guitly of some of them myself. I’m just saying it’s very difficult to make this work well in practice, where one needs to have small type expressions, and good error messages. It’s not a shut case either — many researchers are working on pushing the boundaries here (look for instance at Remy’s MLF). But right now it is a tradeoff of better type inferencing vs better support for these features. You can make the tradeoff both ways. The fact that we wanted to integrate with Java tipped the scales in favor of subtyping and away from Hindley/Milner.

* [Universal Type Inference is a Bad Thing, Martin Odersky? : CodeCommit Scala Blog](http://www.codecommit.com/blog/scala/universal-type-inference-is-a-bad-thing)

---
### Reference Links

[Scala 3 docs](https://docs.scala-lang.org/scala3/)</br>
[Scala 3 reference](https://docs.scala-lang.org/scala3/reference/overview.html)</br>
[Scala 3 API](https://scala-lang.org/api/3.x/)</br>
[Scala 3 at EPFL](https://dotty.epfl.ch/)</br>
[Scala 3 docs at EPFL](https://dotty.epfl.ch/docs/)</br>
[Scala 3 blog at EPFL](https://dotty.epfl.ch/blog/index.html)</br>
[Scala 3 usage at EPFL](https://dotty.epfl.ch/docs/Usage/index.html)</br>
[Scala 3 reference at EPFL](https://dotty.epfl.ch/docs/Reference/index.html)</br>
[Scala 3 API at EPFL](https://dotty.epfl.ch/api/)
