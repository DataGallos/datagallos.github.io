---
layout: post
title: Our Journey Setting Up the Scala Development Environment
---
By: [Jose Arturo Mora Soto "Jams"](https://twitter.com/jarturomora) & [Alejandro Garcia "El Viejo"](https://www.facebook.com/elviejo79)

We started our journey in Data Engineering one year ago using R, Python and most recently Octave. Those languages are quite good to create models and data science prototyping, however we decide to start using really BIG datasets, concurrent and parallel programming; under these new requirements we saw that our current programming skill-set was not enough, so after some research and peer-talking with some colleagues we decided to get into Scala, a functional programming language that runs under the Java Virtual Machine.

At the beginning we were skeptical about using Scala since we didn't want to deal with the complexity of installing "java-based stuff" neither using any IDE like Eclipse, nevertheless after watching the videos from Martin Odersky on his Coursera Course "Functional Programming Principles in Scala", we decide to start our journey with two conditions:

1. El Viejo will never use Eclipse, instead, he will use Emacs.
2. Jams will follow Odersky's recommendations "as is", including using Eclipse.
3. We both will work under Ubuntu Linux.

When we started using R, Python, and Octave, start using them was as easy as type ```sudo apt-get install package```, these installs takes just up-to five minutes, unfortunately, until now we have spent more than four hours and we aren't still able to run Scala following the guide provided in the Odersky course, we are a little bit frustrated now about the need to spend a whole day just to setup a development environment.

As soon we were able to run Scala as we want we will share a step-by-step guide to do it under Ubuntu.
