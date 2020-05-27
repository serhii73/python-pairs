# python-pairs

A SICP'ish Functional Pairs implemented in Python.

## Usage

<!-- This code will be doctested. Do not touch the markup! -->

    >>> from hexlet import pairs
    >>> p = pairs.cons(42, 'foo')
    >>> pairs.is_pair(p)
    True
    >>> pairs.car(p)
    42
    >>> pairs.cdr(p)
    'foo'
    >>> print(pairs.to_string(p))
    (42, 'foo')

[![Hexlet Ltd. logo](https://raw.githubusercontent.com/Hexlet/hexletguides.github.io/master/images/hexlet_logo128.png)](https://ru.hexlet.io/pages/about)

This repository is created and maintained by the team and the community of Hexlet, an educational project. [Read more about Hexlet (in Russian)](https://ru.hexlet.io/pages/about).
