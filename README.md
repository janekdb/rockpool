rockpool
========

High performance, well documented JDBC connection pool coded in Scala

Licence
=======

rookpool is licensed under the Apache License, Version 2.0. A copy of the license is
included as 'LICENSE-2.0.txt'.

Build Details
=============

rockpool is built with Gradle 1.4.

To build and run the unit tests execute this command from within project directory,

    gradle build

To generate Eclipse project files run the eclipse task,

    gradle eclipse

Language Choice
===============

rookpool is written in Scala, initially against the 2.10.1 Scala release.

Testing Libraries
=================

rookpool tests are written in ScalaTest (initially 1.9.1). For more details regarding ScalaTest
please take a look around the ScalaTest web site at http://www.scalatest.org.

Design Constraints
==================

rookpool is developed under the "Rule of Five". This design rule mandates that no class, trait or
object may have more than five methods and fields in total. So an object with four methods and one
field is permitted while a class with three methods and three fields is disallowed.


