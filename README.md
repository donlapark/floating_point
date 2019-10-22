# Floating Point Repository
This repository was created in order to contain work related to floating point precision
problems in differentially private mechanisms (hence the very general repository name).
As of now, this is just my implementation
of the snapping mechanism introduced in [Mironov (2012)](http://citeseerx.ist.psu.edu/viewdoc/download?doi=10.1.1.366.5957&rep=rep1&type=pdf).

<hr>

## Snapping Mechanism
The snapping mechanism is a differentially private mechanism designed to address the vulnerabilities that arise when implementing the laplace mechanism
with floating point numbers.

<hr>

## Implementation
The implementation of the snapping mechanism is [here](./implementation/cc_snap.py).

<hr>

## Notes
The original [Mironov (2012)](http://citeseerx.ist.psu.edu/viewdoc/download?doi=10.1.1.366.5957&rep=rep1&type=pdf) focuses primarily on theory, rather than 
how to use/implement the snapping mechanism in practice. The [notes](./notes/snapping_implementation_notes.pdf) document both provides a bit of background 
on the snapping mechanism and details considerations that were made during the implementation.

<hr>

## State of Completion
The python implementation is more-or-less complete at this point, though it has not been thoroughly vetted. 
I do not currently recommend that anyone use this for sensitive data, though it is my goal to get it to this level.

The notes section is a work in progress and has been partially vetted.