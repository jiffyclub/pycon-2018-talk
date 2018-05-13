# Python Performance Investigation by Example

Slides and content from my 
[PyCon 2018 talk](https://us.pycon.org/2018/schedule/presentation/136/).

## Description

Occasionally we’ll find that some bit of Python we’ve written doesn’t run as
fast as we’d like, what can we do? Performance bottlenecks aren’t always
intuitive or easy to spot by reading code so we need to collect data with
profiling. Once we’ve identified the bottleneck we’ll need to change our
approach, but what options are faster than others?

This talk illustrates a Python performance investigation and improvements using
an Advent of Code programming challenge. I’ll walk through starting from a slow
(but correct) solution, look at profiling data to investigate why it’s slow, 
and explore multiple paths for improving performance, including more efficient
algorithms and using third-party tools like Cython. You’ll leave this talk with
a recipe for analyzing Python performance and information about some options 
for improved performance.

## Notes

Talk video: https://www.youtube.com/watch?v=yrRqNzJTBjk

Slides [here](./presentation/Python%20Performance%20Investigation%20-%20PyCon%202018.pdf).

Use `snakeviz slow_mode.cprof` to see the 
[SnakeViz](https://jiffyclub.github.io/snakeviz/) profile demo'd in the talk.
(Requires Python 3.)
