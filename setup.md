## Scala Notes

### Install sbt in `unix`

$ `sdk install sbt`

### Generate a clean Scala 3 project

$ `sbt new scala/scala3.g8`

### Using Scala 2.13 libraries in Scala 3

The Scala 3 compiler is able to type check Scala 2.13 types and to resolve Scala 2.13 implicits. It means you can safely use Scala 2.13 libraries in a Scala 3 application.

This feature has been extensively tested in the Scala 3 community build for more than a year. It is now natively available in sbt by using `CrossVersion.for3Use2_13`:

```scala
// build.sbt
lazy val hello = project.in(file("."))
  .settings(
    scalaVersion := "3.0.2",
    libraryDependencies += 
      ("org.mongodb.scala" %% "mongo-scala-driver" % "4.3.1")
      .cross(CrossVersion.for3Use2_13)
  )
```

### Generate a initial ScalaFx project

$ `sbt new scalafx/scalafx.g8`
