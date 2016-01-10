# Explicit Elixir

## Abstract
> *elevator pitch - 300 character*

A functional programming background is certainly not required for Elixir but understanding a few functional principles can make your life easier and your code considerably more Elixir like.


## Description:
> *public abstract*

At first glance, Elixir looks a lot like Ruby but about 10 minutes of coding in Elixir will put a screeching halt to that idea. Erlang's functional/distributed programming background shines through in Elixir. Combined with a modern/familiar syntax and a great macro language Elixir gives us an ideal way to start down the functional programming path.

If I had to describe the Elixir Way in one word, it would be "explicit". Elixir avoids programming magic and instead strives for a clean, no surprises, style. We're going to look at a few functional concepts that help bring Explicit Elixir into perspective.


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
5. use with [maybe/maybe not, depends on time/example]
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
