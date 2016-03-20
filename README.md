# List of Scala resources

## For documentation

- typechecked, runnable documentation: [Tut](https://github.com/tpolecat/tut)
- bare-bones integration example with gh-pages: [Indoctrinate](https://github.com/stew/indoctrinate)

## Mathematics

For algebraic typeclasses and data structures, I use [Spire](https://github.com/non/spire).

The current version is 0.11.0 and depends on the following:

```scala
Seq(
  "org.typelevel" %%% "machinist" % "0.4.1",
  "org.typelevel" %%% "discipline" % "0.4", // for the exported laws project
  "org.scalacheck" %%% "scalacheck" % "1.12.4", // for the exported laws project
  "com.chuusai" %% "shapeless" % "1.2.4" % "test", // only in non-exported tests
  "org.scalatest" %%% "scalatest" % "3.0.0-M7" % "test",
  "com.chuusai" %% "shapeless" % "2.2.5" % "test"
)
```

I try to align my own libraries with a specific Spire version.
