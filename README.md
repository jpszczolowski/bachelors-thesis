# bachelors-thesis

The thesis is written in Polish but here you can find the translation of title and abstract to English.

## Title
An overview of synchronization methods in Unix-like kernels and an implementation of turnstiles in Mimiker OS

## Abstract
As Moore's Law ends to apply and single processors don't increase their performance
as regularly as in the past, parallel and concurrent processing is becoming more and more important today.
Such models of computation imply a lot of synchronization-related problems. In this paper we'll explain
why proper synchronization is crucial. We'll revise the core concepts of how an operating system works and
have a glance at user-space locking. However, the emphasis will be put on the next part which is synchronization
in Unix-like kernels. We will cover some details concerning implementation or typical use case.
At the end we'll see the implementation of turnstiles in Mimiker OS based on the FreeBSD source.
