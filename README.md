librepo
=======

Remote repository of Maven or Ivy for the libraries which don't exist in central repositories yet.

For example, in build.sbt to use this repo, you need to write a line,

```scala
resolvers += "Neko repo" at "https://raw.githubusercontent.com/nekopiano/librepo/gh-pages/maven"
```
or
```scala
resolvers += "Neko repo" at "http://nekopiano.github.io/librepo/maven"
```
