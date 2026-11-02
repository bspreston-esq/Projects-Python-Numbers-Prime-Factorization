# Prime Factorization

**Category:** Numbers

## Problem

Have the user enter a number and find all Prime Factors (if there are any) and display them.

## Solution

Trial division by 2 and then by odd candidates up to the square root, collecting multiplicities as (prime, exponent) pairs. Runs in O(sqrt(n)) time.

## How to run

Requires Python 3.8+ and no third-party packages.

```bash
python3 main.py        # prompts for an integer
python3 main.py 360    # non-interactive
python3 main.py --demo
```

## Example

```text
12 = 2^2 x 3
     97 = 97
    360 = 2^3 x 3^2 x 5
   1001 = 7 x 11 x 13
 999999 = 3^3 x 7 x 11 x 13 x 37
```

## Attribution

The problem statement is from [karan/Projects](https://github.com/karan/Projects), a list of practical projects that anyone can solve in any programming language (MIT License, Copyright (c) 2013 Karan Goel). The Python solution in this repository was implemented by [bspreston-esq](https://github.com/bspreston-esq).

This repository is part of the [Projects-Python-All](https://github.com/bspreston-esq/Projects-Python-All) collection.
