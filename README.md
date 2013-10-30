escala-lib
==========

Scala library of the Escala Project

Author
------
I am **not** the author of the library, just to make that clear. All I did was
extracting it from the [original project
source](https://github.com/guidosalva/EScala) to have a small and nice
repository for it. Additionally I added some housekeeping (build automation
with SBT) and made the code compile with Scala 2.10.

Build
-----
It is recommended to use the [Scala Build Tool](http://www.scala-sbt.org/) to
compile and package the library. If you have the tool installed, just go the
base project directory and type the following on your command line:

    $ sbt clean compile package

You can then copy the packaged library from `target/scala-*/escala-lib_*.jar`.
