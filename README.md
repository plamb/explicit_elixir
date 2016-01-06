# Explicit Elixir

## Abstract
> *elevator pitch - 300 character*

A functional programming background is certainly not required for Elixir but there's certainly
some areas that can make your life easier and your code considerably more Elixir like.

-OR-

At first glance, Elixir looks a lot like Ruby but about 10 minutes of coding in Elixir will put
a screeching halt to that idea. We're going to look at a few of the common areas that cause developers
issues as they approach and mature in Elixir coding.

## Description:
> *public abstract*



## Notes
> *for reviewers*



## Outline
0. code should tell a story
  1. pipelines
1. pure functions
  1. small
2. user more pattern matching,
  1. if a param needs to be something, pattern match and/or guard it
3. use more map/reduce,
  1. for isn't as awful in elixir and gets rewritten as map
4. if can get smelly quickly
  1. very short things only
  2. no new variables or assignment
  3. treat as expression that returns a value
  4. just avoid unless
5. use with
  1. refactor nested case


## Notes
params that must/should be a thing, should specify that thing

 https://twitter.com/mat_mcloughlin/status/680869453446393856
  Most important lesson of software development. It always depends

https://twitter.com/joeerl/status/680670648373481473
+ choose accurate names
+ favor beauty over performance
+ design minimal essential API's
+ document the unobvious

What is Functional Programming http://blog.jenkster.com/2015/12/what-is-functional-programming.html


### Setup

Presentation is based on reveal.js, to get all features including speaker notes
the full setup was done (clone repo, renamed repo, npm install) use
```cmd
grunt serve
```
to start the embedded webserver to display presentation.
